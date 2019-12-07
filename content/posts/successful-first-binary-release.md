---
title: "Successful First Binary Release"
date: 2019-12-07T06:00:00+00:00
draft: false
---
**DO NOT PUBLISH: WORK IN PROGRESS**

On Friday 22nd November 2019 we were pleased to announce our first binary release, Glimpse Image Editor 0.1.0. You can try it out for yourself on [our downloads page](/downloads/).

We are also pleased to announced that on Friday 29th November 2019 we released a new "signed" installer for the Windows platform. The previous "unsigned" version is still provided for troubleshooting purposes.

## Download Statistics
There have so far been 3497 downloads from our own directly-supported channels.

We would like to thank everyone that has tried out this release so far, and particularly those who have raised bugs and made feature suggestions.

### Breakdown by platform and channel
* Unsigned Windows installer: 2035
* Signed Windows installer: 290

*Source: http://www.somsubhra.com/github-release-stats/?username=glimpse-editor&repository=Glimpse*

* Linux Flatpak: 1172

*Source: https://gitlab.com/ahayzen/flathub-api-stats-generator*

### Community channels
Heather Ellsworth has reported that there has been an additional xxxx downloads from [snapcraft.io](https://snapcraft.io/glimpse-editor) so far.

We do not have figures for [AUR](https://aur.archlinux.org/packages/glimpse-editor-git/), but as that distribution channel follows development branch they would not be applicable to the stable release count.

## Plans for Glimpse Image Editor 0.1.1
We are hopeful that we will produce our first bug-fix release in January 2020. These will continue to be applied on the [GNU Image Manipulation Program 2.10.12](https://www.gimp.org/news/2019/06/12/gimp-2-10-12-released/) codebase.

The fixes will primarily relate to changes that were not applied to foreign translations, and parts of the user interface that were not correctly changed as part of the rebrand.

It is also possible that we will resolve missing Python plug-in support in the Windows version of Glimpse Image Editor 0.1.0, but as that is [an upstream documentation bug](https://github.com/glimpse-editor/Glimpse/issues/178) it may take some time to resolve and be pushed out to a later release.

You can see a full list of bugs we may potentially fix in 0.1.x bug-fix releases [in this milestone](https://github.com/glimpse-editor/Glimpse/milestone/6).

## Plans for Glimpse Image Editor 0.2.0
There is no firm timeline on when this will be released, but we anticipate it will arrive some time around March/April 2020. It will also be based on [GNU Image Manipulation Program 2.10.14](https://www.gimp.org/news/2019/10/31/gimp-2-10-14-released/).

Due to new information we have received from upstream, we are hopeful that 0.2.0 will be the first release [that supports macOS](https://github.com/glimpse-editor/Glimpse/issues/227).

Work is also ongoing to provide Glimpse Image Editor 0.2.0 as a [Linux AppImage](https://github.com/glimpse-editor/Glimpse/issues/108).

We may also publish this release in [the Windows Store](https://github.comhttps://deploy-preview-67--competent-wright-57cc1e.netlify.com/posts/successful-first-binary-release//glimpse-editor/Glimpse/issues/180) to increase awareness about our application among Windows users, and ensure Glimpse is available to people running locked-down versions of that operating system. It would be zero-cost to download and the user experience would be the same.

After receiving user feedback we also intend to [restore the Color icon theme](https://github.com/glimpse-editor/Glimpse/issues/232) as an option for the user interface.

We are also reviewing how to [support the CMYK color space](https://github.com/glimpse-editor/Glimpse/issues/252) and [add attribution in the front end UI](https://github.com/glimpse-editor/Glimpse/issues/179) for upstream contributors and translators.

You can see the full list of candidate issues [in this milestone](https://github.com/glimpse-editor/Glimpse/milestone/5). Be aware that our plans are subject to change depending on which blockers we encounter.

## We closed our Patreon account
As we have mentioned in previous blog posts, we went ahead with our planned decision to close down our Patreon donation account on Friday 6th December 2019.

We now only accept donations to the project through [Open Collective](https://opencollective.com/glimpse). That means we will now miss out on the donations we were receiving from Patreon (effectively halving the amount we receive each month), but we think the loss of revenue is outweighed by the advantages.

### Benefits from our perspective
* Fewer costs
* Easier management of backer rewards
* More than one person can administrate our fundraising campaign

### Benefits for our donors
* There's now the option to donate with a one-off payment *or* a monthly subscription
* US citizens can record contributions as a charitable donation for tax purposes
* The ability to review how we spend backer money helps potential donors make an informed decision before contributing

### Benefits for the wider community
* You can scrutinize how much money the project receives and who from
* You can view itemized spending records and which individuals are paying for things on our behalf.
* You can have confidence that an established 501c charity based in the United States with a proven track record is reviewing our expense claims and raised invoices before they are disbursed

### Patreon cash transfers
All the money we received through Patreon has been transferred over the past few months, and those transactions are listed under an "Incognito" user that is currently recorded as the top backer.

Our project's founder has also donated $100 over the last six months to cover the various fees and costs associated with those transfers, and ensured that our spending records on Open Collective cover every transaction since the project started on Friday 5th July 2019.

### Thank you to everyone who has donated so far
We believe we have gone above and beyond what most other free software projects are willing to do in this situation, and we have done that to ensure the wider community can have confidence in our motives and intentions. If you have any concerns, then you are welcome to raise them with our governance team on [our Matrix channel](https://matrix.to/#/#glimpse:matrix.org).

And, as usual, we encourage people to also [donate to the upstream project](https://www.gimp.org/donating/) to support the excellent work we rely on to make Glimpse Image Editor happen.
