---
title: "Beta Testing Underway For 0.2.0"
date: 2020-07-21T08:45:00+01:00
draft: false
---
Check out our [Contribute](/contribute/) page for social media and news links to follow our progress.

We are still currently on track to release Glimpse Image Editor 0.2.0 before the end of July 2020. That is subject to change if we discover a major problem during beta testing, or if we need extra time to produce our new Windows installers.

To commemorate our project's first anniversary and the upcoming release of Glimpse Image Editor 0.2.0, we intend to donate $350 USD to the GNU Image Manipulation Program developers. That will mean in our first year we will have contributed $500 USD of our donations in total back upstream.

We also recently added some more answers to [our FAQs page](/about/), so we encourage our community to give that page another look.

## Linux beta testing begins
On 2020-07-18 we published the latest 0.2.0 beta on Snapcraft. To try it out, follow the instructions on [this wiki page](https://github.com/glimpse-editor/Glimpse/wiki/Beta-Testing-with-Snapcraft-%28Linux%29)

On 2020-07-19 we published the latest 0.2.0 beta on Flathub, and started publishing automatically-generated [single-file bundles](https://docs.flatpak.org/en/latest/single-file-bundles.html) on Github. To try it out, follow the instructions on [this wiki page](https://github.com/glimpse-editor/Glimpse/wiki/Beta-Testing-with-Flathub-%28Linux%29)

We will continue to update those builds over the next couple of weeks as we discover bugs and fix them ahead of release.

Work is still ongoing with the Linux AppImage packaging. Unfortunately we seem to be running into some problems with this, so it is possible that may be delayed until after 0.2.0 is formally released. You can track progress on this Github Issue: [#108](https://github.com/glimpse-editor/Glimpse/issues/108)

## Windows beta testing coming soon
We intend to improve our existing 32-bit MSI installer with the option to set a custom install location. We will also continue reducing hard disk usage, and add "quality of life" improvements like better icons and a new application launcher. For the first time, we will also provide a 64-bit MSI installer.

Our project would like to thank [the MSYS2 contributors](https://www.msys2.org/docs/ci/) for making it possible for us to build the Glimpse Image Editor source code automatically with our own [Github Actions](https://github.com/glimpse-editor/Glimpse/actions).

Both installers for the beta testing builds will arrive later on this week. The reason for the delay is that the contributor working on the [WiX Toolset](https://wixtoolset.org/) manifests has been ill recently. Fortunately their COVID-19 test came back negative, and we wish them a speedy recovery!

## New wiki pages for third-party plugin support
We have provided new tutorials that explain how to install popular existing plugins for the GNU Image Manipulation Program in your existing Glimpse Image Editor 0.1.2 installation. You can read them here: https://github.com/glimpse-editor/Glimpse/wiki#third-party-plugin-installation-guides

Those wiki pages also explain how far along we are with improving compatibility for [G'MIC](https://gmic.eu/), [Liquid Rescale](http://liquidrescale.wikidot.com/), [PhotoGIMP](https://github.com/Diolinux/PhotoGIMP) and [Resynthesizer](https://github.com/bootchk/resynthesizer). 

After Glimpse Image Editor 0.2.0 is released, we intend to provide a Linux AppImage that contains a number of third party plugins by default. We will likely adapt the work that has been done here: https://github.com/aferrero2707/gimp-appimage

We are also reviewing if there are changes in PhotoGIMP that we can include by default with Glimpse Image Editor to improve the user experience. You can track our progress on these Github Issues: [#412](https://github.com/glimpse-editor/Glimpse/issues/412), [#414](https://github.com/glimpse-editor/Glimpse/issues/414)

## New website re-design
We would like to thank [Zach Krall](https://zachkrall.com/) for their amazing redesign of our project website. It fits much better with the existing branding guidelines set out by [James Daniel](https://jamesdaniel.dev/), the artist that created our original logo.

[Bobby Moss](https://trechnex.github.io/) also updated the homepage so it is clearer to newcomers what our project aims are, and which version of the GNU Image Manipulation Program our code is based on. We intend to replace the screenshots that are currently displayed before 0.2.0 is released.

## Planning for the longer term
We are pleased to announce that Glimpse NX (previously known as "the rewrite") is going to be where a lot of our developers and resources are going to be focussed over the next few years. There will be more details to share about that project in future blog posts.

However, we will continue to provide updates for our fork of the GNU Image Manipulation Program. Our intention is to provide two releases each year. One will be published each July that rebases on a recent version of the GNU Image Manipulation Program, and another will be published each January that iterates on it. We will re-issue a release only if an urgent bug-fix or security update is required.

Our existing release timetable (i.e. one release every 3-4 months) does not permit us enough time to take on more ambitious changes, such as writing our own plug-ins and customizing the user interface. Now that we have fulfilled our [main development priorities](https://github.com/glimpse-editor/Glimpse/wiki/Development-Priorities), we believe that spacing out our releases will enable us to focus on making UI improvements and differentiating the user experience.

We are also looking into new forms of packaging we can support. For example: [#322](https://github.com/glimpse-editor/Glimpse/issues/322), [#236](https://github.com/glimpse-editor/Glimpse/issues/236), [#402](https://github.com/glimpse-editor/Glimpse/issues/402)

## Download figures update
All figures were correct on the day this blog post was published and sources have been provided so that you can independently verify them. 

If the figures are accurate then we believe that since 2020-05-04 we have had a noticeable increase in popularity with Windows users. Our userbase on Linux has remained approximately the same size, and we suspect some of our users may have switched from Snapcraft to Flathub. [Source](posts/anniversary-plans/)

We know that Glimpse Image Editor has been downloaded at least 54025 (+8417) times across all platforms, versions and download sources since it was first released on 2019-11-22. A detailed breakdown is provided below.

### Linux
Heather Ellsworth reports that there have been 12197 (-4704) active users over the last month that have installed Glimpse Image Editor through [Snapcraft](https://snapcraft.io/glimpse-editor/). These figures are only available through a private dashboard, so we have [provided a screenshot](/glimpse-snap-2020-07-21.png).

Glimpse Image Editor has been downloaded 18028 (+4803) times from [Flathub](https://flathub.org/apps/details/org.glimpse_editor.Glimpse) across all versions since it was first released on 2019-11-22, and there have been 11356 recent requests for updates.

We use [a third-party tool](https://gitlab.com/ahayzen/flathub-api-stats-generator) to get Flathub statistics, and this is the command we run: 
```
$ python3 main.py --report downloads_by_app --type data --output out.dat --report-args app-id=org.glimpse_editor.Glimpse
```

The distribution tarballs we provided on Github for Glimpse Image Editor 0.1.2 have been downloaded 538 (+182) times. [Source](https://somsubhra.com/github-release-stats/?username=glimpse-editor&repository=Glimpse)

We do not have the figures for other community-supported Linux download sources.

### Windows
Glimpse Image Editor 0.1.2 has been downloaded 17959 (+8039) times from Github since its release on 2020-03-02. [Source](https://somsubhra.com/github-release-stats/?username=glimpse-editor&repository=Glimpse)

To date there have been 5080 (+59) direct downloads of Glimpse Image Editor 0.1.0 for Windows from Github since its release on 2019-11-22. [Source](https://somsubhra.com/github-release-stats/?username=glimpse-editor&repository=Glimpse)

There are two new unofficial third-party download sources for Windows users that provide download statistics:

* 118 (+21) downloads from [Softpedia](https://www.softpedia.com/dyn-search.php?search_term=glimpse)
* 105 (+17) downloads from [SourceForge](https://sourceforge.net/projects/glimpse-image-editor/)
