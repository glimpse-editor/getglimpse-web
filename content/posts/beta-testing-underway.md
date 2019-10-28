---
title: "Beta Testing Underway"
date: 2019-10-28T02:00:00+01:00
draft: false
---
Instead of providing a weekly reminder of our social media and project links across the web, check out our all-new [Contribute](/contribute/) page!

**DO NOT PUBLISH YET**

## Another release schedule update
Unfortunately we are going to miss our target of releasing in October 2019. We made that estimate before beta testing had started and also when our packaging efforts were still in their very early stages, so this was not unexpected.

We know that will be disappointing to hear for many of you reading this, but as with any new free software project setbacks and "blockers" like this are to be expected. We apologize, but also take solace in the fact that this project has only existed since Friday 5th July 2019. The amount we have achieved in less than four months has been quite remarkable!

The Glimpse project would like to thank the community for your continued support and patience with us. We will provide an update some time in the middle of November 2019 to confirm if we will be formally releasing before the end of that month or in the first half of December 2019.

## Snap support stalled
Unfortunately (at the time when this blog post was published) there had been no updates made to the related pull request for two weeks: https://github.com/glimpse-editor/Glimpse/pull/153

If you think you can pick this work up and finish it then please get in touch with us! If we cannot complete this task then we will need to bring forward plans to also package Glimpse 0.1 as an [AppImage](https://appimage.org/) so that Linux users will still have an alternative for systems that do not support Flatpak.

## Continued work on the Windows port
Bobby Moss has been working through problems related to packaging Glimpse 0.1 for Windows systems.

Creating a new Windows installer from scratch has proved difficult because of the sheer number of dependency files involved, but we are confident the end result will be worth it. Bobby has succeeded in producing a 32-bit MSI file that should work on all Windows systems from Windows 7 or later. You can find new instructions for this here: https://wiki.glimpse-editor.org/index.php?title=Testing_Glimpse

A roadblock we have run into is that (much like the ZIP files produced at the start of beta testing) this new installer triggers warnings and blocks from Windows User Account Control, Windows SmartScreen and any other locally installed anti-virus program.

While the development releases will always have this problem (even if we use a self-signed certificate), that is clearly not acceptable for formal releases. We will need to buy a three year code signing certificate [from a reputable CA](https://comodosslstore.com/codesigning.aspx) to fix that problem.

Our efforts to automate the building and packaging of the Windows port on [our Jenkins server](https://jenkins.glimpse-editor.org/) have stalled. We are still puzzling out the documented cross-compilation steps from upstream and how to script the packaging process with [the WiX Toolset](https://wixtoolset.org/). However that will not be done in time for the 0.1 release, so currently the Windows build and packaging process relies entirely on one person (Bobby Moss) doing it all manually, and that is not a small task!

In more positive news, we have confirmed that GNU Image Manipulation Program 2.10.12 and Glimpse 0.1 BETA can both be installed alongside each other on the same Windows system without sharing or overwriting each others' configuration files. You cannot currently launch one while the other is still running, but we are working on a fix for that.

Here is a full list of Windows bugs and "known issues" we are currently aware of:

* BETA builds trigger security warnings from Windows and anti-virus programs [195](https://github.com/glimpse-editor/Glimpse/issues/195)
* Glimpse 0.1 BETA is currently built without Python support due to this being missing in upstream documentation, so a noticeable number of plug-ins are not loaded by the application when it is started [178](https://github.com/glimpse-editor/Glimpse/issues/178)
* The Wilber icon is still shown in the taskbar and window title when a file is open and being modified [176](https://github.com/glimpse-editor/Glimpse/issues/176)
* The Wilber icon and upstream application name is still shown in error messages and recovery dialogs [190](https://github.com/glimpse-editor/Glimpse/issues/190)
* Offline help files are not included with this release [145](https://github.com/glimpse-editor/Glimpse/issues/145)
* Glimpse 0.1 BETA and GNU Image Manipulation Program 2.10.12 can be installed alongside each other but cannot run at the same time. [196](https://github.com/glimpse-editor/Glimpse/issues/196)

## Flatpak improvements
Mathieu Bridon has continued to improve the Glimpse 0.1 BETA flatpak with new core dependency versions and updates to the metadata.

**TO BE POPULATED**

## Documentation updates
Bobby Moss has been improving the code level documentation. Their pull request is not quite ready to merge yet, but you can follow it here: https://github.com/glimpse-editor/Glimpse/pull/188

Glimpse project also confirmed that the Glimpse logo and assets are provided under a Creative Commons ([CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/)) license. Clarifications have also been made to the `LICENSE` file in the root of the source code in `dev-g210` branch: https://github.com/glimpse-editor/Glimpse/pull/187

## Website updates
Christopher Davis has been experimenting with new themes, website designs and accessibility changes. You can follow their progress here: https://github.com/glimpse-editor/getglimpse-web/pull/54

The draft release notes and downloads page that Bobby Moss has been working can still be followed here: https://github.com/glimpse-editor/getglimpse-web/pull/48

## Patreon campaign to be closed in December 2019
We would like to thank everyone who has contributed cash to the project on our [Patreon](https://www.patreon.com/glimpse) page since its inception in July 2019.

As we mentioned in previous posts we have created a new fundraising campaign on [Open Collective](https://opencollective.com/glimpse). This is great for you as followers of our project because you can choose between a one-off or monthly donation, see how much we receive and what we spend your money on, and (if you live in the US) benefit from tax deductions. From the project's point of view the charity behind the platform provides us with legal/financial services and ensures our expense claims are legitimate. Open Collective also enables more than one person to run the fundraising campaign and track backer rewards.

We know the project will probably take a financial hit when we do this, but we feel this is the right long term decision because it will reduce the administrative overhead our core contributors have to deal with and better ensure accountability within our project's governance structure.

If there is positive feedback for the idea, we may also encourage individual contributors to host their own Patreon campaigns and PayPal links so they can still receive contributions from those of you who prefer those platforms.

## Release numbering change
On a related note, the project has also changed its future development plans based on what we have collectively learned over the last few months. We originally intended that 0.x would be based on GNU Image Manipulation Program 2.10.x, 1.x would be based on GNU Image Manipulation Program 3.x, and 2.x would be our own rewrite.

We have made the decision to not re-fork the GNU Image Manipulation Program when it reaches version 3.x. Realistically, we do not have the people and resources needed to recreate all the changes and tooling we have produced over the last four months again to make that major update (and its entirely new build processes) a worthwhile end product.

Instead we believe it makes more sense to stick to the 2.10.x base, and make that as stable and "long term supportable" as possible while also adding our own changes to it. 1.0 should be released towards the second half of 2020, assuming the 0.x releases that are produced before then are stable and well-received.

The "UI rewrite" running in parallel will continue unhindered, and we hope to see some initial alpha-level prototypes some time in 2020.

## Reaching out to Facebook users
You will now find the Glimpse project [on Facebook](https://fb.me/glimpse.editor). Bobby Moss is currently maintaining that page, and this is another part of our outreach efforts to users outside the free software community. It should also assist with our efforts to improve the project's search engine optimization (SEO).

Despite this [our Mastodon account](https://bobadon.co.uk/@glimpse) will continue to be our primary social media channel. The Glimpse project spawned from the fediverse, so it will always be our preference.

## Early work on the UI rewrite
There seems to be early support around the idea of using the D programming language with a recent version of GTK to produce this UI rewrite. You can see some of the early design work from people like meltheadorable on our wiki: https://wiki.glimpse-editor.org/index.php?title=Main_Page

Luna (Clipsey) has been experimenting with GTK bindings for D in her own Github project space. She has been regularly posting screenshots of that work in the (invite-only) "Glimpse 2.x UI Rewrite" Matrix channel, and you can check that code out for yourself here: https://github.com/Member1221/d-dazzle and here: https://github.com/Member1221/d-handy.

Chaomodus has also been preparing to contribute to this parallel effort by teaching themselves the D programming language in their spare time, and rewriting simple UNIX utilities as a learning exercise.
