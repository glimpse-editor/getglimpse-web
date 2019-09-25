---
title: "Glimpse 0.1.0 Released"
date: 2019-09-30T18:00:00+01:00
draft: true
---
**DRAFT PLACEHOLDER DO NOT PUBLISH**

*Add a screenshot here*

## Install
Glimpse 0.1.0 is currently supported on:
* Windows 7 or later
* Modern Linux distributions configured to use [Flatpaks](https://flathub.org/home).

 Over the coming weeks and months we intend to provide more installation options on our [Downloads](../../downloads/) page.

## Known Issues
* Linux AppImage is delayed until October 2019
* MacOS port is blocked, so no release timeline yet
* GUI still links to upstream help pages
* Manpages have not been updated
* Wilber mascot is still present in many parts of the UI
* For compatibility purposes the underlying code still uses "GIMP" name for many code files, classes, libraries, methods and command line flags

## New Features
Glimpse 0.1.0 is based on [GNU Image Manipulation Program 2.10.12](https://www.gimp.org/news/2019/06/12/gimp-2-10-12-released/). It also uses the following dependency package versions:

* [BABL](http://www.gegl.org/babl/) 0.1.68
* [GEGL](http://www.gegl.org/) 0.4.16
* [MyPaint](http://mypaint.org/) 1.3.0

### Graphical User Interface
* Translation files, code & build files updated so "Glimpse" is displayed throughout the UI, executables and packages
* Changed the default UI behaviour for a cleaner look
* Replaced application logo and window/taskbar icons
* Replaced initial splash screen
* Updated upstream icon themes to include our own iconography
* Replaced links in the "Help" menu
* Updated the About window
* Removed code for upstream "easter eggs"

### Code Improvements
* Refactored the automated "authors" system for the Glimpse project
* Refactored the build system for the Glimpse project
* Removed scripts and tooling we do not use this with this fork
* Updated the Flatpak build process
* Updated the Snapcraft build process *TODO*
* Added Travis CI support to sanity check builds in version control
* Refactored the Windows installer creation scripts *TODO*

### Developer Assistance
* Added BABL, GEGl and MyPaint dependencies as git submodules pre-set at the current tagged releases
* Added [Vagrant](https://www.vagrantup.com/) support so the code can be built & run without needing to install the prerequisites on the host system
* Provided comprehensive build documentation for Windows and Linux at https://wiki.glimpse-editor.org/index.php?title=Building_Glimpse
* Improved integration with the GNOME Builder IDE
* Provided new code level documentation of our own (such as code of conduct, contributing guide, changelog, etc) *TODO*

### Quality of Life Improvements
* Removed legacy upstream documentation not needed for this fork
* Changed installation & configuration files location to avoid conflicts
* Changed cached and temporary files location to avoid conflicts
* Changed process identifiers so they do not conflict with other running instances of the GNU Image Manipulation Program
* Added our own metadata for built and packaged executables
* Removed "Color" icons (duplicates "Legacy")
* Removed "Gray" UI theme (duplicates "System")
* Updated or replaced GNOME-specific metadata files
* Maintained compatibility with existing GNU IMP v2.x plug-ins

### Maintainers / Governance Team
* Bobby Moss
* Christopher Davis
* Clipsey

### Code Contributors
* igalic
* Mathieu Bridon

## Documentation Contributors
* chaomodus
* Dominic Watson
* melody

### Artwork Contributors
* James Daniel

### Sponsor Contributors
* Kretz
* Loren Dias
* Massimo D'Ambrogio
* Roberts-Loux Foundation
* Sami Mannila

### $5+ Tier Patreon & Open Collective Contributors
We would like to say a special thank you to all of our financial backers regardless of whether they are listed below or not. Without your help this release would not have been possible, and your continued support is highly appreciated.

* Brandon 'Spanky' Mills
* Dominic Watson
* G Cowell
* Kevin Rodriguez
* Kretz
* Loren Dias
* Massimo D'Ambrogio
* nitrohorse
* Pagrus
* Sami Mannila
* Samuel Pickard
* Stan Sorochan
* Transmutable

*More screenshots here?*
