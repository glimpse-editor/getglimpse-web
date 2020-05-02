---
title: "Anniversary Plans"
date: 2020-05-02T11:00:00+01:00
draft: false
---
Check out our [Contribute](/contribute/) page for social media and news links to follow our progress.

## Revamped release schedule
We no longer intend to produce an interim Glimpse Image Editor 0.1.4 release, although much of the work for it has been done.

The original intention behind 0.1.4 was to provide fixes for a show-stopping crash on some Linux distributions quickly, while also including changes Windows users would find useful. However, as re-releasing 0.1.2 on Linux solved the problem that is no longer necessary.

Glimpse Image Editor 0.2.0 will be based on the GNU Image Manipulation Program 2.10.18 and use newer versions of BABL, GEGL and MyPaint. We expect to release it in July 2020, which will mean that our third release coincides with this project's first anniversary celebrations.

In addition to uplifting the base versions, Glimpse Image Editor 0.2.0 will include changes to icon packs, more features in our Windows installer, Python plug-in support on Windows, a Linux AppImage, and an optional Linux AppImage download that contains extra third party plug-ins. You can track our progress in the [0.2.0 milestone](https://github.com/glimpse-editor/Glimpse/milestone/12) on Github.

We have also moved a number of feature suggestions into a [0.2.x candidate](https://github.com/glimpse-editor/Glimpse/milestone/5) milestone on Github, and some of these features will be picked up either as part of the 0.2.0 release or a future 0.2.2 release scheduled for "early 2021".

## Planning for the longer term
We have been reviewing how our project has been progressing every few months, but now we are approaching the end of our first year we are starting to think about how we can support our application in the long term.

To that end, we have ended our plans to run our own self-hosted Jenkins and Gitea servers because of the required monetary and time cost of doing so. Instead we will make use of [Github Actions](https://github.com/features/actions) to automate the building and packaging of our applications. It is a zero-cost solution that is future-proofed and easily portable to other platforms such as Gitlab CI.

Similarly we intend to move our wiki to our Github repository instead of running MediaWiki on its own server, and we are also evaluating potential free hosts for our website.

We believe that 0.2.0 will include all the initial functionality we promised, so our main costs from now on would be related to collaboration tools. Because we now know roughly how many contributors we need to provide services for and how large our user base is likely to be, we have determined that these services should be sufficient for our project's needs.

Currently Bobby Moss is the solo developer of the forked code, with up to a dozen other people providing assistance with packaging, design, testing, moderation and governance.

Luna also runs a separate team composed of herself, Chaomodus and several designers that are working on a complete UI rewrite.

We estimate that Glimpse Image Editor has a user base of <=10000 users across Windows and GNU/Linux ecosystems.

## The future of our fork
[Bobby Moss](http://trechnex.freeshell.org/) has indicated that the 0.2.x releases based on the GNU Image Manipulation Program 2.10.18 are the last ones he intends to develop. He will continue to help us maintain the 0.2.x releases until at least July 2021.

We would like to thank him for lending us his experience, thousands of unpaid volunteer hours, and the $100 USD donation that helped us get this project started. We would particularly like to thank him for being our contact with the GNU Image Manipulation Program developers, and for the time he spent [trying to port](https://github.com/glimpse-editor/Glimpse/issues/227#issuecomment-620214794) Glimpse Image Editor to MacOS.

### Over to you
Within the next year or two, the GNU Image Manipulation Program developers will release version 3.0 of their application. That will use the meson build system, migrate to GTK3 and Python 3, support plug-ins written in Lua and JavaScript, and include sought-after features like CMYK colorspace support and non-destructive editing.

We are looking for volunteers that would be willing to help us create an exciting new fork based on the upstream master branch so we are ready when 3.0 is stable. If you would like to get involved, check out our [contribute page](/contribute/).

## Download figures update
All figures were correct on the day this blog post was published and sources have been provided so that you can verify our claims. If the figures are accurate then we would consider this to be a good start for our project, and can confirm that the number of downloads has increased since 2020-03-17. [Source](/posts/changing-plans/)

We know that Glimpse Image Editor has been downloaded at least NNNNN (+NNNN) times across all platforms and download sources since it was first released on 2019-11-22. A detailed breakdown is provided below.

### Linux
Glimpse Image Editor has been downloaded NNNN (+NNNN) times from Flathub since it was first released. [Source](https://gitlab.com/ahayzen/flathub-api-stats-generator)

Heather Ellsworth reports that there are NNNN (+NNNN) active users that have installed Glimpse Image Editor through Snapcraft. [Source](/glimpse-snap-2020-03-14.png)

The distribution tarballs we provided on Github for Glimpse Image Editor 0.1.2 have been downloaded NN times, suggesting that there is some early interest from Linux distro maintainers about hosting our software natively in their repositories. [Source](https://somsubhra.com/github-release-stats/?username=glimpse-editor&repository=Glimpse)

We do not have the figures for other community-supported Linux download sources.

### Windows
The new Glimpse Image Editor 0.1.2 installer has been downloaded NNNN times from Github since its release on 2020-03-02. [Source](https://somsubhra.com/github-release-stats/?username=glimpse-editor&repository=Glimpse)

To date there have been NNNN (+NNN) direct downloads of Glimpse Image Editor 0.1.0 for Windows from Github. [Source](https://somsubhra.com/github-release-stats/?username=glimpse-editor&repository=Glimpse)

There are two new unofficial third-party download sources for Windows users that provide download statistics:

* NN downloads from [Softpedia](https://www.softpedia.com/dyn-search.php?search_term=glimpse)
* NN downloads from [SourceForge](https://sourceforge.net/projects/glimpse-image-editor/)
