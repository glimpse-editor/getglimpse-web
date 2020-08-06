---
title: "Glimpse 0.1.2 Release Notes"
date: 2020-03-02T17:00:00+00:00
draft: false
---
This release iterates on our very first "minimal viable product" release. The primary objective was to improve the experience for Windows users and fix non-English translation files.

This is also the first release where we have provided a source tarball for Linux distribution packagers. Please note that you will need to mark `libgimp` as a conflicting package as there is a lot of code and file name refactoring we still need to do.

We also took community feedback on board and reinstated the "Color" icon pack and "Grey" UI theme. Upstream contributors are also now credited in **Help** > **About** > **Credits**.

## Installation
Linux users can install Glimpse Image Editor 0.1.2 as a Flatpak from the Flathub repository. There are also a number of additional installation options for Linux detailed on our [Downloads](/downloads/) page.

Windows users can use an MSI file to install Glimpse Image Editor 0.1.2 on 32-bit and 64-bit systems running Windows 7 or later. We chose that type of installer to assist businesses and schools using centralised software management systems. This can also be found on the [Downloads](/downloads/) page.

## Known Issues
* Linux AppImages for 0.1.0 and 0.1.2 are not yet available [#108](https://github.com/glimpse-editor/Glimpse/issues/108)
* Windows users cannot run Python plug-ins [#178](https://github.com/glimpse-editor/Glimpse/issues/178)
* There is no macOS port at the current time [#227](https://github.com/glimpse-editor/Glimpse/issues/227)
* Man pages in the terminal have not been updated
* Compatibility with upstream offline help pages has not been tested

## New Features
Glimpse 0.1.2 is still based on [GNU Image Manipulation Program 2.10.12](https://www.gimp.org/news/2019/06/12/gimp-2-10-12-released/). It also still uses the following dependency package versions:

* [BABL](http://www.gegl.org/babl/) 0.1.68
* [GEGL](http://www.gegl.org/) 0.4.16
* [MyPaint](http://mypaint.org/) 1.3.0

### Windows Improvements
* Translation files are now included in the MSI installer [#240](https://github.com/glimpse-editor/Glimpse/issues/240)
* Glimpse Image Editor and GNU Image Manipulation Program no longer share the same task bar icon [#247](https://github.com/glimpse-editor/Glimpse/issues/247)
* Windows installer now supports upgrading existing installations [#314](https://github.com/glimpse-editor/Glimpse/pull/314)

### UI Improvements
* "Color" icon pack and "Gray" UI theme have been reinstated [#232](https://github.com/glimpse-editor/Glimpse/issues/232)
* The "fun" brushes have now been removed [#286](https://github.com/glimpse-editor/Glimpse/issues/286)
* Upstream contributors and translators are now appropriately credited through the UI [#228](https://github.com/glimpse-editor/Glimpse/issues/228)
* Renamed the "Gimpressionist" plug-in to "Impressionist" [#267](https://github.com/glimpse-editor/Glimpse/issues/267)
* Fixed various problems in translation files [#230](https://github.com/glimpse-editor/Glimpse/issues/230) [#238](https://github.com/glimpse-editor/Glimpse/issues/238)
* Fixed text color chooser that still used Wilber icon and upstream name [#250](https://github.com/glimpse-editor/Glimpse/issues/250)
* Fixed "legacy" UI theme in Snapcraft [#271](https://github.com/glimpse-editor/Glimpse/pull/271)

### Code Improvements
* Moved `build` folder to `build-aux` to follow GNOME conventions [#233](https://github.com/glimpse-editor/Glimpse/issues/233)
* Added packaging documentation to the `snap` and `flatpak` folders to match `windows-msi` [#305](https://github.com/glimpse-editor/Glimpse/pull/305)
* Fixed `make check` so we can produce source tarballs for Linux distribution maintainers [#251](https://github.com/glimpse-editor/Glimpse/pull/251)

## Credits
We would like to thank everyone who contributed towards making Glimpse 0.1.2 a success, particularly those unnamed individuals who spread the word about our project on social media, shared their feature requests with us and provided feedback to the development team during the beta testing phase.

### Creator
* Bobby Moss

### Maintainers
* chaomodus
* Christopher Davis
* Luna

### Code Contributors
* Heather Ellsworth
* Ken VanDine
* Mathieu Bridon
* Mike Burns
* skyejonke

### Documentation Contributors
* Dave Kretz

### Artwork Contributors
* James Daniel

### $20+ Tier Sponsor Contributors
* Sami Mannila

### $5+ Tier Backers and One-off Donors
We would like to say a special thank you to all of our financial backers on [Open Collective](https://opencollective.com/glimpse) regardless of whether they are listed below or not. Without your help this release would not have been possible, and your continued support is highly appreciated.

* Chris 
* Conner
* Dzuk
* Janne Marko
* Jes Wolfe
* kretz
* Magnus Gustafsson
* nitrohorse
* Samuel Pickard
* Stan Sorochan
* Tim Dehring
* Transmutable
