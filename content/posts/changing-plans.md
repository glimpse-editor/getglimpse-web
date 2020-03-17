---
title: "Changing Plans"
date: 2020-03-16T08:28:00+00:00
draft: false
---
Check out our [Contribute](/contribute/) page for social media and news links to follow our progress.

## Glimpse Image Editor updated on Snapcraft
We are pleased to announce that the Snapcraft version of Glimpse Image Editor was updated to 0.1.2 on 2019-03-12. The feedback we have received about this so far has been very positive.

Bobby Moss also worked with Heather Ellsworth to ensure that the “edge” and “beta” channels used by this community-supported download source builds from the correct Github branches, and that the app store text matches what we use for Flathub.

You can find out more here: https://snapcraft.io/glimpse-editor

## Adapting to the Coronavirus (COVID-19) pandemic
We would like to reassure our end users, followers and supporters that we take this global crisis very seriously. The project is taking action to ensure that development continues for as long as possible, and that you are not left without feature improvements and security updates.

We have advised our contributors to avoid attending any free software or Linux conferences on our behalf, and have been circulating this advice from the World Health Organization: https://www.who.int/emergencies/diseases/novel-coronavirus-2019/advice-for-public

Our planned releases over the next six months have also been changed to account for more intermittent contributions from our existing project members. This blog post goes into more detail about that in the "Updated release schedule and priorities" section.

Finally, we would like to ask all our users to be patient with us if there is a delayed response to bug tickets, feature requests, merge approvals, and questions on social media. Our contributors and their families are just as susceptible to COVID-19 as you are, but we will be doing our best to keep the project progressing.

* Find out how to help our project progress: https://glimpse-editor.org/contribute/
* Bolster our funding reserves on Open Collective: https://opencollective.com/glimpse
* Help the GNU Image Manipulation Program too: https://www.gimp.org/donating/

We would also like to remind everyone to wash your hands, take care of your neighbours, and follow the advice your government has provided you with.

## Updated release schedule and priorities
We have decided to create a 0.1.4 release on the same GNU Image Manipulation 2.10.12 base instead of creating a new 0.2.0 release based on 2.10.18.

The reason for this is we want to spend more time fixing bugs and packaging problems. We also expect to have reduced capacity for changes throughout the COVID-19 pandemic, so we have to make adjustments to allow for that.

We will focus on new release packaging first. We expect to provide Linux AppImages for 0.1.2 before the end of March 2020, and an MSIX file for those using Windows 10 on their workplace machines in April 2020.

The new high contrast GUI themes and icons that upstream developers introduced in the GNU Image Manipulation Program 2.10.18 will be backported for Glimpse Image Editor 0.1.4, as will a modified version of the new update checker. We will also uplift the versions for BABL and GEGL that we include in all of our own installers, and pre-bundle useful plug-ins like G'MIC.

The other big change coming for Glimpse Image Editor 0.1.4 is we intend to fix the man pages (finally!) and refactor libgimp so that distribution maintainers can package our software without having to mark the GNU Image Manipulation Program as a conflict in their repositories.

Chaomodus will also be working on Jenkins build infrastructure. They will also be evaluating how we can better manage and improve our non-English translations.

We are aiming to release Glimpse Image Editor 0.1.4 in May 2020, but that may be delayed if the COVID-19 outbreak impacts our contributors badly. After 0.1.4 is released we will immediately start work on the macOS port.

You can see a provisional list of all the planned features and fixes here: https://github.com/glimpse-editor/Glimpse/milestone/12

## Download figures update
All figures were correct on the day this blog post was published. Sources have been provided so that our claims can be independently verified.

We know that Glimpse Image Editor has been downloaded at least 12506 times across all platforms and download sources since it was first released on 2019-11-22, and we estimate that we are supporting an install base of at least 5000 machines.

If these figures are accurate then this would be a good start for us, and it would mean we have [almost doubled the number of downloads](/posts/progress-on-our-first-errata-release/) since 2020-01-31. It is also worth remembering that Glimpse Image Editor has only been available to download for a little over three months, we are working with very limited resources, and this project had quite a mixed response from the wider free software community when we first started.

Planned improvements such as providing a Linux AppImage, packaging the Windows port for the Microsoft Store and porting the application to macOS will boost these numbers further over the course of 2020. We also anticipate our install base will grow significantly as the number of third party download sources increases.

### GNU/Linux
Glimpse Image Editor has been downloaded 5229 (+2559) times from Flathub since it was first released, and there have been 4501 requests for updates. [Source](https://gitlab.com/ahayzen/flathub-api-stats-generator)

Heather Ellsworth reports that there are 1623 (-7) active users that have installed Glimpse Image Editor through Snapcraft. [Source](/glimpse-snap-2020-03-14.png)

The distribution tarballs we provided on Github for Glimpse Image Editor 0.1.2 have been downloaded 52 times, suggesting that there is some early interest from Linux distro maintainers about hosting our software natively in their repositories. [Source](https://somsubhra.com/github-release-stats/?username=glimpse-editor&repository=Glimpse)

We do not have the figures for other community-supported Linux download sources.

### Windows
The new Glimpse Image Editor 0.1.2 installer has been downloaded 573 times from Github since its release on 2020-03-02. [Source](https://somsubhra.com/github-release-stats/?username=glimpse-editor&repository=Glimpse)

To date there have been 4951 (+761) direct downloads of Glimpse Image Editor 0.1.0 for Windows from Github. [Source](https://somsubhra.com/github-release-stats/?username=glimpse-editor&repository=Glimpse)

There are two new unofficial third-party download sources for Windows users that provide download statistics:

* 61 downloads from [Softpedia](https://www.softpedia.com/dyn-search.php?search_term=glimpse)
* 17 downloads from [SourceForge](https://sourceforge.net/projects/glimpse-image-editor/)
