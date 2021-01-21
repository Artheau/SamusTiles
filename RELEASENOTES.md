# SpriteSomething

This release of SpriteSomething includes many basic features of the main design of the program.

## Updates Since Last Version

* Update to Python 3.8 which is the last to support Pillow 6.2.2. A bug was introduced into Pillow 7.0+ that changes how colors are altered. This needs to be figured out before we can upgrade to Python 3.9.
* Drop tested support for Ubuntu 16.04.
* Prepare tested support for Ubuntu 20.04 when GitHub Actions [rolls it out for its virtual environments](https://github.com/actions/virtual-environments/issues/1816).

## Features

### Supported Games

* The Legend of Zelda: A Link to the Past
  * Several romhacks thereof
* ALttP Randomizer
  * Item Randomizer
  * Enemy Randomizer
  * Entrance Randomizer
* Super Metroid
  * Several romhacks thereof
* Super Metroid Randomizer
  * Item Randomizer
* Super Metroid/A Link to the Past Combo Randomizer

### General Features included in this version

* Open sprite from flattened PNG, compiled ZSPR
* Extract sprite from supported game file
* Read/Write ZSPR sprite metadata
* Export sprite as flattened PNG, compiled ZSPR, compiled RDC
* Inject sprite into supported game file; single or a directory (experimental)
* Export current animation frame as PNG
* Export current animation as GIF
* Export current animation as horizontal collage

### Animation Features included in this version

* Bundled backgrounds
* Directional controls
* Palette selection controls
* Zoom controls
* Playback controls
* Download Official ALttPR Sprites
* Download Link sprites as included by the SpriteSomething team
* Download Samus sprites as included by the SpriteSomething team

### Lesser-documented features in this version

* Command-line interface

## Executable Builds

* We currently use GitHub Actions to build the bundled executables with each release. Travis CI was used initially and does most of what we want. GitHub Actions has since matured and is able to produce all that we need now.

* Executables for Linux (built on Ubuntu Bionic), MacOSX (built on 10.15 xcode 11.2.1) and Windows (built on Windows Server 2019) all built on python 3.7 are available.

### Build from source

If you would prefer to run/build from source, you can download the source code for this release below.  See `docs/BUILDING.md` for instructions.
