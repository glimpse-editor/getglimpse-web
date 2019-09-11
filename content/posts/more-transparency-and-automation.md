---
title: "More Transparency And Automation"
date: 2019-09-11T22:40:00+01:00
draft: false
---

Instead of providing a weekly reminder of our social media and project links across the web, check out our all-new [Contribute](../contribute/) page!

We are still on schedule to release Glimpse 0.1 some time in September 2019. The application is mostly code-complete, so the outstanding work items primarily relate to artwork, packaging and automated builds. Minor patches may also still be applied for code cleanup and documentation.

## Glimpse project adopts Open Collective
After feedback from the community asking us to support more donation methods, we have now setup an account on [Open Collective](https://opencollective.com/glimpse).

The great thing about this service is that as supporters and users of Glimpse 0.1 you will be able see how much we receive in donations and how we use those funds to advance the project. It also means the business and legal side of receiving donations is taken care of for us by a well-known US-based charity, and more than one person can administer the funds.

We will continue to support Patreon donations for the foreseeable future, but periodically those funds will need to be transferred across to Open Collective. Switching across from Patreon gives you the option of sending one-off instead of monthly donations, is tax-deductible (in the US) and saves the project money on transfer fees.

More information: https://opencollective.com/glimpse/updates/welcome-to-the-glimpse-open-collective-profile

## Work started on Travis CI integration
Based on a great suggestion from Mathieu Bridon, Bobby Moss has ported the Linux build instructions to Travis-CI and started testing automated builds using the system.

This is still a work in progress as Bobby wants to setup the publishing steps for Windows, Mac and Linux in the same build file. You can take a look at the latest progress here: https://github.com/glimpse-editor/Glimpse/tree/travis-ci

## New project logo
We are very grateful to the amazing [James Daniel](https://jamesdaniel.dev/) for worked with us to produce our project logo. We have finally banished the public domain question mark we were using as a placeholder to the dustbin of history!

They also produced new icons for us to use for the application launcher and throughout the project. These have not yet been applied to the codebase and we are still working on usage guidelines, but you can see a preview of that work here: https://github.com/glimpse-editor/branding

## Code changes
Dominic Watson added the Glimpse project [code of conduct](../code-of-conduct/) on this website to the codebase as `CODE_OF_CONDUCT.md`.

Bobby Moss completed his previous work removing Wilber's eyes and flashing red "jump scare" easter egg from the main window after receiving feedback from XenonFiber about a patch submitted upstream. He also updated the code level documentation and "Help" links to include the new web domain.

We also saw some interesting new UI concepts from marcato10 and taciturasa that were assessed and discussed by the 2.x UI rewrite stream running in parallel to current development efforts.

## Project decisions
Unascribed raised the issue that the hash values in our code's commit tree do not match upstream. The project determined that the fix for this was "high impact with low benefit", so decided against doing so. Users are advised that they can still run `diff` on the commit tree and files to verify file integrity. More information: https://github.com/glimpse-editor/Glimpse/issues/132

The project also discussed where to host the release executables for Glimpse 0.1. The Linux packages are likely to be hosted on [Flathub](https://flathub.org/home) and [AppImageHub](https://appimage.github.io/), while the Mac and Windows packages will most likely be mirrored from a Github release tag. We are also investigating what is required for us to support torrent files.

We also agreed and implemented the new artwork and Open Collective account discussed earlier in this blog post.

## Website updates
Bobby Moss updated the [Contribute](../contribute/) page so it grouped things together a little better and provided new donate links. He also added a new default favicon based on the new project logo.
