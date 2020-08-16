---
title: "Downloads"
date: 2020-08-11T22:00:00+01:00
draft: false
menu: "main"
---
The latest release is Glimpse Image Editor 0.2.0. It is based on the [GNU Image Manipulation Program](https://www.gimp.org/) 2.10.18, and is provided under the terms of the GNU General Public License v3. [Release Notes](/posts/glimpse-0-2-0-release-notes/)

### Windows
Glimpse Image Editor 0.1.2 Gold Edition is supported on 32-bit and 64-bit systems running Windows 7 or later.

#### Glimpse Image Editor 0.1.2 Gold Edition installer
This installer adds many of the same improvements introduced in Glimpse Image Editor 0.2.0, but sticks to the same tried and tested GNU Image Manipulation Program 2.10.12 base.

**glimpse-0.1.2-gold.msi** | [Direct download](https://github.com/glimpse-editor/Glimpse/releases/download/v0.2.0/glimpse-0.1.2-gold.msi) | *Sha256:*

You can download previous versions of Glimpse Image Editor for Windows [from Github](https://github.com/glimpse-editor/Glimpse/releases/).

### Linux
We distribute Glimpse Image Editor 0.2.0 on Flathub and Snapcraft for end users. We also provide a source tarball for Linux distribution maintainers.

To assist users of some Linux distributions, and AppImage is also planned. [#108](https://github.com/glimpse-editor/Glimpse/issues/108)

#### Flatpak
If `flatpak` is not already installed on your machine, follow these instructions: https://flatpak.org/setup/

Once setup is complete you can find Glimpse Image Editor by searching in your distribution's software center, or you can [click on this link](https://flathub.org/apps/details/org.glimpse_editor.Glimpse) from Flathub.

Alternatively you can install it manually at the command line:
```
$ flatpak install flathub org.glimpse_editor.Glimpse
```

If you would prefer to use your own third party repository for dependency resolution instead of Flathub, we also provide a [single-file bundle](https://docs.flatpak.org/en/latest/single-file-bundles.html):

**glimpse-0.2.0.flatpak** | [Direct download](https://github.com/glimpse-editor/Glimpse/releases/download/v0.2.0/glimpse-0.2.0.flatpak) | *Sha256:*

To install the single-file bundle at the command line:
```
$ flatpak install glimpse-0.2.0.flatpak
```

#### Snap
If `snapd` is not already installed on your machine, follow these instructions: https://snapcraft.io/docs/getting-started

Once setup is complete you can find Glimpse Image Editor by searching in your distribution's software center, or you can [click on this link](https://snapcraft.io/glimpse-editor/) from the Snap Store.

Alternatively you can install it manually at the command line:
```
$ sudo snap install glimpse-editor
```

#### Source tarball
**glimpse-0.2.0.tar.bz2** | [Direct download](https://github.com/glimpse-editor/Glimpse/releases/download/v0.2.0/glimpse-0.2.0.tar.bz2) | *Sha256:*

**glimpse-0.2.0.tar.xz** | [Direct download](https://github.com/glimpse-editor/Glimpse/releases/download/v0.2.0/glimpse-0.2.0.tar.xz) | *Sha256:*

Please note that we are still in the process of refactoring certain subcomponents, so distribution maintainers need to mark `libgimp` as a conflicting package. [More details](https://github.com/glimpse-editor/Glimpse/issues/7)

#### Community-supported sources
These builds are provided by third parties in the wider Linux community. We do not create, package or directly support these sources, so if you raise any bugs for them that would not apply to most Linux users, we may direct you elsewhere to get the issue fixed.

* [`glimpse-editor-git`](https://aur.archlinux.org/packages/glimpse-editor-git/) in the AUR
* [`glimpse:IBBboard`](https://software.opensuse.org//download.html?project=home%3AIBBoard%3Adesktop&package=glimpse) on the OpenSUSE Open Build Service

### MacOS
Unfortunately Glimpse Image Editor is not supported on MacOS. We recommend either running the Windows version in a virtualized environment or sticking with the [GNU Image Manipulation Program](https://www.gimp.org/downloads/). 

You may also be interested in trying [Seashore](https://apps.apple.com/us/app/seashore/id1448648921?mt=12), an older fork of the GNU Image Manipulation Program designed specifically for MacOS. While it does have fewer features, it may still be suitable for your intended use case.

We are investigating the possibility of distributing Glimpse Image Editor through [HomeBrew](https://brew.sh/), a popular third-party package manager for macOS. [#402](https://github.com/glimpse-editor/Glimpse/issues/402)

### Build our code
We have provided instructions for building and packaging the Glimpse Image Editor source code on our project wiki: https://github.com/glimpse-editor/Glimpse/wiki

You can also test out our own beta and development releases by following these instructions: https://github.com/glimpse-editor/Glimpse/wiki#testing
