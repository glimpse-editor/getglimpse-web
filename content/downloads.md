---
title: "Downloads"
date: 2020-04-10T21:00:00+01:00
draft: false
menu: "main"
---
The latest release is Glimpse Image Editor 0.1.2, and it is provided under the terms of the GNU General Public License v3. [Release Notes](/posts/glimpse-0-1-2-release-notes/)

### Windows
Glimpse Image Editor 0.1.2 is supported on 32-bit and 64-bit systems running Windows 7 or later.

#### Glimpse Image Editor 0.1.2 installer
**glimpse-0.1.2.msi** | [Direct download](https://github.com/glimpse-editor/Glimpse/releases/download/v0.1.2/glimpse-0.1.2.msi) | *Sha256: 99C3DF2884310CB74C39A15FB63E93FBF2112F581DC5325B37123467618D89E8*

If you are having problems with this installer, we also provide an [unsigned version](https://github.com/glimpse-editor/Glimpse/releases/download/v0.1.2/glimpse-0.1.2-unsigned.msi) for troubleshooting purposes. Please note that the unsigned installer will trigger security warnings from Windows and your installed anti-virus program.

You can download previous versions for Windows [from Github](https://github.com/glimpse-editor/Glimpse/releases/).

### Linux
We distribute Glimpse Image Editor 0.1.2 on Flathub and Snapcraft for end users. We also provide a source tarball for Linux distribution maintainers. A Linux AppImage will be published before the end of March 2020.

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

#### Snapcraft
If Snapcraft is not already installed on your machine, follow these instructions: https://snapcraft.io/docs/getting-started

Once setup is complete you can find Glimpse Image Editor by searching in your distribution's software center, or you can click on this button:

<iframe src="https://snapcraft.io/glimpse-editor/embedded?button=black" frameborder="0" width="100%" height="250px" style="border: 1px solid #CCC; border-radius: 2px;"></iframe>

Alternatively you can install it manually at the command line:
```
$ sudo snap install glimpse-editor
```

#### Source tarball
**glimpse-0.1.2.tar.bz2** | [Direct download](https://github.com/glimpse-editor/Glimpse/releases/download/v0.1.2/glimpse-0.1.2.tar.bz2) | *Sha256: f9845f7a5ce1aece5c0c808b2fa7ba91ce657b942d6e777bbab5c0abb6f2499a*

**glimpse-0.1.2.tar.xz** | [Direct download](https://github.com/glimpse-editor/Glimpse/releases/download/v0.1.2/glimpse-0.1.2.tar.xz) | *Sha256: b1086b7effd9a3f4a9b4577bb4c3bf69d86f8c60a3c4fe9966aeefb7150deb0d*

Please note that we are still in the process of refactoring certain subcomponents, so distribution maintainers need to mark `libgimp` as a conflicting package. [More details](https://github.com/glimpse-editor/Glimpse/issues/7)

#### Community-supported sources
These builds are provided by third parties in the wider Linux community. We do not create, package or directly support these sources, so if you raise any bugs for them that would not apply to most Linux users, we may direct you elsewhere to get the issue fixed.

* [`glimpse-editor-git`](https://aur.archlinux.org/packages/glimpse-editor-git/) in the AUR
* [`glimpse:IBBboard`](https://software.opensuse.org//download.html?project=home%3AIBBoard%3Adesktop&package=glimpse) on the OpenSUSE Open Build Service

### MacOS
Unfortunately Glimpse Image Editor is not supported on MacOS. We recommend either running the Windows version in a virtualized environment or sticking with [the GNU Image Manipulation Program](https://www.gimp.org/downloads/). 

You may also be interested in trying [Seashore](https://apps.apple.com/us/app/seashore/id1448648921?mt=12), an older fork of the GNU Image Manipulation Program designed specifically for MacOS. While it does have fewer features, it may still be suitable for your intended use case.

### Build our code
We have provided instructions for building and packaging the Glimpse Image Editor source code on our project wiki: https://wiki.glimpse-editor.org/index.php?title=Building_Glimpse

You can also test out our own beta and development releases by following these instructions: https://wiki.glimpse-editor.org/index.php?title=Testing_Glimpse
