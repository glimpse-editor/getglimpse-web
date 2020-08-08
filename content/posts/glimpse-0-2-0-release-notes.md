---
title: "Glimpse 0.2.0 Release Notes"
date: 2020-08-08T18:45:00+01:00
draft: false
---
This release rebases Glimpse Image Editor on the GNU Image Manipulation Program 2.10.18, introduces helpful configuration settings from [PhotoGIMP](https://github.com/Diolinux/PhotoGIMP), and adds native 64-bit support on Windows.

We have completely rewritten our Windows installers from scratch, providing users with the option to install in custom locations, and finally deprecating support for Python 2 components on that platform. We have also pre-bundled [G'MIC](https://gmic.eu/) with our 64-bit Windows installer.

Key underlying dependencies and changes have also been backported to provide a more stable and secure experience for all Glimpse Image Editor users across Windows and Linux.

## Installation
Linux users can install Glimpse Image Editor 0.2.0 as a Flatpak from the Flathub repository, and as a Snap from the Snap Store. There are also a number of additional installation options for Linux detailed on our [Downloads](/downloads/) page.

Windows users can use an MSI file to install Glimpse Image Editor 0.2.0 on 32-bit and 64-bit systems running Windows 7 or later. We chose that type of installer to assist businesses and schools using centralised software management systems. The two we have provided can also be found on the [Downloads](/downloads/) page.

## Known Issues
* [Windows](https://github.com/glimpse-editor/Glimpse/wiki/Known-Issues-%28Windows%29)
* [Linux](https://github.com/glimpse-editor/Glimpse/wiki/Known-Issues-%28Linux%29)

## New Features
Glimpse 0.2.0 is based on [GNU Image Manipulation Program 2.10.18](https://www.gimp.org/news/2020/02/24/gimp-2-10-18-released/). It also still uses the following dependency package versions:

* [BABL](http://www.gegl.org/babl/) 0.1.78
* [GEGL](http://www.gegl.org/) 0.4.22
* [LibMyPaint](http://mypaint.org/) 1.5.1
* [MyPaint-Brushes](http://mypaint.org/) 1.3.1 

### UI Improvements
* Added PhotoGIMP keyboard shortcuts and some custom configuration settings
* Replaced Glimpse logo with high resolution version with "sticker" white border
* Updated website and documentation links throughout the application
* Customized existing icon packs, replacing Wilber with the Glimpse logo
* Backported and customized high contrast icon packs
* Backported bugfix for [upstream issue #4487](https://gitlab.gnome.org/GNOME/gimp/issues/4487)

### Windows Improvements
* Replaced WiX manifest files with more efficient replacements
* Added a new 64-bit Windows installer with G'MIC prebundled
* Added an RTF version of the GNU GPLv3 to both installers
* Added support for custom install locations
* Fixed missing "Open With..." option for Glimpse Image Editor
* Fixed default file associations

### Linux Improvements
* Builds delivered through Flathub and the Snap Store are now fully reproducible
* Added generated single-file bundle flatpaks to Github Actions

### Developer Improvements
* Added Github Actions to build and package `dev-g210`, `beta-g210` and `glimpse-0-2` branches
* Updated our documentation and build jobs to account for new `meson` build steps
* Included `intl.dll` with the source code to assist the Windows packaging process
* The `HACKING.md` file has been updated with the new build process
* The `README.md` files provided in the `build-aux` folder have also been updated
* Deprecated `babl`, `gegl`, `mypaint-brushes` and `libmypaint` git submodules provided for convenience only
* Deprecated Vagrant quickstart process and associated Ansible playbook

## Credits
We would like to thank everyone who contributed towards making Glimpse 0.2.0 a success, particularly those unnamed individuals who spread the word about our project on social media, shared their feature requests with us and provided feedback to the development team during the beta testing phase.

### Creator
* Bobby Moss

### Maintainers
* Christopher Davis
* Luna

### Code Contributors
* chaomodus
* Cynthia Revström
* Diolinux
* Heather Ellsworth
* Zoé Bőle

### Documentation Contributors
* Dave Kretz

### Artwork Contributors
* Atra
* James Daniel
* Zach Krall

### $20+ Tier Sponsor Contributors
* Marc

### $5+ Tier Backers and One-off Donors
We would like to say a special thank you to all of our financial backers on [Open Collective](https://opencollective.com/glimpse) regardless of whether they are listed below or not. Without your help this release would not have been possible, and your continued support is highly appreciated.

* Bobby Moss
* Chris Daley
* Christopher Davis
* Conner
* Dave Kretz
* narF
* Nitrohorse
* Richard Hendricks
* Samuel Pickard
* Stan Storochan
* Tim Dehring
* Transmutable
