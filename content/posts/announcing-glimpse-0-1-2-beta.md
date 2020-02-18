---
title: "Announcing Glimpse 0.1.2 Beta"
date: 2020-02-18T17:30:00+00:00
draft: false
---
Check out our [Contribute](/contribute/) page for social media and news links to follow our progress.

## Wait... what happened to 0.1.1?
Don't panic! We inherited a build versioning scheme that seems to work well, so we now define odd number versions (eg. 0.1.1 and 0.1.99) as "in development" and even-number versions (eg. 0.1.0 and 0.1.2) as stable releases we take the time to beta test.

If you want to find out more about how our release numbering works on [our FAQs page](/about/#how-does-your-release-numbering-work).

## Beta testing for the next release begins
On Monday evening Bobby Moss (trechnex) successfully packaged the beta builds for Glimpse Image Editor 0.1.2 and published them on Flathub (Linux) and our own build server (Windows). We would like to also thank Mathieu Bridon for his assistance setting up our project's beta channel on Flathub.

We have already started two weeks of beta testing and bug fixing. Our target release date for 0.1.2 is Monday 2nd March 2020, but that is subject to change based on the severity of the bugs we uncover.

For those who would like to help us with beta testing, here is a summary of the user-facing changes we have made:

Features and fixes ready for testing: 

* "Color" icon theme added
* "Gray" UI theme added
* Recent upstream contributors credited in Help > About > Credits
* "Gimpressionist..." renamed to "Impressionist..." in Filters > Artistic
* Windows users can now select other languages in Edit > Preferences > Interface
* GNU Image Manipulation Program and Glimpse Image Editor no longer share the same Windows taskbar icon when they run at the same time

Features and fixes still being worked on:

* Python-fu support on Windows [#178](https://github.com/glimpse-editor/Glimpse/issues/178)
* Upstream translator credits need fixing [#300](https://github.com/glimpse-editor/Glimpse/issues/300)
* Improved Windows installer [#284](https://github.com/glimpse-editor/Glimpse/issues/284)
* Miscellaneous bugs in [0.1.2 milestone](https://github.com/glimpse-editor/Glimpse/milestone/9)

We strongly recommend that you do not attempt to try out these beta testing changes on a production machine you urgently rely on.

Full instructions for participating in the beta are available on our development wiki: https://wiki.glimpse-editor.org/index.php?title=Testing_Glimpse

## Successful website migration
Two weeks ago Chaomodus migrated our static hugo site and the development wiki to new servers, and so far we have had no outages.

We previously ran everything from one server that Bobby Moss had provisioned in haste last August, so breaking out our systems into several more robust servers is something that promises to help us automate builds and improve uptime for our services.

Within the next few months we intend to fully decommission the old server and run automated packaging and builds for Linux, Windows and (eventually) macOS on a separate Jenkins slave running Docker containers. Once that work is complete we will be able to spend more time improving Glimpse Image Editor and less on manually building and packaging things.

Bobby Moss has already set up a new branching strategy to cover that, and added that information to [our development wiki](https://wiki.glimpse-editor.org/index.php?title=Building_Glimpse).

## Updates to our FAQs page
Governance team reviewed and updated a number of questions on our FAQs page, which we felt was important as our project has evolved a lot since some of these answers were written.

Bobby Moss also wrote new answers explaining [how to find out if we're implementing a feature](/about/#when-are-you-going-to-implement-the-feature-i-asked-for) and an explanation of [how our version numbers works](/about/#how-does-your-release-numbering-work).

If you have additional questions, please contact us by using the links on our [Contribute](/contribute/) page.

## We applied to join the Github Sponsors waiting list
After one of our supporters notified us that [Github Sponsors now supports Open Collective](https://blog.opencollective.com/double-the-love/) we opened up a discussion about it on our public Matrix channel.

The reason this development piqued our interest is that all donations submitted via Github Sponsors would go directly to [our Open Collective profile](https://opencollective.com/glimpse) without requiring our intervention. 

Github also charges no fees for this service, and they have committed to matching any donations we receive in our first year, up to a limit of $5000 USD. This move would also address the feedback we have received that we should support a secondary donation mechanism for those who do not wish to use PayPal.

The response on Matrix was broadly positive, so we have applied to join the waiting list for this platform. Assuming we are accepted, we will briefly re-open the issue so that people can let us know how they feel about this decision before we proceed with it.

As a reminder, money donated to our Open Collective is only used to cover the costs of this project and periodically pass some of those contributions upstream. You can see a full accounting of all the donations we have ever received and how we have spent that money so far on [our Open Collective profile](https://opencollective.com/glimpse).

If you would like to thank our contributors directly for the many hours of unpaid volunteer work they do for our project, you should contact them about their own personal donation platforms:

Creator: [Bobby Moss](https://github.com/TrechNex)
Maintainers: [Chaomodus](https://github.com/chaomodus), [Christopher Davis](https://github.com/BrainBlasted), [Luna](https://github.com/Member1221)
Flatpak: [Mathieu Bridon](https://github.com/bochecha)
Snapcraft: [Heather Ellsworth](https://github.com/hellsworth)
