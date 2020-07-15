---
title: "A Month of Many Patches"
date: 2020-04-12T09:00:00+01:00
draft: false
---
Check out our [Contribute](/contribute/) page for social media and news links to follow our progress.

## Updated timelines for Glimpse Image Editor 0.1.4
We plan to release Glimpse Image Editor 0.1.4 beta before the end of April 2020. That may be delayed if it takes longer than anticipated to resolve Windows build problems, or if we are badly impacted by the current global health emergency. There will then be two weeks of testing before it is formally released.

To recap, we are bumping the versions for key underlying dependencies on the same GNU Image Manipulation Program 2.10.12 base. We have already backported "high contrast" icon packs, and have started improving the ones that are already there. We also want to use the extra time to improve translations and documentation.

We have had positive feedback about our existing Windows MSI installer only using ~500MB disk space (the upstream Windows installer uses 3.5GB). For 0.1.4 we will refine it further with a prototype GUI that displays the GNU GPLv3 and enables users to set a custom install location.

Within a few weeks of releasing Glimpse Image Editor 0.1.4, we will produce AppImages for Linux users. They will contain an in-built update mechanism, and function as "known good" builds for anyone that has trouble installing Flatpaks and Snaps.

We also want to produce a new install option for Windows 10 users through the Microsoft Store as soon as possible. We believe that will resolve issues installing and running Glimpse Image Editor on enterprise computers. Typically anti-virus programs on those machines will incorrectly flag the software as malware and/or interfere with its normal operation, but hopefully a sandboxed version of the program that has been security audited and signed by Microsoft will not have those problems.

In June 2020 we intend to start porting 0.1.4 to macOS, with the aim of releasing a beta version in time for our project's first anniversary in July 2020.

## Glimpse Image Editor featured in the Ubuntu Software Center
In other news, Glimpse Image Editor was recently displayed up in a huge banner at the top of the Ubuntu Software Center. We now also appear in the "Graphics & Photography" section too! Both of these things significantly boosted the size of our user base on Linux, and we now treat Flathub and Snapcraft as equally supported download channels for that operating system.

We would like to thank Heather Ellsworth and Ken VanDine for their amazing work on [our Snapcraft builds](https://snapcraft.io/glimpse-editor).

## Glimpse Image Editor 0.1.2 re-released with important Linux fixes
Towards the end of March 2020 we discovered that upgrading the GNOME platform version on [our Flatpak](https://www.flathub.org/apps/details/org.glimpse_editor.Glimpse) from 3.34 to 3.36 broke our application and prevented it from launching. We initially thought that problem was specific to Flathub and that reverting back to 3.34 was sufficient, but on further investigation discovered that this problem still impacted Arch and Elementary users running GNOME 3.36.

Within days Bobby Moss successfully backported a patch from upstream that fixed this showstopping bug. Cristiano Vitorino then provided his assistance with the testing of that fix over the next week, enabling Bobby to deploy the change through Flathub on 2020-04-03.

The Glimpse Project governance team would like to express their gratitude to the Arch Linux community for originally reporting this problem to us, and for quickly updating the AUR package they provide for Glimpse Image Editor with this fix.

## New Github Sponsors donation option
Don't worry, your Open Collective pledges will still continue as normal. We are just making you aware that this is another donation option that we are starting to share with the community. All the donations we receive on Github Sponsors will go directly to our existing Open Collective campaign that covers project costs, but with the added benefit that Github will match your contribution for the first year.

* Glimpse project Github Sponsors link: https://github.com/sponsors/glimpse-editor
* Glimpse project Open Collective link: https://opencollective.com/glimpse
* GNU Image Manipulation Program donation link: https://www.gimp.org/donating/

## Assistance provided to the GNU Image Manipulation Program
We are pleased to announce that on 2020-04-01 we donated $100 USD to the GNU Image Manipulation Program developers as part of our commitment to share the donations we receive with them. In total we have donated $150 USD since our project started, and we expect that amount to keep growing in coming months and years. [Source](https://opencollective.com/glimpse/expenses/categories/DONATION)

We would also like to take this opportunity to apologize to the GNU Image Manipulation Program contributors for a separate issue that they reported to us on 2020-04-04. 

It was previously stated on our FAQs page that their GUI design team had stopped meeting in 2012. While that is correct, it was unfortunately misinterpreted by some bloggers and YouTubers to mean that development on the GNU Image Manipulation Program's user interface had ceased in 2012. We [issued a clarification](https://twitter.com/glimpse_editor/status/1246837680735948802) on social media, rewrote our FAQs page, then invited upstream contributors to review our changes to that page before we published them.

We take our commitment to build a positive and constructive relationship with the GNU Image Manipulation Program contributors very seriously, and we hope our fast response to this incident demonstrates our desire to act in the best interests of the free software community and do the right things as a downstream fork.

