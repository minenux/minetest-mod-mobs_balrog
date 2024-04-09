# VenenuX minetest mod mobs_balrog

This mod adds big moster

![Mobs Balrog's screenshot](screenshot.png)  

## Information

This mod added a configurable big BIG moster to defeat, 
taken it from the Lord of The Rings game and reworked it a bit.

was originally made by Hamlet but abandoned, now minimal fixed 
for VenenuX minetest game, https://forum.minetest.net/viewtopic.php?f=11&t=18459

#### DIFERENCES WITH FLUX FORK : more fair and consistent

The flux fork is unfair and inconsistent:

* heavy cos has more textures and sound effects (nice but slow on phones)
* the whip just spend so much on any action
* seems sometimes not care of creative mode
* the monster is great but unfair and 
* players never meet it cos spamn too much deep, and finally 
* dont work in any minetest, neither well in phones/rasberrys/tables.
* it chat with player cheaters so will cause some lag in low end devices

This mob is more simple, unfeatured but faster:

* it hurts any player, event in protected areas
* dont detect invisibility in some cases
* it loads faster and works in any device, event phones or rpis
* the balrog dont chat with players launchind obscure sentences, causing more lag

### Usage

**Spawn chance**: 1 en a thousand (same the chance of being struck 
by a lightning in real life) under -1500 on the ground, but if nether then 
will be 1 in half a more thousand under -8000 on the ground.

**Lowered stats**: HP range to a min of 400 to a max of 600; if you are 
alone then you are dead, if you are in a party you might defeat it. 
Maybe. It's a deity after all.

## Technicall information

The mob is configurable by settings, check [settingtypes.txt](settingtypes.txt) file.

* `mobs_balrog:balrog` : the balrog deity!
* `mobs_balrog:balrog_whip` : the balrog whip weapon

Some commits on flux's fork are unclear by example dccf3edeccbd5c7ee6947f12919fc375690a42ff 
seems work in pvp but also changes the tool registry.

Another doub change is the balrog life, in commit 3918415ed53f85266e95f6886173c6a8197b2092 
that increases to 2400 but are not documneted, so non modders will not understand why dont die!

## Download: 

* https://codeberg.org/minenux/minetest-mod-mobs_balrog

Changelog [changelog.md](changelog.md)

## Dependencies: 

* tnt, default, from basic games, 
* mobs (or so called mobs_redo)
* intllib if you are using minetest 0.4 series and only optional

## License: 

* **Source code's license:** [LGPL v2.1][1]  
    * this code is based in the Hamlet one
* **Media (Textures, Models, Sounds) license:** [CC-BY-SA 3.0 Unported][2]
    * initially the balrog was created by STHGOM / sparky
    * sound media files copyright BrandonReese
    * STHGOM / sparky mobs_balrog_balrog.png
* Copyright (CC0) creative commons zero
    * LorNeo mobs_balrog_balrog_whip.png


[1]: https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html
[2]: https://creativecommons.org/licenses/by-sa/3.0/
[3]: https://github.com/minetest/minetest_game
[4]: https://forum.minetest.net/viewtopic.php?t=9917
