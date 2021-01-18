# OpenCombat Design Document

<img alt="Latex" width="32px" src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/ec/Antu_texmaker.svg/512px-Antu_texmaker.svg.png" />

<br />

![](/images/OCGD1024_1.png)

## Table of Contents
- [OpenCombat Design Document](#opencombat-design-document)
  - [Table of Contents](#table-of-contents)
  - [Background](#background)
  - [Process](#process)
    - [Setting Up LaTeX](#setting-up-latex)
    - [Defining the Scope](#defining-the-scope)
    - [Creating the World](#creating-the-world)
    - [Designing the Mechanics](#designing-the-mechanics)
    - [Generating Revenue](#generating-revenue)
  - [Reflections](#reflections)



## Background

As a graduate student at Savannah College of Art and Design, I was tasked with drafting the documentation for a game of our choosing. I chose to design an open-source platform fighting game with an emphasis on community building.

## Process

### Setting Up LaTeX

Since I needed to cite my sources in the documentation, I chose LaTeX so that process would be automated. I used [TeX Live](https://tug.org/texlive/) to get all the tools I needed to compile my LaTeX into a document with citations and used [James Yu's LaTeX Workshop plugin for Visual Studio Code](https://github.com/James-Yu/LaTeX-Workshop) to assist in compilation and previewing.

The document is `letterpaper` size, uses `11pt` font and has `.75in` margins. The citations use the Chicago 17th Edition style and the font was made sans-serif to make the document more visually-appealing overall.

```tex
\documentclass[11pt, letterpaper]{report}

\usepackage[margin=0.75in]{geometry}
\usepackage[backend=bibtex, bibstyle=authortitle, citestyle=verbose, autocite=footnote]{biblatex}
\usepackage{graphicx}

\renewcommand{\familydefault}{\sfdefault}

\title{\textbf{OpenCombat Design Document}}
\author{Devon Ducharme}
\date{Savannah College of Art and Design - ITGM 706 01 - Winter 2020}
\bibliography{bibliography} 


\begin{document}
    \maketitle
    \tableofcontents
    \input{chapters/01-overview.tex}
    \input{chapters/02-intellectual-property.tex}
    \input{chapters/03-mechanics.tex}
    \input{chapters/04-revenue.tex}
    \printbibliography
\end{document}
```

### Defining the Scope

The course in which I was tasked with this project, Game Design Documentation, was only ten weeks long and as such the scope of the game's design needed to reflect that. The game's mechanics as a result borrowed much from other platform fighting game such as [Super Smash Bros. Melee](https://en.wikipedia.org/wiki/Super_Smash_Bros._Melee) and [Rivals of Aether](https://en.wikipedia.org/wiki/Rivals_of_Aether). My design goal for the project was to create an open-source platform fighting game that could be played casually and competitively.

To embody the spirit of community, the game was designed to be cross-platform, not be too resource demanding and be easily accessible via download or package manager. The game was targeted at weaker computer hardware in order to make the game more accessible to those who may not be able to afford computers with game-optimized components. 

### Creating the World

My goal when creating the world of OpenCombat was to balance familiarity with uniqueness. I started by researching the intellectual properties of games I had been exposed to by playing game in the past as well as various historical periods in order to find a combination that could be a compelling direction. Inspired by the [Mean Streets of Gadgetzan expansion of Hearthstone](https://en.wikipedia.org/wiki/Gameplay_of_Hearthstone#Mean_Streets_of_Gadgetzan), I decided on a fantasy world set in modern times with an expanded set of animal-themed races to add variety to the lore.

Since the intellectual property was set in time similar to our current time, I centered the narrative around themes occurring in our society today such as corporate greed and exploitation. Although those topics can be heavy and depressing, I created comedic characters such as De'Dra Orgur and Rufus Wigglebottom to balance out those elements with a splash of humor. The concept art I used as part of my research of the intellectual property was scattered through-out the document to add visual appeal and further communicate the desired aesthetic.

![](/images/OCGD1024_20.png)

### Designing the Mechanics

As mentioned previously, the game was designed with the platform fighting mechanics of games such as [Super Smash Bros. Melee](https://en.wikipedia.org/wiki/Super_Smash_Bros._Melee) and [Rivals of Aether](https://en.wikipedia.org/wiki/Rivals_of_Aether) in mind. Rather than simply copy all the mechanics from each game, I chose to refine them in two keys ways:

1. Additional attack options were offered such as strong aerial attacks and alternate specials in the air.
2. Health replaced percentages as the damage mechanics so that stocks/lives could be replaced with rounds.

These changes were made in order to introduce more traditional fighting game mechanics into the genre. Additionally, the transition to rounds from stocks makes comebacks more possible by providing a damage reset without giving the losing player an advantage since they would still need to out-play their opponent in the new round to make a comeback.

Rather than choosing a character to play, players must create a custom character from one of several classes. These classes each have different move-sets and are designed around various archetypes. The goal of including this feature was the allow the player to express themselves not only in play-style but also in aesthetic.

The community tool was designed to reward players for engaging with each other and the brand by unlocking content once a shared experience point pool hit a certain threshold. The goal of adding this feature was to incentivize players to work together towards a shared goal and to engage with one another in a meaningful way. To reflect this, more points are awarded for multiplayer interactions than purchases or solo content. 

### Generating Revenue

As a free-and-open-source (FOSS) project, generating revenue from the project presented unique challenges. Although some FOSS projects are sustained through donations, developing a video game offered unique opportunities to finance the project. Researching how popular intellectual properties were primarily financed, I discovered that a significant amount of revenue was generated from merchandise. As a result, the revenue section of the documentation leans heavily towards the sale and distribution of merchandise. Donation drives at tournaments and other in-person events would also be a source of revenue since these types of events are often live-streamed on the Internet to large audiences.

## Reflections

This project is a continuation of a long passion project I have had since first becoming interested in game design as a field of study. The idea for this platform fighter has evolved from including super heroes to having custom characters, from being 3D to 2D, from being exclusive to one platform to being multiplatform, etc. This idea will likely always continue to evolve until I program a prototype of it. At the time of writing this reflection, my goals for this project have significantly changed and with it my perspective.

The open-source angle, although well-intended, is not an angle I would pursue should I reimagine this project. While it did allow for the community to engage with the developers in ways that could shape the code of the game itself, it also opened up the possibility for malicious builds and limited the possibilities for purchasable downloadable content. Rather than develop the game as a FOSS project, the better solution would be to provide a FOSS mod development SDK to allow players to extend the games functionality while also having all the advantages propriety software includes.

The aspect of this design that I am most proud of is the community organizing features. Whether or not it is explored in projects of a similar nature to this one in the future or not, reward players for engaging with one another through shared rewards is an opportunity that could be worth exploring in the future. Additionally, the research done into how to generate revenue for the game was a useful exercise for me because I am now more aware of ways to make money from a game.