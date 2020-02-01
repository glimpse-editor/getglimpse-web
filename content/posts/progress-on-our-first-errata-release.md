---
title: "Progress On Our First Errata Release"
date: 2020-01-31T20:45:00+00:00
draft: false
---
Check out our [Contribute](/contribute/) page for social media and news links to follow our progress.

**Please note:** We have now moved to a different Mastodon account! Follow us at [@glimpse@mastodon.art](https://mastodon.art/@glimpse)

## Audience Figures Update
Glimpse Image Editor 0.1.0 was released on Friday 22nd November 2019. [Release Notes](/posts/glimpse-0-1-0-release-notes/)

These download figures were correct at the time of publication. There has been 6860 downloads in total from our directly supported sources (Github and Flathub):

* Our Windows release has been downloaded 4190 times (+490). [Source](http://www.somsubhra.com/github-release-stats/?username=glimpse-editor&repository=Glimpse)
* Our Linux release on Flathub has been downloaded 2670 times (+570). [Source](https://gitlab.com/ahayzen/flathub-api-stats-generator)

Heather Ellsworth reports that there are 1630 active installs from Snapcraft.

## Progress on Glimpse Image Editor 0.1.1
Bobby Moss created a huge utility pull request that resolved a number of important bugs:

* GNU Image Manipulation Program and Glimpse Image Editor currently share the same Windows task bar icon if you run them at the same time [#247](https://github.com/glimpse-editor/Glimpse/issues/247)
* Still displays "GIMP" in the splash screen title [#230](https://github.com/glimpse-editor/Glimpse/issues/230)
* "GIMP" is still used throughout the Help and About menus in the German translation [#238](https://github.com/glimpse-editor/Glimpse/issues/238)
* "GIMP" still being incorrectly used throughout parts of the application in non-English translations [#240](https://github.com/glimpse-editor/Glimpse/issues/240)

The pull request also updated the application version, updated the list of Glimpse contributors, and updated the documentation. You can review all the changes here: https://github.com/glimpse-editor/Glimpse/pull/263

The remaining bugs that still need to be resolved are listed here:

* "GIMP" and Wilber mascot still used in the color picker [#250](https://github.com/glimpse-editor/Glimpse/issues/250)
* Restore the "Color" icon theme [#232](https://github.com/glimpse-editor/Glimpse/issues/232)
* Fix Python Support on Windows [#178](https://github.com/glimpse-editor/Glimpse/issues/178)
* Rename the "Gimpressionist" plug-in [#267](https://github.com/glimpse-editor/Glimpse/issues/267)

We have revised our expected release timeline to "some time in February 2020". [Bobby's wiki page](https://wiki.glimpse-editor.org/index.php?title=User:TrechNex) has been updated accordingly.

Shortly before this post was published we also received an excellent contribution from Ken VanDine that fixed the legacy user interface theme for Linux users who installed Glimpse Image Editor through Snapcraft. That fix will be included in this release: https://github.com/glimpse-editor/Glimpse/pull/271

## Updated Plans for Glimpse Image Editor 0.2.0
After a number of people (including chaomodus) suggested it, we are now determining how to include [the G'MIC toolkit](https://gmic.eu/) with Glimpse Image Editor by default. We [confirmed with the project](https://twitter.com/gmic_ip/status/1217899762554408960) that the license was compatible, and in future releases we will integrate the plug-ins functions more tightly within the user interface. You can follow the Github issue's progress here: https://github.com/glimpse-editor/Glimpse/issues/262

Kretz also suggested that we include the "GIMP Resynthesizer" plug-in: https://github.com/glimpse-editor/Glimpse/issues/270

Let us know if you have more ideas for plug-ins we should consider bundling with Glimpse Image Editor. You can also see a preview of potential issues we might cover on our milestones page: https://github.com/glimpse-editor/Glimpse/milestones

## Chaomodus joins the Glimpse project governance team
You may have seen chaomodus mentioned in previous blog posts because of their excellent work running [our development wiki](https://wiki.glimpse-editor.org). They have helped out with the project from the very beginning, and assisted Luna (Clipsey) numerous times with our parallel user interface rewriting efforts.

Chaomodus has also taken on the task of revamping our build tooling and infrastructure, and recently started trialling a Gitea server as an optional alternative for people who have moral objections to using Github.

We hope you will give them a warm welcome as our newest member of the governance team. You can see more details about how the Glimpse project governs itself on [our FAQs page](/about/#how-does-this-project-govern-itself).

It has also not escaped our notice that this continues our trend of diverse representation in leadership positions for our project! The lesson other free software projects can take from us is that if you treat joining your public communication channels as a privilege instead of a right, pro-actively police your project's code of conduct and value creating a pleasant culture over nursing peoples' egos, then this can in fact emerge organically.

## Enjoy yourselves at FOSDEM!
We would just like to confirm that we do not have any official representation this year, and none of our governance team are in attendance. We are unlikely to be present at any conferences this year because it is still quite early in our project's lifespan and we do not have the resources to send people!

However, we know many of you are attending this weekend. Bobby Moss (who once lived in Belgium for a year and attended FOSDEM himself in 2012 and 2015) particularly recommends [Hoegaarden](https://hoegaarden.com/) and [Leffe Blond](https://leffe.com/en/leffe-blond) as good beer choices!