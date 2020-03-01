---
title: "Downloads"
date: 2020-02-27T23:30:00+00:00
draft: false
menu: "main"
---
The latest release is Glimpse Image Editor 0.1.2, and it is provided under the terms of the GNU General Public License v3. [Release Notes](/posts/glimpse-0-1-2-release-notes/)

### Windows
Glimpse Image Editor 0.1.0 is supported on 32-bit and 64-bit systems running Windows 7 or later.

#### Glimpse Image Editor 0.1.2 installer
[Direct download](https://github.com/glimpse-editor/Glimpse/releases/download/v0.1.2/glimpse-0.1.2.msi) |*Sha256: TBD*

You can download previous versions for Windows [from Github](https://github.com/glimpse-editor/Glimpse/releases/).

### Linux
We distribute Glimpse Image Editor 0.1.2 on Flathub for end users. We also provide a source tarball for Linux distribution maintainers. A Linux AppImage will be published before the end of March 2020.

#### Flatpak
If Flatpak is not already installed on your machine, follow these instructions: https://flatpak.org/setup/

Once setup is complete you can find Glimpse by searching in your distribution's software center, or you can click on this button:

<a href="https://flathub.org/apps/details/org.glimpse_editor.Glimpse">
    <img src="https://flathub.org/assets/badges/flathub-badge-en.png" alt="Download on Flathub" width="240">
</a>

Alternatively you can install it manually at the command line:
```
$ flatpak install flathub org.glimpse_editor.Glimpse
```

#### Source tarball
[Direct download](https://github.com/glimpse-editor/Glimpse/releases/download/v0.1.2/glimpse-0.1.2.tar.gz) |*Sha256: TBD*

**Please note:** We are still in the process of refactoring certain subcomponents, so you may need to mark `libgimp` as a conflicting package. [More details](https://github.com/glimpse-editor/Glimpse/issues/7)

#### Community-supported sources
These packages are provided by third parties in the wider Glimpse community. We sometimes merge changes to the codebase they provide us with but they are not directly supported by the Glimpse project.

* [Glimpse](https://snapcraft.io/glimpse-editor) on Snapcraft
* [`glimpse-editor-git`](https://aur.archlinux.org/packages/glimpse-editor-git/) in the AUR

### MacOS
The Glimpse project does not currently support the MacOS platform, but we are actively working on it.

As a temporary work-around, we recommend using the [Seashore](https://en.wikipedia.org/wiki/Seashore_%28software%29) variant of the GNU Image Manipulation Program instead.

### Build our code
We have provided instructions for building and packaging the Glimpse Image Editor source code on our project wiki: https://wiki.glimpse-editor.org/index.php?title=Building_Glimpse

You can also test out our own beta and development releases by following these instructions: https://wiki.glimpse-editor.org/index.php?title=Testing_Glimpse
