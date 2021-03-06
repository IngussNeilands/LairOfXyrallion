# Change Log
All notable changes to Lair of Xyrallion are documented in this file.  
LoX uses version numbers in format w.x.y.z where:
- w is the major version
- x is the minor verison
- y is the release status (0=alpha, 1=beta, 2=release candidate, 3=final)
- z is the patch number

## [0.1.0.4] - 2015-06-
##Added
- Main menu

##Changed
- Map is now drawn dynamically, with the player always centered.

##Fixed
- Armour items can now be generated.

## [0.1.0.3] - 2015-06-07
##Added
- Window system for easier drawing management and neater screen layout
- Implemented a basic state machine for future menu systems and flow control

##Changed
- Some renderer methods have been switched to private, and are instead called through one ‘super’ method

## [0.1.0.2] - 2015-06-02
### Added
- Now using colour on supported terminals

### Removed
- Removed Psionic races and classes

## [0.1.0.1] - 2015-05-31
### Changed
- Renderer now uses lookup table to determine which symbol to display tiles/items/creatures as.

### Fixed
- Messages now print at line 21 rather than 24, which was offscreen on default 80x24 terminals.

## [0.1.0.0] - 2015-05-31
### Added
- Added changelog and version number (starting from 0.1.0.0).
- See git logs previous to commit 12d48be518d11b2da62bb42ade88a7e4f9ef33cf for additions prior to this log.
