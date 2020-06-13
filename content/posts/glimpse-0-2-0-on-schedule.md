---
title: "Glimpse Image Editor 0.2.0 On Schedule"
date: 2020-06-13T22:00:00+01:00
draft: false
---
Check out our [Contribute](/contribute/) page for social media and news links to follow our progress.

## Our Statement on Equality
FOSS projects do not exist in a vacuum isolated from the rest of society. Historically our movement has not engaged well with people from diverse backgrounds, meaning we have missed out on valuable ideas and contributions, and we have all been the poorer for it.

The Glimpse project was founded and continues to be governed by a black man, a transgender woman and a gay man. We continue to rely on the contributions and feedback from our atypically diverse community of contributors to shape our project's structures and processes.

We are all shocked and appalled by the ongoing injustices perpetrated against people around the world based on their race, gender and sexuality. Our project and contributors confirm that we all stand in solidarity with the Black Lives Matter movement and support Pride Month.

If we collectively want the free software and open source movements to succeed and stay relevant to as many people as possible, we all need to work together to create a safe, welcoming community where everyone feels respected and able to express their true selves without hurting others. That will take a lot of work and "trial and error", but we can succeed if we take the time to listen to each other and learn from past mistakes.

## Glimpse Image Editor 0.2.0 Progress
As previously stated, we intend to release Glimpse Image Editor 0.2.0 in July 2020. We anticipate that beta testing will start before the end of June 2020.

We have already re-based the code on the GNU Image Manipulation Program 2.10.18 and uplifted the dependency versions for BABL, GEGL and MyPaint. Considerable re-work was needed because some of those dependencies now use the "meson" build system, and we are still in the process of updating translations and build scripts.

As mentioned in previous blog posts we have also made minor refinements to the icon packs, updated the splash screen, and provided a new application icon that works better on dark/light backgrounds.

Remaining tasks include:

* Refactoring "libgimp" libraries to "libglimpse" so that distribution packagers no longer have to mark the GNU Image Manipulation Program as a conflicting package
* Updating man pages so that they include Glimpse-specific information
* Updating our automated Linux build job to package the result as an AppImage
* Creating a new automated Windows build job that packages the result as a ZIP file
* Updating the WiX Toolset manifest to display the GNU General Public License version 3 to end users and provide the option to install in a custom location on Windows
* Updating the WiX Toolset manifest for the latest 32-bit Windows build, and Creating a new WiX Toolset manifest for the 64-bit Windows build
* Creating the "Optional" Linux AppImage containing extra third party plug-ins such as G'MIC, Rasterizer, and others

## Servers Decommissioned and Replaced
As stated in previous blog posts, we have decommissioned the vast majority of our servers on Linode to cut our running costs and safeguard our project's future. That is possible because we now know how many contributors and users we need to facilitate, where before we were concerned we might have to scale rapidly in a very short space of time.

We are particularly proud of our new developer wiki. Not only does it cover various ways to build and package the code for Windows and Linux, it also lists known issues and hosts important project documents. It will continue to evolve and grow over time.

There will no longer be a development repository for Flatpaks, but we intend to provide Linux AppImage files for our development, beta and release branches on Github. These will be automatically generated with Github Actions.

Github Actions will also be used to create automated builds for Windows using the "crossroad" tool that the GNU Image Manipulation Program contributors currently rely on. It is likely that for the 0.2.0 release the MSI packaging we have created with WiX Toolset will still be run manually, but we intend to fully automate that for future releases too.

Our website has also been migrated to Github Pages, but we still host our own "nanode" VPS with an NGINX proxy server to redirect existing in-app links to the correct places within our project. We anticipate that the glimpse-editor.org and glimpse-editor.com domains will be renewed in August 2020, and that will ensure that users still running the 0.1.x releases will continue to be supported for a reasonable time period.

## Chaomodus Stepped Down From The Governance Team
We would like to thank chaomodus for helping us shape and moderate the project over the last five months. Their expertise as an experienced sysadmin was also invaluable when we were working on self-hosted infrastructure proofs of concept.

They will continue to be a part of the Glimpse project as a contributor, and we look forward to working with them in the future.

## Pre-emptive Action Taken on Social Media
As some of you may have noticed, we send out a message across our social media channels on 2020-05-29 that we were temporarily restricting access to our Github repositories and Matrix channel. We reversed those restrictions on 2020-06-03 as promised.

For background, between August 2019 and November 2019 there was a sustained troll campaign targeted at our project. This was organized and carried out by "free speech extremists" who believed that our intention was to "tear down the GNU Image Manipulation Program" and replace it with a "politically correct" alternative.

During that time our contributors received considerable personal abuse for their race, gender and sexuality. Our creator was also briefly forced off the public Internet, and still has not reinstated all of his online accounts. There were also YouTube videos and blog posts published with the intent of spreading false accusations and misleading information about our project to sabotage our reputation, and we still receive negative reviews through application distribution channels and social media platforms for that reason.

We chose to take action because our contributors expressed concern that a Linux influencer who has previously posted misleading information about our project was set to make a video we expected to go viral. We did not know if the project would be mentioned by name, or if the same incorrect information would be repeated, or if the video would trigger the same trolls into action. Measures were taken to protect our contributors and limit the disruption that such an event would cause.

Fortunately the video our contributors were concerned about did not go viral, so this was a "false alarm". We do not regret the decision we took however, because we value the safety of our contributors and the integrity of our project above all other considerations.

### A Message to Our Critics
The stated intention of this project is to address the fear, uncertainty and doubt reasons that prevent the GNU Image Manipulation Program from being used, advocated and deployed more widely in English-speaking countries. Our concerns about the name comprise only a small part of that mandate, and we have stated clearly on our FAQs page since August 2019 that it is not our intention to replace or supplant the GNU Image Manipulation Program. 

We would also like to make it very clear that we are not backed or influenced by any specific company, and there is no larger partisan political movement to which we all belong. Glimpse Image Editor is a not-for-profit project that is developed and maintained by enthusiastic amateurs who are volunteering their spare time to fix a well-articulated problem.

Since starting the project we have co-operated fully with the upstream contributors' collective requests to amend our FAQs page, publicly apologized for any past mistakes, conducted ourselves positively on social media and issued corrections when requested, provided a contact on the upstream IRC channel to resolve potential conflicts, and have passed along $150 USD of our own donations so far. We have also not retaliated against any negative actions that have been taken against us by misguided individuals that feel it necessary to attack our project and contributors "to protect the GNU Image Manipulation Program".

Our fork does not negatively impact the popularity of the upstream project or the work their contributors do. The same core contributors that were working on the GNU Image Manipulation Program before are still working on the GNU Image Manipulation Program today. Our project is also in full compliance with the wording of and spirit behind the GNU General Public License version 3.

It is time for those of you who were angered by the way our fork emerged to put down your torches and pitchforks, and remember that our success does not detract from the GNU Image Manipulation Program's success. If both programs can be successful, that means fewer people yelling at each other on social media, and more people contributing constructively to the advancement of the free software movement.