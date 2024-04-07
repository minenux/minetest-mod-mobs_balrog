# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](https://semver.org/).


## [Unreleased]

	- No further addition planned.


## [0.6.0] - 2024-03-30
### Added

	- detect nether and spawn into right nodes, more deep if and more chance

### Changed

	- prevent balrogs from spawning on trap nodes, using stone group
	- make the balrog whip act as a wielded light source
	- check user validation on use to avoid crash on disconected
	- keep balrog whip drop from exploding with the balrog due lagfix
	- improved information in the mod.conf, no shit of forums or contendb



## [0.5.0] - 2021-11-27
### Added

	- backguard older compatibility on localization.
	- improved information in the source, no shit of forums or contendb
	- added spanish translation

### Changed

	- init.lua - error due mistake in prtection area integration
          https://codeberg.org/minenux/minetest-mod-mobs_balrog/issues/3
	- backguar compatibility with intllib for 0.4 minetest
          https://codeberg.org/minenux/minetest-mod-mobs_balrog/issues/2



## [0.4.0] - 2019-10-16
### Added

	- Support for localization.

### Changed

	- mod.conf to follow MT v5.x specifics.
	- Textures have been optimized (with optipng).

### Removed

	- Support for MT v4.x



## [0.3.5] - 2018-08-23
### Changed

	- fixed deprecated lua api calls
	- minor code improvements

### Removed

	- balrog_model.b3d (identical to mobs_balrog.b3d)



## [0.3.4] - 2018-07-10
### Added

	- changelog.md

### Changed

	- fixed the knock_back bug
	- increased the jump height to 16 nodes (was 4)
	- moved constant values into entity's definition/spawner function
	- README.txt -> README.md
