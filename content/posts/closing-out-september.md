---
title: "Closing Out September"
date: 2019-09-26T18:00:00+01:00
draft: false
---

Instead of providing a weekly reminder of our social media and project links across the web, check out our all-new [Contribute](../../contribute/) page!

## Updated release schedule
We have been working hard over the last two weeks, and we aim to provide beta test releases for Windows and Linux before the end of September 2019. With the help of our supporters trying them out when they are made available and reporting bugs they find we can expect to officially release Glimpse 0.1.0 around the middle of October 2019.

We apologise for the delay, but we believe it is important to release a robust application that people can use as a drop-in replacement for GNU Image Manipulation Program 2.10.12 and start working with as their daily driver.

Glimpse also does not have an internal update mechanism and could be deployed on centrally managed systems in schools and workplaces where stability is highly valued, so we do not feel that "release early, patch often" is the right approach for this project.

All of our core contributors thank you for your patience, and we will continue to work hard to make sure that Glimpse 0.1.0 achieves our stated objectives and makes you proud to support us.

## Help wanted
Work on a Linux AppImage has not yet started, so if you would like to try your hand at packaging then this Github issue is a great starting point: https://github.com/glimpse-editor/Glimpse/issues/108

Finally for those who still have concerns about our project name, the original poster of this Github issue is now hosting an unofficial spreadsheet to gather suggestions and informally canvas opinion on our behalf: https://github.com/glimpse-editor/Glimpse/issues/92

## Porting to Windows
Bobby Moss has been focussing most of his development time and energy over the past week on porting Glimpse to the Windows platform. You can see the progress he is making here: https://github.com/glimpse-editor/Glimpse/pull/152

At the time of writing our current plan is to port the upstream process for creating an installer. If that proves to be problematic then we will switch back to our previous plan of writing our own bespoke installer for Glimpse using the [WiX toolset](https://wixtoolset.org/) as described here: https://github.com/glimpse-editor/Glimpse/issues/119

The process of building the code on Windows using [MSYS2](https://www.msys2.org/) has been documented here: https://wiki.glimpse-editor.org/index.php?title=Building_Glimpse/Windows

## Documentation updates
Bobby Moss and Mathieu Bridon have created an excellent new section on the wiki that comprehensively covers how to build and package Glimpse on Linux and Windows. They have also added instructions for how to build the code from IDEs like [GNOME Builder](https://wiki.gnome.org/Apps/Builder) on Linux and [Visual Studio Code](https://code.visualstudio.com/) on Windows.

We hope you will find this useful, and you can see their work here: https://wiki.glimpse-editor.org/index.php?title=Building_Glimpse

## Code changes
Bobby Moss added support for [Travis CI](https://travis-ci.org/glimpse-editor/Glimpse/branches) so that every new commit and pull request is automatically sanity checked with a build before it is merged. Mathieu Bridon is currently working to enhance this by ensuring that unit tests are also run against the code.

Bobby Moss also updated the code so that our new splash screen and application icons are used throughout the application. He has also been fixing bugs related to folder locations and processes clashing with past or existing installations of the GNU Image Manipulation Program.

Mathieu Bridon has cleared away redundant files and been updating the metadata files used by GNOME desktop and Flatpak to ensure Linux users have an optimal experience when we release Glimpse 0.1.0. We look forward to him assisting us when we push the latest build to [Flathub](https://flathub.org/).

psymole and EndrII have also been working together to add [Snap](https://snapcraft.io/) support to the current codebase. We did not expect to be able to support this technology in time for Glimpse 0.1.0, so we are deeply grateful for their efforts: https://github.com/glimpse-editor/Glimpse/pull/153

## Project decisions
You can see which work items are still outstanding for Glimpse 0.1.0 here: https://github.com/glimpse-editor/Glimpse/milestone/1

In anticipation of us releasing Glimpse 0.1.0 we have donated $50 of backer funds to the GNU Image Manipulation Program. That exceeds our stated pledge that at least 10% of the funds we receive for this release will be donated to the upstream project. You can see a full accounting of the donations we have received and how we have started to spend them on our [Open Collective](https://opencollective.com/glimpse) page.

The Glimpse project also participated in the [Digital Climate Strike](https://digital.globalclimatestrike.net/) on Friday 20th September 2019 to show our support and solidarity with demonstrations being held around the world.

## Website updates
After a number of people provided feedback about it we updated the subtitle on the Glimpse home page to make our objectives clear. It now reads "Glimpse is an open source image editor based on the GNU Image Manipulation Program. The goal is to experiment with new ideas and expand the use of free software."

Christopher Davis has also taken on the task of redesigning our project website. We anticipate improvements to the overall layout and design in the weeks and months ahead.

Bobby Moss has also started drafting the Glimpse 0.1.0 release post and our new downloads page. You can preview that work here: https://github.com/glimpse-editor/getglimpse-web/pull/48

## Dropped support for Apple MacOS
Unfortunately at the time of writing the upstream documentation for [building on OSX](https://wiki.gimp.org/wiki/Hacking:_Building/Mac_OSX) is quite sparse and does not seem to have been updated since it was first created in April 2011. As a result we have had to do our own research to figure out how that works.

Our research sadly did not yield the right answer, despite our core contributors committing whole weeks of time to working on the problem and reading through old Github repositories, forums and community blog posts. The closest we came to a solution was finding an [upstream experiment with CircleCI](https://gitlab.gnome.org/Infrastructure/gimp-macos-build), but this seems to be a very early work-in-progress and our own attempts to get it working using more cost-effective local tools did not succeed.

After further review we determined that even if we reached out to the upstream project to find out how to build Glimpse 0.1 for MacOS, we do not have anyone with the right combination of skills, equipment, enthusiasm and free time to keep that build maintained over a sustained period of time. We concluded that focussing our efforts on the Linux and Windows ports instead best serves the most number of people with the limited resources available to us.

While we know that will come as a disappointment for many of you, we hope that [SeaShore](http://libregraphicsworld.org/blog/entry/meet-seashore-free-image-editor-for-macos) will prove to be a viable substitute we can recommend. We believe it fits the criteria of being a re-branded variant of the GNU Image Manipulation Program with a better GUI, and it also benefits from being mature, well-maintained, available for zero cost through the Apple App Store and developed specifically for use with MacOS. Give it a try, and let us know what you think!

## Other news
We are aware that an enthusiastic member of the Arch community has created an AUR package that links to the Glimpse project's development branch. If you would like to preview the latest changes and are using a compatible GNU/Linux distribution then that is an exciting new unofficial installation option.
