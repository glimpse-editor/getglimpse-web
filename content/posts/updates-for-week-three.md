---
title: "Updates for Week Three"
date: 2019-07-28T01:51:36+01:00
draft: false
---
## IRC Channel Deprecated
We stated last week that we would be deprecating the #glimpse IRC channel soon. After discussing that with the community we believe the switch to Matrix is now complete, so we can safely proceed with deprecating that communication method.

**To confirm: we no longer track, administer, support or own the #glimpse channel on Freenode**.

If you spot anyone abusing the IRC channel we have vacated, please report the incident to Freenode's own staff moderators.

To join the project discussion, please join us [on Matrix](https://matrix.to/#/#glimpse:matrix.org) instead.

We know some people will find our decision on this disappointing, but this was a choice our community made. The feedback so far has been positive, and our contributors appreciate the lower barrier to entry and more modern client applications.

## Code Changes
There have been quite a few code changes made on [the gimp2-10 branch](https://github.com/glimpse-editor/Glimpse/tree/gimp2-10).

Clipsey removed redundant doc files and performed some code cleanup for us. She also continued work on [Glir](https://github.com/glimpse-editor/glir), an automated tool intended to make the refactoring work in a future "hard fork" easier.

Bobby Moss (or "trechnex") removed [Wilber](https://www.gimp.org/about/ancient_history.html#publicity) from the top of menus and its giant eyes from the main window. He also started updating the translation files to use the correct project name and made minor tweaks like fixing "tip of the day" and ensuring we display the correct Glimpse release version in the "about" window. He also added our [Patreon sponsor contributors](https://www.patreon.com/glimpse) to `authors.xml`.

We also switched to using the "system" UI theme by default with "legacy" icons from GNU Image Manipulation Program 2.8 for the time being. The other stock themes from upstream have been removed because we intend to replace them with more visually appealing and accessible alternatives. Chaomodus has already started producing some of those replacements for us.

## Community Decisions
The community discussed how we should package the Linux port of Glimpse. It was agreed that [Flatpak](https://flatpak.org/) would be the preferred distribution mechanism and an [AppImage](https://appimage.org/) provided as an alternative for those who are unable to use Flatpaks.

A source tarball will also be provided for advanced users and distribution package maintainers for Linux, BSD and Solaris distributions.

We also continued to discuss the project's logo and there were a number of ideas and concepts posted to the Matrix channel. The most popular idea seemed to be a paintbrush splodging paint onto a Polaroid-style photo. Chris (or "Brainblasted") has fed back to a fellow GNOME contributor that we would like to have the branding assets some time in August so we can aim for a 1.0 release before the end of that month.

## Website Updates
We have rearranged the About page and added new questions for [how to follow news about Glimpse](../../about/#how-do-i-stay-up-to-date-with-this-project) and [how to get involved with this project](../../about/#how-do-i-contribute-to-this-project).

There is also now a provisional answer that lists [the operating systems we plan to support](../../about/#which-operating-systems-do-you-support).
