# RT-Customz KiCad Library

Library with additional symbols, footprints and 3D models.

# Installation

## Cloning the repository
A good place might be `~/Documents/kicad` but it can be freely choosen.
You can download the repository as zip and extract it, but when cloned with git,
it can be updated easily with `git pull`.

## Adding Symbols
* Open the symbol library manager (`Preferences`->`Manage Symbol Libraries...`)
* Click the folder icon (`Add Existing`) (make sure you add them under Global Libraries)
* Select one or more library to add (files with `.kicad_sym` extension)
* Repeat for every additional symbol library

![Symbol manager screenshot](/docs/res/symbol_manager.jpg)

## Adding Footprints
* Open the footprint library manager (`Preferences`->`Manage Footprint Libraries...`)
* Click the folder icon (`Add Existing`) (make sure you add them under Global Libraries)
* Select one or more library to add (folders with `.pretty` extension)
* Repeat for every additional footprint library

![Footprint manager screenshot](/docs/res/footprint_manager.jpg)

## Adding the path for 3d models
* Open the `Configure Paths` dialog (`Preferences`->`Configure Paths...`)
* Add a new entry (`+`)
* Set the name to `RTLIB_3DMODEL_DIR`
* Set the path to the 3d model folder

![Configure Paths screenshot](/docs/res/configure_paths.jpg)

## Graphics
Additionally the [grapics](/graphics) folder contains graphics and logos in svg format.
These can be imported directly onto a board.
This has the advantage that the layer and scale can be choosen freely.

# Contributing
For conventions how to design symbols, footprints and models, see the [Kicad Library Conventions](https://klc.kicad.org/).

Open a Pull request.

# License
_TODO_
