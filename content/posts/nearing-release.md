---
title: "Nearing Release"
date: 2019-11-15T18:00:00+00:00
draft: false
---
Instead of providing a weekly reminder of our social media and project links across the web, check out our all-new [Contribute](/contribute/) page!

## Release tentatively scheduled for Friday 22nd November 2019
As the subtitle suggests we are "penciling in" a release date before the Thanksgiving holiday season in the United States. That is intended to assist our American contributors and ensure the release is not delayed because of winter festivities held around the world.

We are aiming for a "code freeze" on Monday 18th November 2019, and the timeline after that will depend on how quickly we can complete our documentation and how long it takes to submit Glimpse Image Editor to Flathub and the Windows Store.

We would like to thank everyone who has donated and contributed to the Glimpse project so far, and encourage our supporters to help us now with a final push to make Glimpse available to the wider public.

## Snap community support solved
We are pleased to say that there will be a Snapcraft version of Glimpse 0.1 at launch! Thanks to the excellent efforts of Heather Ellsworth and psymole we now have changes merged into the codebase and [a Wiki page](https://wiki.glimpse-editor.org/index.php?title=Building_Glimpse/Linux#Package_as_a_Snap) explaining how to package our application as a Snap.

## Continued work on the Windows port
Bobby Moss has been working through problems related to packaging Glimpse 0.1 for Windows systems.

Unfortunately when Glimpse 0.1 launches it will not support Python plug-ins on Windows. This is due to a missing part of the upstream build instructions and we have been unable to find a workaround. JavaScript and Lua plug-ins are not affected.

Unfortunately we were unable to acquire a CA validated code signing certificate for our Windows installers, meaning it will be blocked by Windows SmartScreen and your locally installed anti-virus program if you attempt to install it. This means that the 32-bit and 64-bit MSI installer files will only be released as a backup method for installing the application.

Our intended workaround is to submit Glimpse Image Editor to [the Windows Store](https://en.wikipedia.org/wiki/Microsoft_Store_(digital)) and promote that as our primary supported method for downloading and installing our application on Windows. It will still be available for zero cost but it will fix the security warnings.

## Flatpak improvements
Mathieu Bridon has continued to improve the Glimpse 0.1 BETA flatpak with new core dependency versions and updates to the metadata.

You can beta test the current flatpak release by following the instructions here: https://wiki.glimpse-editor.org/index.php?title=Testing_Glimpse

## Documentation updates
Bobby Moss has been drastically improving the code level documentation and Github integrations. Their pull request is not quite ready to merge yet, but you can follow it here: https://github.com/glimpse-editor/Glimpse/pull/214

## Website updates
Christopher Davis has been experimenting with new themes, website designs and accessibility changes. You can follow their progress here: https://github.com/glimpse-editor/getglimpse-web/pull/54

The draft release notes and downloads page that Bobby Moss has been working can still be followed here: https://github.com/glimpse-editor/getglimpse-web/pull/48

## Bug fixes
Bobby Moss has fixed a number of issues raised during beta testing such as "GIMP" still being used in recovery messages and the wrong logo being shown in the taskbar and window title.

With assistance from Clipsey and Mathieu Bridon a fix has also been applied so Glimpse Image Editor can run at the same time as GNU Image Manipulation Program on a Windows machine.

## The "Glimpse" naming discussion is finally over!
We have now [closed the issue](https://github.com/glimpse-editor/Glimpse/issues?page=2&q=is%3Aissue+is%3Aclosed) where people were robustly discussing if we should stick with "Glimpse" as a project name or not.

That controversy originally started after [a well-known YouTuber](https://www.youtube.com/watch?v=CV1HZU4KFHc) expressed negative opinions about our project's name, and we spent *two entire weeks* in August being aggressively lobbied around the clock on our communication channels by people repeating that YouTuber's views to us verbatim and subsequently getting frustrated if we pointed out any flaws or practical issues with the points they were raising.

As discussed on the Github issue we now treat "Glimpse" as a shortened version of "Glimpse Image Editor" and have changed our domain to glimpse-editor.org (with a matching .com) to address the legitimate concerns that were raised.

Over the past few months we have reviewed workable alternative suggestions we received on our Matrix channel, and we assisted the original poster with hosting a spreadsheet to assess support for a name change and any proposed alternatives. It was ultimately determined that there was very little internal support in favor of changing the name within the project, and no compelling alternative was ever produced. We also heard the feedback from our social media followers telling us that we need to draw a line under this discussion so we can focus more of our efforts on producing an excellent fork of the GNU Image Manipulation Program.

We would like to thank everyone for their patience as this discussion slowly made its way through our project's system of governance. It received more attention and scrutiny than any other issue we have so far discussed, and we hope that is some consolation to anyone that is disappointed with the outcome.

## REMINDER: Patreon campaign to be closed in December 2019
We would like to thank everyone who has contributed cash to the project on our [Patreon](https://www.patreon.com/glimpse) page since its inception in July 2019.

As we mentioned in previous posts we have created a new fundraising campaign on [Open Collective](https://opencollective.com/glimpse). This is great for you as followers of our project because you can choose between a one-off or monthly donation, see how much we receive and what we spend your money on, and (if you live in the US) benefit from tax deductions. From the project's point of view the charity behind the platform provides us with legal/financial services and ensures our expense claims are legitimate. Open Collective also enables more than one person to run the fundraising campaign and track backer rewards.

We know the project will probably take a financial hit when we do this, but we feel this is the right long term decision because it will reduce the administrative overhead our core contributors have to deal with and better ensure accountability within our project's governance structure.
