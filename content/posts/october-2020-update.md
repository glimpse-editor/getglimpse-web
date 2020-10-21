---
title: "October 2020 Update"
date: 2020-10-21T18:45:00+01:00
draft: false
---
Check out our [Contribute](/contribute/) page for social media and news links to follow our progress.

We have some cool milestones coming up, and would like to thank everyone that helped us to reach them:
- 1 year since we released Glimpse Image Editor 0.1.0 (21st November 2020)
- 18 months since we started the project (6th January 2020)

## Windows support changes
In response to end user feedback, we have now changed the "recommended" download to the x64 (64-bit) version of Glimpse Image Editor 0.2.0. You can see this change on our [downloads](https://glimpse-editor.github.io/downloads/) page.

The x86 (32-bit) version is now referred to as the "legacy" download, as we intend for Glimpse Image Editor 0.2.2 to be the last release that supports 32-bit versions of Windows. That is because neither our project nor upstream regularly test on that platform, almost all workstation CPUs now in circulation support x64 instructions, and we understand that Microsoft plans to release an x64 emulation layer for the ARM platform within the next year or so. For more information about how this helps our project, read [this wiki page](https://github.com/glimpse-editor/Glimpse/wiki/Supported-Platform-Versions-%28Windows%29).

We have also reinstated the download link for Glimpse Image Editor 0.1.2. This reflects the ongoing popularity of that release with Windows users, and the much better binary compatibility for existing GNU Image Manipulation Program plugins that it provides. For future releases, we intend to rebuild and repackage the most popular plugins for Glimpse specifically to fix compatibility problems.

CPU platform support for Linux remains unchanged. If you are using an x64 CPU then you have free choice of any supported installation method. We recommend you use [the Snap Store](https://snapcraft.io/glimpse-editor) for x86 CPUs, and [Flathub](https://flathub.org/apps/details/org.glimpse_editor.Glimpse) for AARCH64 devices. Community-supported repositories may provide additional installation options for those CPU platforms.

## Glimpse Image Editor 0.2.0 released on the Snap Store
On 2020-09-28 we successfully published Glimpse Image Editor 0.2.0 to [the Snap Store](https://snapcraft.io/glimpse-editor). Our apologies for the delay, but there were some blockers behinds the scenes we needed to work through. We are grateful for the assistance we received from Canonical to resolve them.

You can see full details about how that progressed via this Github Issue: [#477](https://github.com/glimpse-editor/Glimpse/issues/477)

## Glimpse Image Editor 0.2.0 released as a Linux AppImage
As promised, on 2020-09-20 we released our very first automatically-built Linux AppImage. This "universal binary" is built from the tip of our development branch, and is primarily intended for Linux enthusiasts and testing purposes.

You can see full details about how that progressed via this Github Issue: [#108](https://github.com/glimpse-editor/Glimpse/issues/108)

## Progress on distributing our Windows port via Scoop
As you will see on our downloads page, you can already download Glimpse Image Editor via [Chocolatey](https://chocolatey.org/packages/glimpse/) and [WinGet](https://winget.run/pkg/Glimpse/Glimpse). We understand that [bb010g](https://github.com/bb010g) is currently working on publishing our Windows installer for the automated [Scoop](https://scoop.sh/) package manager. 

You can track progress on that work via this Github Issue: [#65](https://github.com/glimpse-editor/Glimpse/issues/65)

## MacOS port progress has stalled
Full details have been provided in a comment on this Github Issue: [#402 (comment)](https://github.com/glimpse-editor/Glimpse/issues/402#issuecomment-706778462)

We would like to stress that we have not given up on the idea of producing a MacOS port for Glimpse Image Editor, but unfortunately until the GNU Image Manipulation Program developers themselves are able to successfully build and package the software for MacOS again, we will not be able to recreate it here in this downstream project.

If you are a MacOS user, we suggest that you continue using the GNU Image Manipulation Program 2.10.14 for the time being. Alternatively, you can run the Windows or Linux versions of Glimpse Image Editor 0.2.0 from inside a virtualized environment.

## Work tentatively begins on Glimpse Image Editor 0.2.2
As promised, we intend to improve third-party plugin support for Glimpse Image Editor 0.2.2. As part of that initiative we plan to customize and prebundle a number of different plugins that our users may find useful.

G'MIC is already provided with our 64-bit Windows port, but we expect to provide it across all other packaging methods. [#465](https://github.com/glimpse-editor/Glimpse/issues/465)

We also intend to include the remainder of PhotoGIMP where commercial/academic use is permitted for those assets. [#414](https://github.com/glimpse-editor/Glimpse/issues/414) 

You can track progress on other plugins via these Github Issues: [#441](https://github.com/glimpse-editor/Glimpse/issues/441), [#466](https://github.com/glimpse-editor/Glimpse/issues/466) & [#467](https://github.com/glimpse-editor/Glimpse/issues/467)

## Planning for the future with Glimpse Redux
Bobby Moss has already created an initial private fork of the pre-release code for the GNU Image Manipulation Program 3.0.0. Over the coming year he will gradually customize that fork, and once it is at least "alpha" quality that work will be pushed to a new branch in the [existing Github repository](https://github.com/glimpse-editor/Glimpse) we use to host the Glimpse source code.

We believe this work will be crucial in guaranteeing the future of the Glimpse project, as the GNU Image Manipulation Program developers will eventually switch across to their future 3.0.0 technology stack and deprecate 2.10.x.

## Early investigation work starts on Glimpse NX
Christopher Davis has already started familiarising himself with the technology stack we plan to use for this project. There have also been some excellent ideas introduced by our community on the Glimpse Discord server. We encourage anyone that is interested in participating with this effort to consider [requesting to join the server](https://discord.gg/hZhRceq).
