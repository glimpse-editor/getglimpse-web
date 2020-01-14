---
title: "Kicking Off a New Year"
date: 2020-01-14T21:14:00+00:00
draft: false
---
Check out our [Contribute](/contribute/) page for social media and news links to follow our progress.

## Download Figures Update
Glimpse Image Editor 0.1.0 was released on Friday 22nd November 2019. The feedback we have had from end users has been mostly positive, and we are actively working on the translation bugs that have been reported to us. [Release Notes](/glimpse-0-1-0-release-notes/)

These download figures were correct at the time of publication. We estimated there has been around 7600 downloads so far.

* Our Windows release has been downloaded 3700 times. [Source](http://www.somsubhra.com/github-release-stats/?username=glimpse-editor&repository=Glimpse)
* Our Linux release on Flathub has been downloaded 2100 times. [Source](https://gitlab.com/ahayzen/flathub-api-stats-generator)

Heather Ellsworth also reports that our Linux release has also been downloaded 1800 times on Snapcraft.

Given this was our very first binary release and most of the coverage our project has received on community blog posts and in YouTube videos has been generally negative, we feel that these figures are as good as we could have hoped for.

## Updates From the Festive Break
We were definitely not idle throughout December 2019! A major discussion currently ongoing is how we will scale our server infrastructure in a "long term sustainable" way. This year we plan to create automated reproducible builds and packaging for Windows, macOS, Linux Flatpak and Linux AppImage. We will need to provision a build server capable of achieving that, and a separate web server to host our website and published development builds.

Discussions have also been re-opened about possibly moving our source code and issue tracking from Github to a more ethical alternative. Chaomodus and meltheadorable are currently working on a proof of concept self-hosted [Gitea](https://gitea.io/en-us/) server, and if that proves to be a viable alternative that our community supports we could switch to it. If we do choose to make the switch, we would likely continue mirroring code to Github and using the service as a download mirror.

Bobby Moss has been tracking some of the GNU Image Manipulation Program's project IRC channels and mailing lists to help us keep track of upstream bugs and changes that might impact our project. He has also laid out a [roadmap of changes](https://wiki.glimpse-editor.org/index.php?title=User:TrechNex) that he intends to contribute to the project.

Luna (Clipsey) has continued to work on the user interface rewrite with the help of other project contributors. She is currently experimenting with cross-platform development frameworks and assessing the viability of our project developing its own user interface toolkit. Our choice of programming language is still an open discussion, and design work for a potential new user interface has started in earnest.

Finally we collectively started a discussion about creating an "unstable" branch as a technical exercise. This would copy the latest changes from our own development branch, but then apply them to the upstream `master` branches for GNU Image Manipulation Program, GEGL, BABL and MyPaint. It would not be the version of the code we ever use for stable releases (which always rely on upstream tags) or recommend that anyone use it for productive work, but contributors may find it useful to understand which features we need make fixes for. We will keep you updated on how that discussion progresses.

## Bug-fix Release Planned
We are hoping to release Glimpse Image Editor 0.1.1 either towards of the end of January 2020 or in the first half of February 2020 depending on how we progress.

Anticipated features include:

* Restoring the "Color" icon theme to assist users with high DPI displays
* Fixing translations for the rebrand that still need changes to be applied
* Restoring Python support for the Windows version of Glimpse Image Editor

It will continue to be based on the GNU Image Manipulation Program 2.10.12 so that we can apply and release these changes as quickly as possible for our new user base. There may also be other features that are bundled as part of the update, and we will do our best to keep you up-to-date as our plans evolve.

## Rebase to 2.10.14 Planned
Once 0.1.1 has been released we intend to rebase Glimpse Image Editor on GNU Image Manipulation Program 2.10.14 and release the result as version 0.2.0.

This will also be the release where we credit upstream contributions through the graphical user interface. We think this is the best release to add that change in because we will benefit from upstream improvements that also add contributions from translators. To comply with the GNU GPLv3 we include the names of the original authors with the source code, but we want to ensure that they are also credited through the user interface before publishing Glimpse Image Editor to any new download channels.

We anticipate that Glimpse Image Editor 0.2.0 will be released in early March 2020. Shortly after we will focus on porting the code base to macOS based on the new information we have been provided by the GNU Image Manipulation Program contributors.

Just like our previous releases, these plans are subject to change and may also include contributions that have not been mentioned in this article.

## Thank you
We would like to take this opportunity to thank everyone that stuck with us through the four months our project was vaporware, and particularly those of you who continue to donate your time, money and ideas to our project today. It means a lot to all of us that work on Glimpse Image Editor, and we are doing our best to push this project to the next level and keep developing it.

Our aim is still to try out new ideas and bring new people into the world of free software. It's still very possible that we could fail miserably, and there are many people in the free software community that we will probably never win over, but we are committed to deliver on our promises as best we can and hope we can continue make our community proud to support us.