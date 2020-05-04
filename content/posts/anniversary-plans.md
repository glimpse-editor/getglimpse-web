---
title: "Anniversary Plans"
date: 2020-05-04T19:00:00+01:00
draft: false
---
Check out our [Contribute](/contribute/) page for social media and news links to follow our progress.

## Revamped release schedule
We no longer intend to produce an interim Glimpse Image Editor 0.1.4 release, although much of the work for it has been done.

The original intention behind 0.1.4 was to provide fixes for a show-stopping crash on some Linux distributions quickly, while also including changes Windows users would find useful. However, as re-releasing 0.1.2 on Linux solved the problem that is no longer necessary.

Glimpse Image Editor 0.2.0 will be based on the GNU Image Manipulation Program 2.10.18 and use newer versions of BABL, GEGL and MyPaint. We expect to release it in July 2020, which will mean that our third release coincides with this project's first anniversary celebrations.

In addition to uplifting the base versions, Glimpse Image Editor 0.2.0 will include changes to icon packs, more features in our Windows installer, a Linux AppImage, and an optional Linux AppImage download that contains extra third party plug-ins. You can track our progress in the [0.2.0 milestone](https://github.com/glimpse-editor/Glimpse/milestone/12) on Github.

We have also moved a number of feature suggestions into a [0.2.x candidate](https://github.com/glimpse-editor/Glimpse/milestone/5) milestone on Github, and some of these features will be picked up either as part of Glimpse Image Editor 0.2.0 or a future maintenance release.

## Planning for the longer term
We have been reviewing how our project has been progressing every few months, but now we are approaching the end of our first year we are starting to think about how we can support our application in the long term.

To that end, we have ended our plans to run our own self-hosted Jenkins and Gitea servers because of the required monetary and time cost of doing so. Instead we will make use of [Github Actions](https://github.com/features/actions) to automate the building and packaging of our applications. It is a zero-cost solution that is future-proofed and easily portable to other platforms such as Gitlab CI.

Similarly we intend to move our wiki to our Github repository instead of running MediaWiki on its own server, and due to [an outage we experienced](https://github.com/glimpse-editor/Glimpse/issues/395) earlier today we have already migrated our website to Github Pages.

We believe that 0.2.0 will include all the initial functionality we promised, so our main costs from now on would be related to collaboration tools. Because we now know roughly how many contributors we need to provide services for and how large our user base is likely to be, we have determined that these services should be sufficient for our project's needs.

Currently Bobby Moss is the solo developer of the forked code, with up to a dozen other people providing assistance with packaging, design, testing, moderation and governance. You can use the links on the [Contribute](/contribute/) page to follow their progress.

Luna also runs a separate team composed of herself and several designers that are working on a complete UI rewrite. We will provide more details about this in future blog posts, but in the meantime you can follow their progress [on Discord](https://discord.gg/hZhRceq).

## How does this impact donations?
We will continue to accept donations on [Open Collective](https://opencollective.com/glimpse) and [Github Sponsors](https://github.com/sponsors/glimpse-editor), just as we do now.

Because we are a not-for-profit project and the costs for maintaining the forked code will effectively become $0 USD, we intend to uphold our previous pledge to pass all remaining money after costs to the GNU Image Manipulation Program. This will happen towards the end of July 2020, when we have completed our infrastructure migration, released Glimpse Image Editor 0.2.0 and received our first disbursement from Github Sponsors.

From July 2020, all new donations we receive from our backers will be specifically earmarked for producing a new image editing application with a completely different user interface that is **not** based on the GNU Image Manipulation Program.

We will clearly communicate that change to our backers so we continue to ensure they make informed choices about how they can best support our project.

## The future of our fork
[Bobby Moss](http://trechnex.freeshell.org/) has indicated that 0.2.0 (based on the GNU Image Manipulation Program 2.10.18) is the last feature release he intends to develop for the "fork" stream. He will continue to produce 0.2.x maintenance releases periodically to ensure the program is stable and continues to work until the UI rewrite is ready.

We would like to thank him for lending us his experience, thousands of unpaid volunteer hours, and the $100 USD donation that helped us get this project started. We would particularly like to thank him for being our contact with the GNU Image Manipulation Program developers, and for the time he spent [trying to port](https://github.com/glimpse-editor/Glimpse/issues/227#issuecomment-620214794) Glimpse Image Editor to MacOS.

Glimpse Image Editor 0.2.0 will complete the rebranding effort, finish improving the installation experience on Windows, and include a number of minor features and UI fixes that users have requested.

## Download figures update
All figures were correct on the day this blog post was published and sources have been provided so that you can verify our claims. If the figures are accurate then we would consider this to mean that Glimpse Image Editor 0.1.2 has been positively-received by users. We can confirm that the number of downloads has increased since 2020-03-17. [Source](/posts/changing-plans/)

We know that Glimpse Image Editor has been downloaded at least 45608 (+33064) times across all platforms, versions and download sources since it was first released on 2019-11-22. A detailed breakdown is provided below.

### Linux
Heather Ellsworth reports that there have been 16901 (+15278) active users over the last month that have installed Glimpse Image Editor through Snapcraft. This outlier is likely due to us being a featured application on the Ubuntu Software Center for a a short period in April 2020. [Source](/glimpse-snap-2020-05-04.png)

Glimpse Image Editor has been downloaded 13225 (+7951) times from Flathub across all versions since it was first released on 2019-11-22. [Source](https://gitlab.com/ahayzen/flathub-api-stats-generator)

The distribution tarballs we provided on Github for Glimpse Image Editor 0.1.2 have been downloaded 356 (+303) times. [Source](https://somsubhra.com/github-release-stats/?username=glimpse-editor&repository=Glimpse)

We do not have the figures for other community-supported Linux download sources.

### Windows
Glimpse Image Editor 0.1.2 has been downloaded 9920 (+4650) times from Github since its release on 2020-03-02. [Source](https://somsubhra.com/github-release-stats/?username=glimpse-editor&repository=Glimpse)

To date there have been 5021 (+70) direct downloads of Glimpse Image Editor 0.1.0 for Windows from Github since its release on 2019-11-22. [Source](https://somsubhra.com/github-release-stats/?username=glimpse-editor&repository=Glimpse)

There are two new unofficial third-party download sources for Windows users that provide download statistics:

* 97 (+25) downloads from [Softpedia](https://www.softpedia.com/dyn-search.php?search_term=glimpse)
* 88 (+59) downloads from [SourceForge](https://sourceforge.net/projects/glimpse-image-editor/)
