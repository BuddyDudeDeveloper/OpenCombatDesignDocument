# Overview

## Title

OpenCombat

## Authors

Devon Ducharme

## Genre

2D Platform Fighting Game

## Theme

When ordinary people come together, they can do extraordinary things.

## Philosophy

At the heart of OpenCombat lies its theme. The game's narrative is centered around combatants starting as normal entrants to the tournament and ends with them teaming up to defeat the business interests that seek to profit at the expense of society. The free and open source nature of the project allows the community to contribute to bug fixes, create mods and be part of testing future builds. Built into the game is the community management tool which seeks to bring people physically together to have shared experiences around OpenCombat.

## Value Proposition

OpenCombat offers many benefits to players as well as the community that surrounds them. Players can easily access the game and play it on any computer, making it a great choice for parties, small gatherings or personal play. Since it is built on a platform fighting game core, players will easily be able to jump in and engage with the experience even if they are never played it due to the accessibility of inputs. The open source nature of the game allows them to extend the experience as they see fit with mods and plugins they make themselves or acquire from the community. Tournament organizers of platform fighting games will appreciate the ability to easily obtain, install and modify any version of the game they wish. The community organizing tool also serves as a centralized spot for planning and hosting events which is ideal for players or TOs who organize gatherings.

## Goals

1. Design a community-driven game in which the experience in-play matters as much as the experience around-play.
2. Develop an implementable crowdfunding model to decouple game development from venture capital.
3. Experiment with cooperative open source development between a centralized team and the community.

## Engine

[Godot Engine][godot-link]

## Hardware Requirements

### Platforms

- Windows (10+)
- macOS (10.15+)
- Ubuntu (18.04+)

### Minimum Specifications

#### CPU

- Intel Pentium D
- AMD Athlon 64 X2

#### GPU

- NVIDIA GeForce 8600 GT
- ATI Radeon HD 2600XT

#### RAM

- 2 GB

## Distribution Methods

- Website
- GitHub repository
- Package managers

# Schedule

### v0.1

Q4 2020

#### Features

- Playable matches with customizable rules.
- Local and online matchmatching.

### v0.2

Q1 2021

#### Features

- Character customization and rewards.

### v1.0

Q3 2021

#### Features

- Community organizing tool.

## Marketplace Analysis

### Target Audience

As a free-and-open-source game, the barrier of entry of OpenCombat is virtually non-existent and as such a broad audience is expected. However, OpenCombat is targeted at players who exhibit some or all of the following characteristics:

- Young adults just starting university or post-secondary careers.
- Likely own a laptop for school and/or work but not a gaming computer.
- Likely have friends over from time-to-time for couch gaming or watching sessions.
- Likely to pirate shows, movies, music and games not accessible to them.
- Unapologetic about plugging their laptop in a TV and using it as a media station, gaming device, etc.

### Competitive Analysis

#### Super Smash Bros. Ultimate

![ultimate-gameplay]

##### What Works Well

- The roster is massive and has many characters from prominent franchises including ones not owned by Nintendo.
- Inputs to perform attacks are simple, intuitive and consistent across all characters.
- Rules are flexible allowing for both casual and competitive experiences.
- Plethora of additional modes that all utilize platform mechanics.
- Picking the stage before characters prevents players from picking stages that disadvantage the other player.

##### What Could Be Improved

- Stages are too large which often results in slower matches.
- Although movement had been made faster from the two previous titles in the series, the lack of momentum in movement makes it difficult for characters to navigate platforms quickly.
- Although updates are free, additional downloadable characters and stages require purchasing.

#### Super Smash Bros. Melee

![melee-gameplay]

##### What Works Well

- The roster is mid-sized but has many characters from prominent franchises.
- Inputs to perform attacks are simple, intuitive and consistent across all characters.
- Rules are flexible allowing for both casual and competitive experiences.
- When mastered, movement is relatively fast and smooth.
- Plethora of additional modes that all utilize platform mechanics.

##### What Could Be Improved

- Stages are too large which often results in slower matches.
- The tech skill required to play this game at a competitive level is high and even [dangerous to the health of players' hands][espn-hax-injury].
- Stage hazards cannot be turned off causing debate in the competitive community about which stages should be legal.

#### Rivals of Aether

![rivals-gameplay]

##### What Works Well

- Inputs to perform attacks are simple, intuitive and consistent across all characters.
- When mastered, movement is relatively fast and smooth.
- Minimal lag on attacks and landing.
- The stages are unique enough to be different from one another but balanced enough to be used for competitive matches.
- Although the roster is small, each character feels unique.

##### What Could Be Improved

- There no items or rule adjustments to play casually.
- Although updates are free, additional downloadable characters and stages require purchasing.
- Stages are too large which often results in slower matches.

#### Brawlhalla

![brawlhalla-gameplay]

##### What Works Well

- Inputs to perform attacks are simple, intuitive and consistent across all characters.
- When mastered, movement is relatively fast and smooth.
- Minimal lag on attacks and landing.
- The stages are unique enough to be different from one another but balanced enough to be used for competitive matches.

##### What Could Be Improved

- Although the game is free-to-play, various components of the game require in-game purchases.
- Stages are too large which often results in slower matches.

## Revenue

### Donations

As a free and open-source community-driven game, the primary revenue source for OpenCombat will be sustained or singular donations through platforms such as [Patreon][patreon-link]. Current revenue models, such as pay-to-play and in-game purchases, often require players to make repeated or costly financial commitments in order to maintain enjoyment, consistency or access to the experience. Community-funding mitigates this issue at the expense of short-term revenue.

### Merchandising

The intellectual property of the game can be utilized to generate additional revenue through sales of clothing, figurines and other merchandise. As the game for the community grows, the cultural aspects (such as memes or jokes) can be applied to the merchandising. The game's soundtrack can be available on [Bandcamp][bandcamp-link].

### Sponsorships

Companies or individuals can sponsor OpenCombat through single or sustained contributions. By doing so, billboards, posters and other in-game advertising materials will have their brands on them adapted for the style of the game. For example, if Pepsi were to sponsor OpenCombat, there may be a billboard in the background of a stage that shows an advertisement for Pepsi with an NPC on it.

### Community eSports Drives

During large eSports events for platform fighting games, such as Genesis and EVO, donation drives can be launched to encourage players to contribute. At these events, the donations can also serve as a way of increasing the prize pool for participants.

# Gameplay

## Overview

OpenCombat is a free and open-source 2D platform fighting game where players punch, kick, grab, block, dodge and use their super powers to knock out all their opponents in intense and fast-paced battles across diverse arenas. Players can embrace the chaos by fighting 4v4 free-for-alls with items _(generously provided by the audience)_ or show off their skills in competitive 1v1 matches; the rules are completely customizable in both offline and online play. Players can also create their own combatants and choose from 1 of 4 different classes each with their own unique set of moves. By completing objectives and playing matches, players will earn badges that they can proudly display on their profile.

At the core of OpenCombat is the players and their experiences inside and outside the game. OpenCombat is free and all subsequent updates will also be free requiring no monthly subscriptions or purchases to acquire new content. Since the game is open source, players can create plugins or take part in helping to add new features, fix bugs or balance gameplay. One of the essential experiences of fighting games is coming together with others and playing multiplayer locally; players can use the in-game community organizing tool to host or attend events in their area.

## Combat

### Overview

Similarly to other platform fighting games, OpenCombat matches are fought on stages with varying platform layouts between 2 to 4 players. Players coming from the previously mentioned games will be familiar with the simple button-and-direction execution of actions. These actions include:

- Neutral attack, throw item (A with or without direction)
- Special attack (B with or without direction)
- Strong attack (X with or without direction)
- Jump (Y)
- Block (L2 or R2 without direction)
- Dodge (L2 or R2 with direction)
- Grab (L1 or R1)
- Taunt (D-Pad)

The OpenCombat experience distinguishes itself from these titles by including new actions and mechanics from 2D traditional fighting games such as:

- Stocks and percent are replaced with rounds, matches and stamina from traditional fighting games.
- Specials and strong attacks, like neutral attacks, have an aerial variation.
- Knockback and stun are significantly reduced and do not scale with damage.

Players will utilize all of these actions in order to be the last one remaining. Players can block incoming players' attacks, grab their blocking opponents to catch them off-guard or seize the opportunity to strike if they try to grab them. Players can also take advantage of the unique platform layouts of each stage to put themselves in a position to take the upper hand. Players are eliminated when their stamina reaches 0 or they have been knocked out of the ring.

The players have complete control over the rules they choose to play with whether they are playing offline or online. Some of these options include:

- Rounds
- Stamina
- Items
- Teams
- Physics

### Items

The audience of a match can throw items into the arena for combatants to use. The audience is usually tame and only throws items into the ring if they have a reason.

#### Concessions

If the combatants bore the audience by not attacking each other for a while, they will start throwing their trash into the arena. Clever combatants can pick up the ones that don't explode and throw them at their opponents for light amounts of damage.

#### Underwear

When one of the combatants successfully pulls off a taunt, some of the more zealous fans in the audience will throw their boxers, bras, briefs and panties into the arena. Combatants have to be careful though because the smell of the underwear can cause small incremental damage to those close by. Underwear can be thrown but they have little to no momentum.

#### Confetti F-Bombs

When one of the combatants in a match with 3 or more is eliminated, the audience pays their respects by throwing confetti bombs shaped like the letter F into the arena. Combatants can try to catch them as they fall but if they fail to do so, they explode on impact for massive damage.

#### Headphones

When a Berserker is getting beaten badly, a pair of headphones is thrown into the arena that, when picked up, play an enraging voice line. The combatant who heard it gets a temporary strength and speed boost.

Some of the voice lines that will be played include the following:

- It's pronounced "jif."
- Your favorite anime is trash.
- Pineapple doesn't belong on pizza.
- Always put the ketchup on top of your fries.
- Pour the milk in the bowl before you add the cereal.
- Water is not wet.
- Hot dogs are sandwiches.
- You want to listen to my mixtape?
- I brush my teeth without wetting the bristles.

#### Tome

Concerned that their favorite mage combatant is losing, the audience will start throwing in tomes to help them out. Since combatants don't have time to study the text, they can use it as a heavy projectile to toss at opponents.

#### Ale

When a sailor is losing in combat, the audience will start tossing ale into the arena to help them out. Drinking the ale will slow down the player's attacks but make them more powerful; they can also toss the empty bottle at opponents for moderate damage.

#### Treats

The allies of druids will toss animal treats into the arena if the Druid is losing. When consumed, these treats restore a little health and the empty bag can be tossed at opponents for light damage.

#### Battleaxe

To the shock of many, someone in the audience was allowed to bring in a battleaxe and tosses it into the arena when heavies are losing. Only large fighters can pick up the axe and although it does not move quickly or go far when thrown, it deals a lot of damage on impact.

#### Zen Grass

The audience will toss in a jar of zen grass if their favorite monk is being beaten. Regardless of who picks this up, everyone is slowed down temporarily.

## Matchmaking, Player Profiles and the Community Organizing Tool

Players can fight it out online in private matches or by using online matchmatching. When players first start the game, they create a local profile that is used to keep track of their wins, losses and other in-game data. These profiles can be synced to an optional online account so players can simply log in and have access to their information from anywhere. At any point, the player can choose to reset their progress and have their data deleted.

The community organizing tool is designed for every type of user from the college sophomore looking to have some friends over to the tournament organizer preparing for a large event. Organizers can post information about their event, track attendance, setup brackets and quickly communicate with all parties involved to coordinate without needing social media or external services. The average player will find the community organizing tool to be a helpful way to plan ahead for social gatherings as well as find local events to play at. To encourage players to come together and plan community events, player profiles will have a community level where experience is gained from playing matches at community events, hosting events and being commended by your fellow players for sportsmanship, teamwork, positivity, etc.

## Custom Combatants

Players can create their own custom combatant based on 1 of 4 classes. They can customize their physical appearance, clothing and biographical information. Each of these classes come with their own movesets, strengths and weaknesses.

### Playable Classes

#### Mage

##### Archetype

Zoner

##### Body Size

Medium

##### Description

Combatants who can wield the arcane arts use it to control the space around them and keep their opponents away. Although these fighters move on the ground at a moderate speed, they are able to better control their aerial movement despite their average weight. While they are great at keeping slower opponents away, they are weak against opponents that can rush and attack them.

#### Sailor

##### Archetype

Grappler

##### Body Size

Medium

##### Description

From the sea to the shore, sailors are the undisputed masters of the cutlass and hookshot. Their average mobility, power and speed are offset by their ability to pull distant opponents towards them. The sailors' hookshots give them a distinct advantage over range opponents but they can be easily be overwhelmed by faster fighters.

#### Berserker

##### Archetype

Rushdown

##### Body Size

Small

##### Description

Wielding small axes and a thirst for blood, Berserkers are able to harnass their rage to overwhelm their foes. They are the quickest combatants on the ground and are able to rush into combat easily. This makes them adept at navigating around projectiles to smother distance-based opponents, however, they have difficulty with large or armored opponents.

#### Monk

##### Archetype

Aerial

##### Body Size

Small

##### Description

Using paragliders and karate, these combatants maneuver smoothly in the air and fight from the skies. Their extremely light weight helps them escape combos easier but their ground combat skills and grappling leave much to be desired. They excel against large and slow opponents but can easily be overwhelmed by ranged attacks or easily smothered by fast fighters.

#### Druid

##### Archetype

Grappler

##### Body Size

Large

##### Description

The combatants most in-tune with nature leverage its power to transform parts of their body into various flora and fauna. Whether it is grabbing their opponents with talons or protecting themselves with tree bark, these combatants are renowned for their ingenuity in combat. Although they can smother smaller opponents with their strength, ranged and aerial opponents can easily outmaneuver them.

#### Heavy

##### Archetype

Rushdown

##### Body Size

Large

##### Description

Equipped with the largest armor and weaponry they could find, these combatants pride themselves on their ability to withstand damage. Their speed is the slowest of all the combatants but they also do the most damage with their massive strikes. Their lack of dexterity leaves them vulnerable to grappling opponents but their armor makes them resiliant against small and fast foes.

### Races and Body Sizes

| Small  | Medium |  Large  |
| :----: | :----: | :-----: |
| Gnome  | Human  |  Kong   |
| Dwarf  |  Orc   |  Troll  |
| Goblin |  Elf   | Goliath |
| Corgo  | Purrs  |  Drake  |

# Flow

## Match

![flow-match]

## State Machine

![flow-states]

# Story

## Setting

Modern Fantasy

## Tone

- Light-hearted
- Comical

## Overview

Prosperity is a bustling cityscape populated by fantasy creatures of all shapes and sizes. The city's newest attraction is a large arena with plentiful seating and amenities funded by one of the city's monopolists. To celebrate the grand opening, the arena is hosting the city's first ever combat tournament. People from all walks of life have flocked to the city to either prove they have what it takes to win or to watch the spectacle. As the player progresses through the tournament, they discover that the monopolist and his cohorts are stealing the powers away from the most powerful defeated combatants and trying to mass-produce them as consumable potions. The player will ultimately stop the company and become the first champion of the tournament.

## Conflict

There are two central conflicts in the narrative:

1. Competing against others to become the first tournament champion.
2. Stopping the monopolist from selling the powers of defeated combatants.

## The World

### Outside Prosperity

The world outside the walls of Prosperity is in a state of massive change. For as long as history has been recorded, kings and emperors ruled over their race and any races from kingdoms they had conquered. This system fell apart, however, 15 years ago when the human kingdom invaded the orc kingdom and started the the War of Warm Thrones named because poor people were being sent off to fight and die while kings and nobles were able to stay home. After every other world power, except the Republic of Prosperity, joined in the conflict and after 5 years of stalemates and pointless violence, the citizens of the world became tired of killing their neighbors. The conscripts rose up, ending the war between the kingdoms but starting new ones inside each kingdom.

The rebellion that resulted from the War of Warm Thrones resulted in a shift in the geopolitics of the world. The gnome and dwarf kingdoms were the first to fall, being replaced with an autocratic communist state called The Tinkerer's Commune. After the orc kingdom fell to a nationalist military dictatorship and became The Dawning Empire, the troll and goblin kingdoms were quickly absorbed. The human kingdom, meanwhile, was able to survive but only if the king was willing to adopt a constitution which, alongside the Elf and Goliath kingdoms, formed The Commonwealth. The kingdoms of the corgos, purrs, kongs and drakes united during the war and became the Imperium Animalia.

### Prosperity Itself

The Republic of Prosperity is a bustling city-state that allures people from around the world with its promise of a fresh start and opportunity for all. Legend has it that the city was founded around 200 years in the past by humble merchants from various kingdoms who were so sick of having to deal with unreasonable and unfair taxation; this led the dwarven merchant Lorenzo Wealthcovet to buy the land where the city-state sits today. Historians, however, question the authenticity of the legend and argue that Wealthcovet and the other merchants avoided taxation not because they thought the taxes were unfair but rather that they wanted more power within the kingdoms and the monarchs denied them.

The city itself is a bustling cityscape with a vibrant nightlife, diverse populace and modern amenities. After the War of Warm Thrones, the city became a place for refugees, deserters and merchants to come and continue on with a quiet and peaceful life. The streets of the central district are lined with jazz bars, small stores and lavish hotels. After the sun sets, the bars are filled with patrons from around the world and all different walks of life. The city's business tycoons, a group of self-made people and inherited wealth, own the vast majority of the businesses in the district as well as the businesses that serve the needs of those businesses such as distilleries, cleaning services and protection services.

What the historians and common folk of Prosperity can agree on is that the city-state does not live up to its name. Business tycoons own massive monopolies that use their capital to bribe government officials, get lucrative contracts and enrich themselves at the expense of society. Most of the working class people in Prosperity work for the city's monopolists and although they put on a smile when they work the central district, they leave tired and underpaid. The corruption and neglect in Prosperity's poorest neighborhoods is so rampant that organized crime has been able to take over the streets. This is the backdrop behind which the new arena is being built.

## Races

### Small

#### Gnomes

The gnomes are a short people who populate hills, forests and caves alongside the drawves. A humble people, they are best known as being the punchline in jokes made about height. What they do not have in size, however, they make up for with their wit. Most gnomes pursue higher education such as engineering or magic school while the most brave learn the art of combat despite their size disadvantage.

#### Dwarves

A proud and noble race, these long-bearded, stout people developed the Berserker fighting style and have since exported it to the world. Like their gnomish cousins, dwarves primarily live in mountainous areas. On average, most dwarves like to pursue blacksmithing or military service however some choose to pursue the life of the Monk.

#### Goblins

These plains people are best known for their short stature and long ears. Traditionally merchants, Goblins are also well known for their exceptional sense of fashion and engineering skills. Unlike other races of their size, they prefer to live in flatlands where they can build trading posts and small towns.

#### Corgos

The small Corgi people are known as being the most adorable people on the planet but also the most peaceful. Before it was absorbed into Imperium Animalia, the kingdom of the Corgos had only use their Monk fighting style to defend their homes. The most notable contribution to the world was Zen Grass, a plant that is smoked and consumed for medical or recreational purposes. Most Corgos pursue the ways of the Monk but also have a strong tradition of cooking and performance art.

### Medium

#### Humans

The most populace of all the races, humans lived all across the world but were largely centered around rivers and lakes. Arrogant yet driven, humans pride themselves on overcoming any obstacles that lie before them. Humans have a broad range of occupations they typically pursue but they are most often sailors, mages, musicians and politicians.

#### Orcs

The orcs originated from complex cave societies and developed a culture that valued strength as well as honor. Primarily miners, blacksmiths and military officers, orcs are exceptional at physical tasks and also make for expert builders. Their architecture, monuments and other constructs have served as inspiration for other societies around the world.

#### Elves

The race that introduced magic to the world, elves are an elegant people that originated from mountainous regions. Known for their goldsmithing, jewelry and art, the elves also mastered the arcane arts and were pacifistic. Today, most elves are academics, adventurers and can often be tending the wounded as nurses or doctors.

#### Purrs

The feline people of the Purrs thrived in jungles alongside the kongs for most of recorded history. Quick, nimble and intelligent, purrs built their societies in the canopies of the trees and are considered to have a strong engineering tradition. In modern times, purrs expert building skills make them great sailors.

### Large

#### Kongs

The large, gorilla people of the jungle lived alongside the purrs in peace for most of recorded history. Like the purrs, they also lived in treetop societies however their constructions were much larger and utilitarian than the purrs' elegant designs. They were the race that spread the Druid arts to the world and today largely serve as Druids, builders, bodyguards and academics.

#### Trolls

Trolls are most well-known for two things: their tusks and their size. These towering being are close cousins of the orcs and also lived in cave societies. Their raw strength makes them most suitable for mining, building, blacksmithing and military service but they are also proud writers and artisans. Their blacksmithing abilities have allowed them to create resilient but heavy armor that is used by the strong races of the world.

#### Goliaths

These towering cousins to humans have lived along them on river settlements that were peaceful and prosperous. Despite their size, goliaths prefer to stay out of combat and focus on the arts, woodworking, construction and cooking. There is a strong tradition of Druids in early goliath societies as well but those who served in combat often did so as heavily-plated fighters.

#### Drakes

Bearing a striking resemblance to dragons, Drakes are more humanoid than their look-alike and also do not have wings. They also lived atop the mountains like the Corgo did however they were never able to successful capture any Corgo lands. Although the Drake tradition emphasizes war, not all take the path of their claymore-wielding ancestors; some have chosen to live peaceful lives as Druids, merchants and stonemasons.

## Non-playable Characters

### Molten Mic

#### Race

Mech

#### Gender

N/A

#### Age

12

#### Physical Appearance

##### Height

6ft, 7in.

##### Weight

637lbs

##### Characteristics

- He has veins filled with lava.
- His eyes glow orange from the lava-flow.
- His metal plating is black and thick with cracks that show the light from the flowing lava.
- His big belly is engineered to also serve as a speaker.

#### Personality

- Outspoken
- Blunt
- Prideful
- Sarcastic
- Humorous

#### Background

Molten Mic is an award winning rapper and activist best known for his hit singles _Zen Grass and Goliath Ass_, _No Shame_ and _masters = null;_. Constructed as a speaker mech for a dwarven rap duo, Molten Mic escaped servitude and took to the underground rap scene in Prosperity. His flows spoke to the working class people of Prosperity and he would eventually become the most popular rapper in the city. When he is not rapping, Molten Mic is a advocate for mech rights and the rights of the working class people in Prosperity.

#### Role

Molten Mic was hired by Mr. Peels to be the first commentator in the tournament's history. His rough-around-the-edges style makes him a fan favorite and his commentary is legendary. Molten Mic has no problem using his podium to say exactly what he thinks about the match. Some of the comments he will make in-match include:

- "Holy shit, leave the little one alone!"
- "G.O.N.E. GONE!"
- "That combo was some fresh shit!"
- "Damn, my ass could feel that from up here and I don't have nerves."
- "Now THAT is an ass-whooping."
- "They don't pay me to talk about y'all wasting time; attack each other, dammit!"
- "Good thing I didn't bet my mortgage on _that_ one."
- "Do it to 'em!"
- "Whoever tossed that Zen Grass into the arena: bring some up to the podium, please and thank you."

### Eugene Esquire Peels IV

#### Race

Kong

#### Gender

Male

#### Age

36

#### Physical Appearance

##### Height

6ft, 2in.

##### Weight

512lbs

##### Characteristics

- He always dresses up in a button-up shirt with a tie.
- He is almost always smiling.
- His fur is dark grey and very finely groomed.

#### Personality

- Polite
- Elitist
- Snobby
- Intelligent
- Studious

#### Background

Born into the the wealthy Peels family, Eugene inherited the Peels Corportation empire after his parents mysteriously died in an accident. Quiet and studious, his education that the best schools in Prosperity prepared him well for the task of owning the entertainment monopoly his parents left behind. He is also known for his extension philanthropy which prominent journalists in the city have accused of being a front for bribery and money laundering schemes. Like his parents and all the other monopolists in Prosperity, Eugene's only goal is to become the richest man in the world and he will stop at nothing to achieve that.

#### Role

As the owner of the new arena, Mr. Peels will guide the player through the main menu the first time they log in. He also will tell the player about any announcements about the game or upcoming events. He is also the default playable large character if the player has no custom characters of that size.

### De'Dra Orgur

#### Race

Troll

#### Gender

Female

#### Age

65

#### Physical Appearance

##### Height

6ft, 5in.

##### Weight

505lbs

##### Characteristics

- Her skin is dark-purple will several moles and age-spots.
- She got her tusks pierced when she was younger but now keeps it classy within minimal tusk-rings or other jewelry.
- She always seems to be glaring at others.
- She also always seems to be expressionless; it is unclear whether she is apathetic or bottling in rage.

#### Personality

- Grouchy
- Focused
- Motherly
- Merciless

#### Background

De'Dra is a troll born and raised in Prosperity. She started off as a waitress at one of the city's upscale jazz bars. She caught the attention of Mr. Peels who hired her as his personal secretary after scaring some drunkards into paying a bill they were refusing to pay. She does not tolerate incompetence or mistakes which is why Mr. Peels put her in charge of the tournament's logistics.

#### Role

De'Dra will be the player's guide through the settings and their account information. She will inform the player of how the account system works as well as give recommendations for the settings players should use.

### Lola Moonborn

#### Race

Elf

#### Gender

Female

#### Age

31

#### Physical Appearance

##### Height

5ft, 5in.

##### Weight

120lbs

##### Characteristics

- Unlike most other elves, she has a slight tan from working outside all day.
- She is very physically fit; her six-pack and muscles make her intimidating to criminals on the street.
- Her police uniform is ripped and tattered but she refuses to get a new one.
- The rumor among criminals is that her bright green eyes glow in the dark but that is just a myth.

#### Personality

- Kind
- Hard-working
- Stubborn
- Tenacious

#### Background

Lola Moonborn embodied the Prosperity Dream; born into deep poverty, she taught herself magic and became a police officer. While on the job, she was notorious among crooks and thieves as one of the only cops in the city that both would not take bribes and destroy them if they tried to offer. She is considered to be a hero among the working class of the city but her investigative tendencies have made her the enemy of powerful people. Suspecting Mr. Peels is up to something, she decided to enter the tournament and investigate.

#### Role

Lola will help the player through the tutorial of the game as well as in training mode. She is also the default playable medium character if the player has no custom characters of that size.

### Rufus Wigglebottom

#### Race

Corgo

#### Gender

Male

#### Physical Appearance

##### Height

3ft, 3in.

##### Weight

70lbs

##### Characteristics

- He has bright orange fur with white dimples and big cheeks.
- His eyes are a soulless brown that is contrasted by his bright smile.
- He equipped his police uniform with Monk gliders so he can fight crime from the skies.

#### Personality

- Kind
- Sassy
- Determined
- Vicious
- Relentless

#### Background

One of the most adorable member of the police force, Rufus has been a deputy since after learning the ways of the Monk. He grew up homeless and alone most of his life until Lola saved him from a group of muggers trying to shake him down for all he had. Her courage inspired him to learn how to fight and after learning how he came back to the streets where he was mugged and began a vicious campaign of vigilante justice against the criminals. Impressed with his willingness to shameless beat criminals, Lola brought him on as a partner and the two have been best friends ever since.

#### Role

Rufus will guide the player through creating their own combatants. He motivates them to make their character however they want and to do great in the arena. He is also the default playable small character if the player has no custom characters of that size.

## Visual References

### Characters

![characters-civilian]

![characters-villains]

![characters-dragon]

![characters-gnome]

![characters-goblin]

### Setting

![setting-cityscape]

![setting-populated]

![setting-school]

# Works Cited

Iwanaga, Hendry. “ArtStation - Hearthstone Challenge ‘Zapping Bird’, Hendry Iwanaga.” ArtStation - Hearthstone Challenge "Zapping Bird", Hendry Iwanaga, ArtStation, 2015, <https://www.artstation.com/artwork/nYGwO>.

Lee, Daniel. “Hax's Retirement, and the Uncertain World of Esports Injuries.” ESPN, ESPN Internet Ventures, 29 Apr. 2016, <https://www.espn.com/esports/story/\_/id/15428951/>.

“A Digital Painting of the Gadgetzan Skyline Used as Promotional Material for the Mean Streets of Gadgetzan Hearthstone Expansion.” Mean Streets of Gadgetzan - Hearthstone, Blizzard Entertainment, Inc, Nov. 2016, <https://playhearthstone.com/en-us/expansions-adventures/mean-streets-of-gadgetzan/>.

“A Digital Painting of Gadgetzan for the Promotion of the Mean Streets of Gadgetzan Hearthstone Expansion.” Mean Streets of Gadgetzan - Hearthstone, Blizzard Entertainment, Inc, Nov. 2016, <https://playhearthstone.com/en-us/expansions-adventures/mean-streets-of-gadgetzan/>.

Ribeiro, Murillo. “ArtStation - Cesar, The Mentor, Murillo Ribeiro.” ArtStation - Cesar, The Mentor, Murillo Ribeiro, ArtStation, July 2019, <https://www.artstation.com/artwork/xzwLz4>.

“Hearthstone's Rise of Shadows Expansion Promotional Banner Featuring The League of EVIL.” Rise of Shadows - Hearthstone, Blizzard Entertainment, Inc, Mar. 2019, <https://playhearthstone.com/en-us/expansions-adventures/rise-of-shadows/>.

Setiawan, Lie. “ArtStation - Mad Goblin Technician, Lie Setiawan.” ArtStation - Mad Goblin Technician, Lie Setiawan, ArtStation, 2015, <https://www.artstation.com/artwork/aYyrX>.

Stovbunskyi, Vadym. “ArtStation - University of Wizardry and Applied Magics - .” ArtStation - University of Wizardry and Applied Magics - , ArtStation, Sept. 2019, <https://www.artstation.com/artwork/xzykNX>.

Čeliković, Milica. “ArtStation - Book Wyrm, Milica Čeliković.” ArtStation - Book Wyrm, Milica Čeliković, ArtStation, Dec. 2019, <https://www.artstation.com/artwork/5890rP>.

<!-- #region Links -->

[patreon-link]: https://patreon.com
[bandcamp-link]: https://bandcamp.com
[godot-link]: https://godotengine.org
[espn-hax-injury]: https://www.espn.com/esports/story/_/id/15428951/hax-retirement-why-injuries-smash-bros-melee-esports-problem-needs-solved
[brawlhalla-gameplay]: images/brawlhalla-gameplay.gif
[melee-gameplay]: images/melee-gameplay.gif
[ultimate-gameplay]: images/ultimate-gameplay.gif
[rivals-gameplay]: images/rivals-gameplay.gif
[setting-cityscape]: images/setting-cityscape.jpg
[setting-populated]: images/setting-populated.jpg
[setting-school]: images/setting-school.jpg
[characters-civilian]: images/characters-civilian.jpg
[characters-villains]: images/characters-villains.jpg
[characters-dragon]: images/characters-dragon.jpg
[characters-gnome]: images/characters-gnome.jpg
[characters-goblin]: images/characters-goblin.jpg
[flow-match]: images/MatchFlow.png
[flow-states]: images/MenuFlow.png

<!-- #endregion  Links -->
