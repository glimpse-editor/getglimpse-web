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

## Updated Plans for Glimpse Image Editor 0.2.0
After a number of people (including chaomodus) suggested it, we are now determining how to include [the G'MIC toolkit](https://gmic.eu/) with Glimpse Image Editor by default. We [confirmed with the project](https://twitter.com/gmic_ip/status/1217899762554408960) that the license was compatible, and in future releases we will integrate the plug-ins functions more tightly within the user interface. You can follow the Github issue's progress here: https://github.com/glimpse-editor/Glimpse/issues/262

Kretz also suggested that we include the "GIMP Resynthesizer" plug-in: https://github.com/glimpse-editor/Glimpse/issues/270

Let us know if you have more ideas for plug-ins we should consider bundling with Glimpse Image Editor. You can also see a preview of potential issues we might cover on our milestones page: https://github.com/glimpse-editor/Glimpse/milestones

## Chaomodus joins the Glimpse project governance team
