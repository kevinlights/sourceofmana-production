# Source of Mana

![](RackMultipart20221023-1-eegcr3_html_ee28ad0396a1cffd.png)

#
## **Open Game Design Document**

_This document is designed for_ _ **Source of Mana** _ _as a result of years of eyewitnessing and various knowledge accumulated from past projects' successes and failures._

_This document is an hybrid Game Design Document and Project Management Document available under the license Creative Commons CC BY-SA 4.0._

Reid

### Summary

[Forkstory](#_mptlvkrwj1dk)

[TMW Umbrella](#_l86d2e4eoj0h)

[The Mana World](#_77gy2iv2vyo3)

[Evol Online](#_59ydhkmzipxj)

[The Mana World; rEvolt](#_k14ymehje8qr)

[The Mana World 2 : Mouboutaur Legends](#_m11zhqzeu3k9)

[The Mana World; evolved](#_h6084fo20h9e)

[Source of Mana](#_4k3hcb85uv0q)

[Game Pillars](#_5y1pix1juci5)

[Game Story](#_pf26z9y849t3)

[Game economy](#_c6vna1ao6w6q)

[Playable races](#_e9p5l01iopld)

[Other races](#_nq9fcrscr8vr)

[Class](#_9msl7tnikmbo)

[Combat features](#_obnudmady7bl)

[Content databases](#_o1zolqp8bn3y)

[Monsters](#_usdc12zick2t)

[Items](#_n88lymauygtk)

[GUI](#_gb3u5o8k9bqq)

[Actions](#_advzgzwydpzb)

[Production](#_msawbaz9tmlc)

[Options](#_el3czt11f0sg)

[License](#_dxial6kj4cej)

### Forkstory

The Mana World (TMW) was created in 2004 aiming to deliver a retro RPG gameplay experience enjoyable online by anyone and those in as many and diverse ways as possible.

The project rapidly adopted the Free and Open Source Software (FOSS) culture and surfed into the wave of many other open-source projects through GNU/Linux Distributions and Open Source communities.

Throughout its history, the project knew multiple forks and sister-projects, multiple development teams, contributors and players that could be splitted into different eras.

## eAthena

Working on a Massive and Multiplayer Online Role-Playing Game (MMORPG) is a huge task that could not be done from scratch. Thus, TMW used as its core technology the game engine named eAthena (european Athena). This game engine was forked some years ago with the dust of the jAthena (japanese Athena) source code that was available under the GNU GPL v2+ license.

jAthena and eAthena were designed to emulate a Ragnarok Online server to permit the creation of private servers.

## tmwAthena

The architecture of the eAthena server was too big for the needs of TMW which vaguely needed most of the available features. A new fork was then created under the name of tmwAthena to purge most of the unneeded features and to focus on what mattered to produce a first playable preview.

This first playable preview was extended into what we now know as the main server of this project running since.

## TMW Client

eAthena used to be a server emulation that connects directly to Ragnarok's non-free game client, the compromise to use a mostly ready server was to create a client from scratch and to follow Ragnarok's server and database structures.

TMW client evolved through the age to finally reach its maturity with the SDL 1.2 graphical library which will later allow it to run on Windows, Mac, BSD and most GNU/Linux distributions.

## ManaSource

Through the years, The Mana World evolved into a structured but complex game project that turned out to be difficult to maintain and improve.

Design and story wise, the game project lacked coordination across contributors which is fairly normal for a non-profit project. New contributions came from players and could sometimes lack consistency to previous game content.

Code wise, the use of an axed-cut eAthena fork turned out to be a nightmare to maintain as any new feature would necessitate to "hardcode" and hack into the existing code base.

All of these issues created a schism in the project and saw the creation of the "Content Release 1" (CR1) game revamp and the creation of "ManaSource" server and the rebranding of the client which would replace respectively tmwAthena server and the current TMW client.

As most of the contributors put all of their free time into creating a whole new server software, the time started to seem long to the current player base that lacked communication with the CR1 crew and saw the lack of content release.
 In the end, a large proportion of the player community felt abandoned and started to keep the current game alive by their own means. This resulted in a split between CR1 and the current game.

This decision hurted the development of all of these newly created projects (CR1, Mana client and the ManaSource server) as most of their new contributors used to come from the game community. With the faucet of new contributors closed, all of these new projects started to slowly die from lack of new help.

## ManaPlus

[wip]

##


## tmwA

[wip]

## Game forks

[wip] TAW, LoF, TMW-UFB, TMW.net

## evolserv

[wip] evol

##


## Hercules

[wip] tmw2, revolt

### TMW Umbrella

## The Mana World

As it aged, TMW development went through different phases and eras but the project main goal stayed to create an innovative, free, and open source MMORPG.
 As Wushin described perfectly, TMW's primary directives are :

- Maintain continuity
- Improve content
- Reinforce perpetuity
- Encourage community

Make TMW easier to change and the easier it is for individuals to make changes as it could have as many goals as it has of users.

#### TMW is for people to develop themselves

TMW is mature now, in many ways. TMW has the learned experience of 15+ years of operations. TMW has a wide set of skills individuals can learn from contributing to Being a Game Master to Being a Guild Leader to Translation Work to Programming and much more.

#### TMW is dead, long live TMW!

As a project/game matures, old people leave and new people join. A MMO has a life cycle and a software cycle. A MMO has social and programmatic problems. Everyone is here on a voluntary basis, free to come and go as they please. This is all a natural part of personal and project growth.

#### TMW is IRC with hats

One of the best compliments of this game. Users only sit in IRC because they enjoy the discussion and/or the people. IRC and TMW are both places people can come back to and feel somewhat the same continuity among the content and community. As much as everything changes, everything stays pretty much the same.

#### TMW is the community we make it.

TMW has become an entity dependent on the community of TMW users. A community TMW wants to help develop.

## Evol Online

EvoL is born from the imagination of two french students in 2005. Their aim was to create a homely MMORPG where the community and the game would evolve together.

In 2010, a group of contributors from TMW decided to revive this utopian idea by releasing a new version of Evol Online which would feature a server, client and game development forked from various projects:

- Game content and guidelines forked TMW's.
- The evolserv game server is a fork from Hercules; a most up-to-date eAthena server.
- The ManaPlus game client is a fork based on the Mana client.

#### The adventure begins

After some months of research and plannifcation, the project's aims were set and the development started and would focus on these main points:

- Multilingual support for the game client and the game itself.
- A respect of the FOSS world, as did before them their fork'cestors.
- A place to develop a game based on a well established design, guidelines and story.

The focus on quality over quantity slowed down the development and resulted in a low amount of available content and gameplay.

## The Mana World; rEvolt

Cutting the workforce into two different projects didn't work through the age and the inevitable loss of speed that independent 2D MMORPG projects could have.

Inevitably, discussion to merge both TMW and Evol teams were started and negotiation started to formalize what could look like this future world.

Some mistakes that were done previously with the mana' s CR1 were done again and the lack of free time and communication hurted badly the community badly. Once again, the community mutated and started a new fork that would force rEvolt to slowly die due to the lack of new contributors.

[wip]

pros: milestones and production improvement

cons: sudden lack of contributors and leads

##


## The Mana World 2 : Mouboutaur Legends

[wip]

##


## The Mana World; evolved

[wip]

###


### Source of Mana

Source of Mana is a project that aims to reboot The Mana World almost 20 years later with new technologies, a lightweight process and a clear game design and lore.

Following The Mana World's footprints, Source of Mana is a MMORPG 2D set into the fantasy world of Aemil.

![](RackMultipart20221023-1-eegcr3_html_897bd7f2cebee0b8.png)

We are using Godot as our game engine and our main editor, the goal is to focus on the game development and to benefit from Godot's experience, community support and features.

Some external tools like Tiled, Gimp, Krita and Inkscape will still be needed and required to produce our game assets as we will port a large amount of content from past TMW and Evol Online projects.

Our target audience is from the community of players that used to play The Mana World these last years and like-minded players that are sharing our values. Players from any age, countries and personal beliefs are welcome.
 Although this is not official, our target PEGI would be PEGI 3 (https://pegi.info/what-do-the-labels-mean).

Source of Mana's main point of interest is to provide a community built game where the community is placed at a central key of its development and unlike any other game advertising the same as it truly is the community that is building the game!
 We want players used to old RPG games to feel nostalgia and new players not accustomed to this kind of game to discover and enjoy our world as we did many years ago.

Through the years we developed our own style of development for many part of the game:

- Our visual style is mostly pixel art with a soft outline but we do not limit ourselves to a precise palette to ease up the development of new assets from the community.
- Our audio style features simple instrumental audio samples.
- Our coding style aims to keep things simple, secure and easy to modify.

##


## Game Pillars

Our design revolves around multiple keywords that we call "pillars".

_The primary reason to reduce our game design to such a limited list of words is to help us focus on what is important and what should be rethought._

_We ought to keep in mind these pillars for any future design or narrative choice, if an idea doesn't fit any of these points, then it may say that it is not an important addition or not suited to the game._

#### Community

To connect anybody associated with the game project within the same space. From players to contributors, anybody should have a way to meet, communicate and interact with each other.

#### Freedom

To access any part of the game content, story and features within its sole character by the only restriction of finishing the game tutorial.

#### Narrative

To be driven into an immersive world where both the lore and the story are main elements of the game's narration.

#### Old School

To dive into a fantastic world that has old school feelings but not an old fashioned integration, this applies to all sides of the game and its development.

##


## Game Story

#### Community integration

A large number of players went through the desert of Tulimshar and the hill of Hurnscald over these last 18 years. The Mana World's original story is their story and we ought to use such tales and stories to build our game lore and main plot.

From guilds like the Holy Mana Clan to the Crew of Red Corsair passing by various dramas, friend groups, famous project dictators and even some forgotten tales.
 Our story is rich and we should benefit from this fact and use all of these as inspiration for our game lore, main quest and side quests.

#### Source, Mana & the Tree

#####


The Mana World has always used this term to refer to magical abilities but never dug much deeper into the concept.

In the name "Source of Mana" we already tell much of our story, as simple as it may seem.

**Mana** is that special element that allows us to delve into magical themes and gives life to our fantasy world. It's a concept that has been used a lot in many games, books or films. Mana is always used as some sort of device to give the magical power of any given world a name. In games, it's traditionally used as the name of a mage's primary resource and can be found as a blue status bar or potion. The blue colour itself also seems to be a recurring theme that has been picked up as part of the idea of Mana in fantasy games. However, a lot of the games fail to really explore the idea of Mana beyond its use as a blue resource bar.

The Mana World was given a very simple name entirely based on that one word: Mana. Many years later, however, Mana was once again forgotten, unexplained and taken for granted. We believe that Source of Mana as a project is about going back to the **source** and telling old stories in new and better ways, so we intend to make Mana one of the central themes of the game, to give it a story and a purpose. Mana will inspire all the magical elements of the game's storytelling. To understand and discover more about Mana will be one of the objectives of the player character. As such, Mana will be a life force that powers everything and everyone, including all traditional RPG game classes (not only mages) which will learn to manipulate Mana to use special abilities. All living things will be powered by this mysterious life force.

The theme of Mana also meets the theme of trees in our story. Evol Online had always used a tree as its emblem: a symbol of life, _evol_ution and growth. The Mana World meanwhile had this well-known quest involving a mysterious "[Mana](https://wiki.themanaworld.org/index.php/Legacy:Mana_Seed)[Seed](https://wiki.themanaworld.org/index.php/Legacy:Mana_Seed)", which suffered the same fate as all Mana-themed things: it was never explained further. Source of Mana will tell the story of the Mana **Tree** , a world-tree with roots that reach every corner of the planet and act as conductors for Mana to flow through. The Tree is in fact the source of all Mana, which is in turn the source of all life.

## Game economy

The Mana World introduced at their expense a flawed game economy due to the global increase of game content that targeted only some range of players of very low and very high level.

The constant need of new content from the community messed up with past contents that were previously introduced, thus some parts of the game became unused and some equipment items were never used.

Seasonal events introduced some items obtainable for a short amount of time that became rare and unavailable over the years, these pieces of equipment were for the most part only cosmetic hats or unusable items that saw their value rise every year until it was eventually re-introduced in-game.

This rare hat system was the fondement of the economy and one of the main attractions of the game.

To prevent items to lose their value and to be unused, we will have to segment the number of gear per level range.

A complete gear should be available every 10 levels for a specific class of gameplay, equipment gears should feature a minimum level to equip to prevent mules from being created too fast with some high-end gears.

## Geography

![](RackMultipart20221023-1-eegcr3_html_ae5dbd2778147b07.png)

##


## Playable races

#### Humans ![](RackMultipart20221023-1-eegcr3_html_33c160155abdb380.jpg)

Humans evolved from primordial Tritans thanks to the mutating effects of Mana in the early centuries of Gasaron's creation. Their ancestral home is the region of Argaes on the continent of Ancea.

Humans live in all sorts of climates all over Gasaron, constructing villages and cities and trading with each other. Strong bodies and sharp minds make humans the most versatile of races, able to thrive in almost any environment and to specialize in most disciplines. Humans invented strong ships to travel on water and to spread their civilization to most parts of the world. Both main continents are dotted with Human cities, where they congregate and live together. Urban areas are a specific characteristic of the Human race. They protect humans from the unpredictable wilderness of the outside world and foster trade and cooperation among individuals. Other races have slowly become accustomed to Human cities and often use these as meeting points and sometimes even dwell in them.

#### ![](RackMultipart20221023-1-eegcr3_html_e5d5bd000de7d841.jpg)


#### Ukar

Ukar evolved from primordial Tritans thanks to the mutating effects of Mana in the early centuries of Gasaron's creation. Their ancestral home is the Tempus Mountains south of the region of Kaizei.

The Ukar (both singular and plural) are an extremely independent-minded race. They favor underground environments and build their dwellings inside large mountains. An Ukar's eyesight is poor and particularly suited for the dark. However, this race possesses extremely advanced senses of smell and hearing. Ukar can detect noises at a wider range of frequencies than any other race and can use their smell to track pretty much everything. These abilities make this race particularly skilled at stealth.

Ukar are the only other race apart from Humans who congregate in cities. However, Ukar cities are merely densely populated communal areas rather than commercial hubs. Ukar have no trading or military culture, focusing their interests towards artistry. Ukar music is famed for filling mountain tunnels and valleys with enchanting and beautiful sounds, their sculptures seem to emerge from the very rock they are carved from as naturally as a tree grows from the ground, and their writings tell great stories of fantasy and accounts of real events that concern all races in Gasaron.

In an old language Ukar were also known as Talpans, a name still sometimes used by Humans to refer to them.

#### ![](RackMultipart20221023-1-eegcr3_html_9aa02e8d54e3a9cd.jpg)


#### Tritans

By far the oldest race on Gasaron, the Tritans originate from the deep sea. Some say Humans evolved as a land-dwelling branch of the Tritan species. They live in the Tritan Ocean, which received its name from them, and the Oranye Isles - the only land in Gasaron which is fully inhabited and controlled by them. The Tritans can live on land for unlimited amounts of time, but generally prefer water and will submerge whenever possible. Tritans living on land will often live in coastal huts or Human cities and still possess a main home in the nearby sea.

Tritans are a very simple yet pragmatic race and often find it difficult to be taken seriously and valued by other races. However, their pragmatism is what gives Tritans such a strong resolve and military-oriented mind. Tritan warriors can be ferocious adversaries and thanks to their quick regeneration skills (especially when in water), they can withstand more damage than most others.

#### ![](RackMultipart20221023-1-eegcr3_html_2ce0fce84f3deeae.jpg)


#### Kralogs

The Kralogs are a nomadic species, distantly descended from the Ukar. They originate from the Land of Fire, two large volcanic islands off the coast of Kaizei. Their land is very cold and temperatures are kept tolerable by geothermal activity and the great volcano of Ar'kibh. Kralogs live mostly in camps, always ready to relocate to avoid volcanic activity. They are great metal workers and warriors, owing their skills to what little their land has to offer.

Due to the harsh environment in which they live, the Kralogs have become extremely resourceful and have developed to a unique level of technological advancement. Thanks to the use of the various metals available and the harnessing of the geothermal power of the Isle of Pihre, unique machinery and strange steam-powered contraptions can be seen in all of the Kralogs' moving villages; many of the machines are in fact designed to aid in moving across the Pihrean Tundra.

Kralogs develop extremely different external appearances based on what temperature they have been exposed to the most during childhood. The reasons for this are unknown, but this characteristic is attributed at least to the unusual presence of two temperature extremes on the Land of Fire. Kralogs exposed to very cold temperatures in areas away from volcanoes develop a grayish skin tone with two small horns on the head. Kralogs exposed to very hot temperatures in underground complexes where lava flows freely develop a red skin tone with various horns protruding from the scalp (forming a crown-like feature) and from the brow.

#### ![](RackMultipart20221023-1-eegcr3_html_9d056290a4a2f630.jpg)


#### Raijin

The Raijin (both plural and singular) were created by accident following the events of The Mana War. The conflict between the Wizard Order and the non-human races of Gasaron accidentally triggered a Mana storm. Unable to contain the energy of the storm, the sorcerers fell victim to its raw power and were mutated into hybrid beings that were mostly organic, but infused with raw mana energy. Over a few days, the energy itself dissipated, fueling the leylines of Gasaron and strengthening the effects of magic in the world. What remained of the sorcerers was the Raijin; a strange looking race with great affinity for Mana and all the types of magic that it fuels.

As the First Raijin recovered and went on with their lives, they discovered that they could no longer mate with Humans. However, when mating among themselves they produced new Raijin. This race has two typical morphological patterns: Light Raijin and Dark Raijin. Which pattern they take on depends on what magic they are exposed to the most during infancy. It is possible for them to mutate forms; however this is an extremely painful and difficult to achieve transition as it requires intensive exposure to the Raijin's opposite side of magic.

A widespread myth is that Raijin reproduce through laying eggs. This is untrue. The myth is fairly common among Humans and is often referred to with the intention of poking fun at the Raijin race.

##


## Other races

There are some other races, but they are so exceptionally rare that some even might question whether these races actually exist.

####


#### Hantu

The Hantu were supposedly the first beings to come into existence. Most of the stories about them were told by the Mana Tree and passed on through thousands of generations of Tritans, eventually mixing history with myth. Not much is truly known about the Hantu today.

####


#### Irminsul

On rare occasions, the Mana Tree is able to produce seeds in its fruits. These Mana Seeds are capable of producing an Irminsul. These tree-like, immobile beings are fully sentient. They take a much smaller form of the Mana Tree and are able to grow in dark caves, cold tundras or even arid deserts and their luscious blue-green leaves seem unaffected by these environments. They wield considerable power, but are in no way invincible. Irminsul can be killed and will die if their underground connection to the Mana Tree is severed. Irminsul typically do not talk to most people unless they are addressed first. They are said to be of good disposition and would only cause harm to defend themselves or the natural environment around them.

## Class

The player will be able to switch between multiple kinds of classes during his playthrough without having to create a new character.

These kinds are all derived from three main kind of battle mode:

- Short range combat
- Long range combat
- Spell combat

Each classes will focus to one of these battle mode and receive a bonus in some stats:

- Healer, focus on light magic and provide assistance during a combat
- Warmage, focus on dark magic and cast spells to kill
- Support, spawn and manipulate wildlife and monsters
- Tank, can resist a large amount of damage
- Fighter, deals a large amount of damage
- Thief, uses tools to win a fight
- Archer, uses a bow to shoot from long distance

Some quests aim to improve your class gauge, once you've hit the maximum experience you will be able to obtain a bonus of up to 125% by doing daily quests and practices related to your current class.

Switching from one mode to another will reset this bonus experience, your global experience will remain up to 100% and you will need to do new daily quests and practice to regain your bonus.

## Combat features

Our combat features multiple kinds of attack systems for a playable character. It comes from single attack being rapidly casted to some heavy attack that takes more time to process but does bigger damages.

Additionally to these two kinds of attacks, you can use some spells to complete your war arsenal.

A mix of these slow attacks, fast attacks and spells can lead into some "combo attacks", if you alternate between multiple kinds of attack you can improve your damage per seconds and use less stamina.

A gauge will keep track of your combo score and unlock and launch automatically an ultimate attack that does 150% damage if you reach its maximum.

## Content databases

Our content databases are splitted across multiple JSON files that store all information necessary for the client and the server as the same file will be used on both projects.

## Monsters

A large amount of monsters are available from The Mana World but only a few of them are actually humanoid (skeleton, soldiers, thiefs, etc…) enemies.

Humanoid enemies will fill some empty areas, caves and will help to reduce the need of new monster sprites.

Placement of these monsters and enemies has to be coherent, wildlife should be unique to some areas of the world only while the same group of thieves can't be used across different maps without a reason.

A dungeon has to follow some consistency, as an example Phatyna's cave is filled with 2 kinds of slime monsters, 3 semi-bosses and a Phatyna as the final boss. There is no need to add maggots, skeletons or anything else.

## Items

Each item will have the ability to be used, equipped or remain unused. These items will be dispatched across multiple categories:

- Equipment, head gear, chest gear, hand gear, foot gear, pant gear, arm gear, jewelry 1, jewelry 2, shield and weapon
- Usable item, potions and books
- Unusable item, loot and craft items

##


## GUI

Our Graphical User Interface should display easily all information available to the player without obstructing the game view on all of our platforms.

Our main GUI articulate over a shared group of elements across all platforms:

- Floating windows
- Stat indicator
- Shortcuts

Additionally to these elements there are some mobile specificities available for phone and tablet support:

- Control Overlay

#### Floating Windows

Each floating window can be enabled by mouse with a top-right button or by keyboard with Fn keys.

These windows regroup:

- Inventory, display the player inventory and a visual to show equipped clothes and gears
- Chat, a multi-tab window to show discussions across different channels
- Options, a list of parameters to modify at the player's ease
- Minimap, a visual of the current map
- Social, display all online players, your friends, people in your party and guild members.
- Quest, a list of all available and completed main and side quests
- Glossary, display all items, mobs and person you encountered

Example:

![](RackMultipart20221023-1-eegcr3_html_f1d75aa36989c200.png)

#### Stat Indicator

Display the player level, current experience count and basic health, mana and stamina information at any time with multiple bars and text indicators.

Once clicked, a sub menu opens and displays all your characters (i.e.: stats, race, gender, money count, etc…) and lets you tweak your personal stats if you have some stat points available.

Examples:

![](RackMultipart20221023-1-eegcr3_html_f5f4d5cba5bf60e7.png)

![](RackMultipart20221023-1-eegcr3_html_58f3568000e0cc4a.png)

#### Shortcut

The player will be able to drag & drop any items, skills and spells inside 8 boxes on the bottom of his screen, each of them will be usable by pressing the key corresponding to the box number.

Example:

![](RackMultipart20221023-1-eegcr3_html_f2350a9a44810bcb.png)

#### Control Overlay

To emulate a gamepad overlay over the screen

Example:

![](RackMultipart20221023-1-eegcr3_html_92e2ae382158b30.png)

##


## Actions

Our game UX and gameplay features should be available to all kinds of gamepad and play styles.

Our main constraints are the number of buttons available with a gamepad controller and their reciprocity to a keyboard and mouse mapping.

We reduce our number of actions and we separate them in 3 groups to place them in different parts of a gamepad controller:

- Gameplay actions
- Target selections
- Player interactions

The same key will also be used to do a basic attack and to interact with other players and npcs as it will be the primary key for our gameplay.

|
## Action
 |
## Keyboard
 |
## Gamepad
 |
| --- | --- | --- |
| **Move around** |
## Arrow Keys
 |
## Left Stick
 |
| **Fast Attack** | **Ctrl** | **Cross / A** |
| **Heavy attack** | **X** | **Circle / B** |
| **Use skill / Cast spell** | **[0-9]** | **Triangle / Y -\> Select the skill with DPad Left/Right** |
| **Dash** | **C** | **Square / X** |
| **Pick up item** | **Z** | **Cross / A** |
| **Interact with PC/NPC** | **T** | **Cross / A** |
| **Clear target** | **Shift** | **R3 / RSB** |
| **Sit down / Stand up** | **S** | **L3 / LSB** |
| **Target nearest monster** | **A** | **R1 / RB** |
| **Target nearest PC/NPC** | **D** | **L1 / LB** |
| **Target next monster** | **Q** | **R2 / RT** |
| **Target next PC/NPC** | **W** | **L2 / LT** |
| **Show smiley** | **Alt + [0, …, 9, -, =, Q, …, L]** | **DPad Up -\> Select the smiley with DPad Left/Right** |
| **Focus chat window** | **Enter** | **DPad Down** |
| **Mouse** | **Mouse** | **Right Stick** |

[wip] Add a visual example on a keyboard and gamepad layout

Keyboard:

Gamepad:

## Production

We use a milestone system to manage our current development progress. Here is a preview of our current and future planned milestones.

#### Milestone 1

Status: completed.

Goal: decide if Godot is a viable solution through the implementation of a basic game prototype.

Tasks:

- Create a basic dungeon layout to wander into
- Adapt vnen's Tiled addon support in order to import our Tiled maps directly to Godot and to experiment with various Godot features
- A simple GUI overlay to manage basic game interactions
- Mouse navigation
- Filesystem, databases and config files management
- Entity and map management
- Android, Linux, Windows and MacOS builds

####


#### Milestone 2

Status: completed.

Goal: benefit from Godot 4 new navigation system, network api and Tilemap/Tileset improvements.

Tasks:

- Port the current game prototype to Godot 4 and upgrade our scripts to GDScript2
- Port our map import to Godot 4
- Use the new agent navigation system to move our entities

#### Milestone 3

Status: in progress.

Goal: play online and profit from a basic online experience:

Tasks:

- Implement a basic client-server API

- Improve the FSM to handle player connexion
- Create a server scene
- Split some services script code to work on both the server and client scenes
- Have a NPC and a monster

#### Milestone 4

Status: not started.

Goal: overworld and multiple dungeons locations.

Tasks:

- Implement the overworld system client and server side
- Implement Candor Cave
- List all available content that fits our need and quality standard from Evol Online and The Mana World
- More network support
- Basic combat support

## Options

[wip] accessibility:

Button remapping, colour deficiency, adjustable font size, HUD scaling, contrast

mobile:

shaders

volumes

translation

## License

This project is for the most part licensed under the MIT license with the exception of all of the artistical work that is released under the CC BY-SA 4.0 license.

Things to document:

- Game loop
- Main quest and side quests
- Lore
- Geography
- Overworld and map support
- Game systems, mini-games
- Platform supports and build options
- Options
