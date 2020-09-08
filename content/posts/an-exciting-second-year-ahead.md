---
title: "An Exciting Second Year Ahead"
date: 2020-09-08T08:45:00+01:00
draft: false
---
Check out our [Contribute](/contribute/) page for social media and news links to follow our progress.

We are pleased to say that the reception for Glimpse Image Editor 0.2.0 from our own users has been very positive. The Glimpse project governance team would particularly like to thank Windows and Linux packagers in the wider free software community for making our work more widely available.

## Early Plans for Glimpse Image Editor 0.2.2 and 0.3.0
Detailed below are remaining items of work for Glimpse Image Editor 0.2.0, and our development priorities for the next two releases. **These are all provisional plans, and are subject to change**.

### Glimpse Image Editor 0.2.0
* Update the Snap store
* Complete the Linux AppImage [#108](https://github.com/glimpse-editor/Glimpse/issues/108)
* Distribute our Windows installer through Scoop [#65](https://github.com/glimpse-editor/Glimpse/issues/65)
* Port to macOS and distribute through Homebrew [#402](https://github.com/glimpse-editor/Glimpse/issues/402)

### Glimpse Image Editor 0.2.2 (aiming for January/February 2021)
* Include most of PhotoGIMP (we cannot use assets with licenses that prohibit commercial/academic use)
* Include G'MIC by default across all first party packaging and distribution methods
* Port other useful third-party plugins (such as BIMP, Liquid Rescale and Resynthesizer)
* Add polish to the new Windows MSI installers we introduced in 0.2.0 [#459](https://github.com/glimpse-editor/Glimpse/issues/459)

### Glimpse Image Editor 0.3.0 (aiming for July/August 2021)
* Rebase on a newer Glimpse Image Editor 2.10.x release
* Refactor libgimp* and manual pages to fix Linux repository packaging conflicts [#7](https://github.com/glimpse-editor/Glimpse/issues/7)
* Document how to build DEB and RPM packages to assist Linux distro maintainers
* Support offline help pages provided by the GNU Image Manipulation Program [#331](https://github.com/glimpse-editor/Glimpse/issues/331)

## Introducing Glimpse Redux
"Glimpse Redux" is the codename we are using for the preparation work we plan to start soon for an eventual re-fork on the (still to be released) GNU Image Manipulation Program 3.0.

Currently Glimpse Image Editor is based on GNU Image Manipulation Program 2.10.18, and our stable releases will continue to be based on upstream 2.10.x releases for as long as the upstream project continues to produce releases on the same code base. 

The reason why we need to work on this effort separately is because the GNU Image Manipulation Program 3.0 uses a different technology stack and has a slightly different featureset. It is also highly likely that 3.0 will deprecate most existing plugins and break many of the features we have already implemented.

So that our own users do not have to wait 12+ months for us to catch up after the GNU Image Manipulation Program 3.0 is released, we intend to create a new Github repository that follows the correct upstream branch so that we can gradually reimplement our customizations on that code ahead of time. When the GNU Image Manipulation 3.0 is eventually released, we will plan and schedule a smooth transition from the existing Glimpse Image Editor code to the Glimpse Redux code.

Initially the Github repository for Glimpse Redux will only be visible to our core contributors. Once we have produced the appropriate developer documentation and working reproducible builds, we will make the repository visible to the public so that we can open up this effort to third-party plugin developers and community software packagers.

To confirm, we will not be renaming Glimpse Image Editor. "Glimpse Redux" is a temporary codename we are using for the preparation work described above.

## Introducing Glimpse NX
Glimpse NX will be a free/libre software application using [GNOME](https://www.gnome.org/) technologies that provides a more lightweight and accessible user interface for the same underlying components that the GNU Image Manipulation Program uses. It will also be ported to Windows and MacOS.

We are still deciding which programming language to use, but [Rust](https://www.rust-lang.org/) is the most likely candidate. As we will be using components that are licensed under the [GNU LGPLv3](https://www.gnu.org/licenses/lgpl-3.0.html), we expect the project itself will be provided under the GNU General Public License v3 or a similar compatible license.

Further information for this exciting new spin-off project will be provided in coming months.

## Introducing Yuzu Studio
As stated in previous blog posts, we did originally consider the possibility of creating a new bespoke cross-platform user interface toolkit and then writing an entirely new BSD-licensed program based on it with the more estoteric [D](https://dlang.org/) programming language. 

A group of contributors investigated that solution, but after six months of incubation we collectively agreed that such an ambitious project cannot be delivered in a two year timeframe with the resources we have available.

However, there is still a lot of enthusiasm in the wider community for a free software image editing program that behaves more like a competitor to the GNU Image Manipulation Program. For that reason [Luna](https://twitter.com/Clipsey5) (a member of our governance team) is spinning out the idea into her own separate project called "Yuzu Studio", and the contributors involved have already been making some exciting progress on Luna's Discord server.

We wish her and everyone involved with Yuzu Studio the best of luck with that initiative, and we will provide further links for that project in a future blog post for anyone that may be interested in contributing to it.
