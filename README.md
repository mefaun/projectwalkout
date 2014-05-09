---------------------------------------------------
[ Hip-Hop Life Design Document for Project WALKOUT]
---------------------------------------------------

    The material contained in this document does not constitute an offer for sale. Information expressed are subject to change at any time. The material is based upon information which is considered reliable, but no representation is made that it is accurate or complete, and should not be relied upon.

Revision 1

Date Created 4 May 2014

Last Modified 9 May 2014


(C) 2014 Michael W Hsu mefaun@gmail.com

I feel a lot of things are still rather vague at this moment. We will have to discuss this document over and set a more definite, clearer goal.


= OVERVIEW =
============

Hip-Hop Life is a web browser-based multi-player dancer simulation game (RPG). This design document states the goals and purposes of codename WALKOUT (version 0.1).

Every developer should always work from the latest version of the design document.

= THE USER EXPERIENCE =
=======================

The fundamental architecture of the game engine is based on gaming ideas from Browser-based games.

I am simply fascinated by the extent of details and rich role-playing atmosphere.

As a player of Hip-Hop Life, he or she will experience a turn-based multiplayer game with extracts of the essentials from various cRPGs, combined with interesting ideas from other types of browser-based games.

Hip-Hop Life is written in PHP, a powerful dynamic server-side scripting language. A multiplayer environment is created by manipulation of the MySQL database.

Every time a client accesses a page, PHP will access the database and dynamically generate the necessary HTML content.

Real-time interactions are limited by a tick-based system, in a form of stamina. A quick response along with some strategy is required.

Although timing can be affected by the variable connection speeds, a forced delay is imposed on the player as a consequence of each action to balance the difference.

The basic interface to the role-playing environment consists of pages, and a map of their current location.

The map will include structures (such as shops, houses, stages, etc.) for the user to visit.

Interactions between players (visualisation, talk, trade or battle) are also usually limited to their own particular pages.

Role-playing is encouraged in the game by relying on individual players' co-operation and respect. This can also be enforced by game rules and penalties.

A player starts off as a new jack with no moves. The player will have to battle its way through the tutorial, the player has to gain enough experience to start competing with other dancers.

The path to this release determines what style he or she will be.

From that point onwards, the player takes hold of their hip-hop career. He or she can be a solo player,

or team up with other players to form a crew (once they get to a certain level) so they could potentially win bigger loot from competitions.

Each player can equip with his or her own moves learned and develop their own personal style.

Extra styles or moves could be learned from buying a DVD at the shop. Some may build a dance studio and make profit that way rather than competitions.

A Ranking page will be accessed by the player to let the player know their current standings. They can select options, filtering ranking such as: Top 10 Dancers, Top 50 Dancers, Top 10 Crews, and so on.


= THE PLATFORM =
===============

Server: Web server with PHP and MySQL
Client: Web browser with JavaScript / CSS / PNG support


= THE USERS =
=============

General audience, users with interest in the RPG genre. Users with interest of Hip-Hop.


= TIME MANAGEMENT =
===================

A basic average player is expected to spend approximately half an hour a day (limited by turns, such as the use of stamnia points, or research points) as "maintenance" to his or her character.

Experience users take part in more roles may spend an excess of one to two hours per day.

WALKOUT is a persistent world. However to maintain a balance between old and new players, an "aging" factor will be imposed on players.

The aging process includes faster skills atrophy, greater chance of creative boxk, and eventually involving quittage.

*As there is always a possibility to expand the game by adding other elements of hiphop into the game and implementing  other new things, I estimate the lifespan of the final product can last for more than just a few years.*



= CONCEPTS =
============

Design concepts and ideas are to be listed here.

SUBJECT: storyline
STATUS: draft
DESCRIPTION:
The world is heavily cultured in hip-hop and involves the large hip-hop competitions. Dancers gather and compete with each other in this world with the same goal - to be the best.


--


SUBJECT: Dancer Body Type
STATUS: Completed

Body Type:

Players select from height and weight.

A skinny body are able to do more clean moves but lacks in strength to do pops.

A heavy body is more fluid and but capable of having bigger pops.

Athletic body is pretty good at doing cleans moves, hard to achieve. recovers stamnia.



--

SUBJECT: Dancer Style

STATUS: important

DESCRIPTION:
The style is not entirely by choice but by the path the character follows. The style is determined by the players's path in the tutorial. Types of dancers known to the WALKOUT world are:

(Form: A more descriptive input is required from you especially when I am not good at the language. The description should first concentrate on descriptive / qualitative approach first, then game attribute / quantitative. Which is obviously not what I am doing here.)

< Allstyles >

Introduction: Allstyles are of a well-balanced style to which all others compare to, with no particular strengths or weaknesses.

Appearance: Passionate, confident features.

Feature: Well balanced attributes.

< Storyteller>

Introduction: You recover stamnia much quicker which lets you freely tell your story more in rounds. Your hits however appear less common.


< Creative >

Introduction: Creative dancers tend to study more than whats at their local dance community. They show advanced intelligence amongst other  dancers.

Appearance: Standout-ish, lacks confidence.

Feature: Chance of more style points during training are better.

< Genius >

Introduction: They seem to be clean and don't crash. They have high musicality.

Appearance: Hipster. Always has earbuds on.

Feature: High musicality.

< Powerhead >

Introduction: Powerheads are small & robust with remarkable amount of strength and vitality, thus able to do more difficult moves.

Appearance: Short and robust.

Feature: Greater strength. Can do more difficult moves. Chances of crashing are fewer.

< Crowdpleaser >

Introduction: Crowdpleasers have tons of fans. They tend to get the upperhand at battles.

Appearance: Stands-out. A Show-off. (need reorganising)

Feature: Greater chance of absorbing more fans. More Hit Points Judge favors Crowdpleasers if execution is done right.

< Street Performer >

Introduction: Street performers are always on the streets performing for either a quick buck or building a fan base.

Features: Get bonuses training or competing at the park or street.

* to be implemented at a later release
--

SUBJECT: skills and professions

STATUS: draft

DESCRIPTION:

Professions are again not selected specifically by the player but determined by what skills the character has developed. A reasonable amount of social involvement is required to establish a profession. This can ensure enough player-to-player interactions and provide players opportunities to meet new players to keep the game interesting.

BBoys

< Trickster >

< Stylehead >

< Powerhead >


Poppers

= STYLES THAT CAN BE LEARNED =
==============================

< Stepper - Base >

INTRODUCTION: Nice footwork.

MOVES: Walk Out, Shuffle, Crossover

REQUIRES FOR: Strut, Float, Crazy legs

< Boogaloo - Base >

INTRODUCTION: High in Stamnia.

MOVES: Fresno, Oldman

REQUIRES FOR:

BONUSES: Stamina

ATTRIBUTES:

< Wave - Base >

INTRODUCTION: Very fluid.

Moves: Arm Wave, Body Wave, Fixed Waves

Requires for:

Bonuses:

< Tut - Base >

Introduction: Exploit the body's ability to make geometric positions and movements.

Moves: Boxes,

Bonuses: Execution not difficult, lacks fan support.

< Floats >

INTRODUCTION:

MOVES: Backslide, Side Glide , Airwalk (at lvl 3), Circle Glide (at lvl 5)

< Ground Mover >

You put more emphasis on ground moves

MOVES: Knee Glide, UFO, Backdrop

PRE-REQUISITE: Stepper lvl 5.

< Bopper >

With the flex and isolation of the chest muscle, your mind and body feels like in total control.
Robot moves attract more fans.

Moves: Chest Bop, Knee Bop, Remote Control

PRE-REQUISITE: Robot lvl 5., Boogaloo Lvl. 5


< Animation >

Done by pantomimes of the past, Animation  is the umbrella term that is wise in style, but difficult to learn.

Moves: Scarecrow, Puppet, Strobing

< Trick >

Lots of blowups.

< Robot >

A style imitating a robot or mannequin.

MOVES: Dime stop

< Boogaloo >

With an unknown origin yet done by many, Boogaloo is a groove style that is high in stamina.

= EXTRA STYLES =
================

< Bopping >

With the flex and isolation of the chest muscle, your mind and body feels like in total control.

MOVES: Chest Bop, Knee Bop

BONUSES: Robot moves attract more fans.

< Strut >

Created in the Bay Area, strutting does lots of damage and is seen a strength style.

Moves: Clinkin'

BONUSES: With Robot, crew routines

< Threader >

You are now connecting your movements more abruptly with rails.

Wave and Tut moves can impress more fans.

Requires: Tut or wave.

--

SUBJECT: Perks
STATUS: draft
Perks are can be obtained from random by Training or buying them from a shop.

< Toy Man >

Based on action figures, Straight arms and right angles are lethal in battle.

Strutting moves have higher critical hit damage.

Requires: Animation lvl 7, Strut lvl 5.

< Ticking >

You pop at smaller intervals. This is twice as fast as normal.


You are able to do more hits in battle., with the cost of stamnia.

Requires:

< Animatronic >

You have begun adding a hit or bounce to the end of each movement.
Robot and Boogaloo base moves do 15% more damage.

Requires: Animation lvl 3, Robot lvl 5

< Liquid Pop >

Originated in the electronic community, your wave and overall style now has more fluidity to them, now that you have rails.

Waves do more damage with the cost of less hits.

Requires: Wave lvl 5, Animation lvl 2.


< Contortionist >

You seem to understand the anatomy more than the average dancer. You have less hits but you have a fluid motion.

Pre-requisite: Wave lvl. 7, Animation lvl. 10

< Crazy Legs >

Your legs seem to move fast, your knees begin to roll and your feet begin to twist.

Requires: Boogaloo lvl 5., Steppin lvl 5.




= SUBJECT: self and player-driven NPCs =
========================================

STATUS: IMPORTANT

Non-Player Characters (NPCs), including encounters, are basically driven by the players themselves. Every time a page is loaded, a simple script will have to determine the character's next movement.

Some NPCs should also be controllable by players. Making a NPC controllable, by one of our staff or voluntary members, will create random surprises to players.

= SUBJECT: Character Screen =
=============================

STATUS: Draft

On this page the player views information about the dancer.
Character Attributes (and its system) are described better in detail on the game design document.
Displays Dancer Type, Perks, Style, Attributes, Current Research Points, # of Fans, Friends, Crew Name, Affiliated Crews, Battle Ranking

--

SUBJECT: Training

STATUS: draft

Players will train at their home using research points and stamina. If they are given access to other locations such as studios, they can train there as well for bonuses. They will use stamina to strengthen moves they have learned already. Research points are used to obtain new moves but require time.

Strength drill can increase more
hits.

Footwork Drill can increase the damage of leg moves.

Musicality Drill will increase fans.

Isolation drill makes moves clean.

--

SUBJECT: Shops

INTRODUCTION: Shops will let dancers obtain items and shoes that they need to compete with other players.

STATUS: draft

--

SUBJECT: Battles

STATUS: draft

Players can battle other players by whoever is online. Players can also enter competitions (nPCs or Live Events) to win fanfare and win top prizes.

--

SUBJECT: Crews

STATUS: draft

Dancers are able to form crews. Crews can enter competitions to win fanfare and win top prizes.

--

= MOVE GUIDE =
============

STATUS: draft, needs completion

This guide will explain in detail every move in the game.

*SAFE MOVES*
********************

Safe moves are deemed safe when executing.

MOVE: Dime stop

STAMINA: 3pts

STRENGTH: 5pts
End a pose with an abrupt halt.


MOVE: Arm Wave

STAMINA: 5pts
A fluid motion with the arms.

MOVE: Side Glide

STAMINA: 7pts
a Footwork move.

MOVE: Foxtrot

MOVE: Float

MOVE: Shuffle

MOVE: Crossover

SIGNATURE MOVES
***************

MOVE:Wiggle Walk

MOVE:Ground-body Wave


--

SUBJECT:


END OF DESIGN DOCUMENT
