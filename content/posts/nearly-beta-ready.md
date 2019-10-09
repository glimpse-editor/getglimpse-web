---
title: "Nearly Beta-Ready"
date: 2019-10-09T19:00:00+01:00
draft: false
---
Instead of providing a weekly reminder of our social media and project links across the web, check out our all-new [Contribute](/contribute/) page!

## Another release schedule update
The target date for Glimpse 0.1 to be "officially" released is some time this month (October 2019). However, you do not need to wait much longer to try the software out for yourself as we now have some beta testing builds for Windows and Linux!

We are still actively working on the packaging for Glimpse 0.1 and will continue to update the instructions you need to test pre-release versions of the software. Our initial instructions are available here: https://wiki.glimpse-editor.org/index.php?title=Testing_Glimpse

Please report any problems you find with our beta builds here: https://github.com/glimpse-editor/Glimpse/issues

## Snap support coming soon
psymole, EndrII and Heather Ellsworth have been doing some fantastic work ensuring we can build Glimpse with [snapcraft](https://snapcraft.io/). We previously believed we would not be able to support that packaging format, but thanks to their efforts it should be ready by the time Glimpse 0.1 is released.

You can follow their progress inside this merge request: https://github.com/glimpse-editor/Glimpse/pull/153

## Continued work on the Windows port
Bobby Moss has been working through problems related to packaging Glimpse 0.1 for Windows systems.

The [build process](https://wiki.glimpse-editor.org/index.php?title=Building_Glimpse/Windows) we currently follow dynamically links with components from MinGW, so time was set aside to determine which dependencies we needed to bundle with Glimpse and to verify that the licenses relating to those components permitted us to do so.

We have succeeded in creating a pair of ZIP files for Windows 7 or newer, with one being for 32-bit systems and the other for 64-bit. These have been provided as a stop-gap measure until we have working MSI installers and portable executables to publish within the next couple of weeks.

## Flatpak improvements
Mathieu Bridon has successfully removed the Webkit dependency from our flatpak development builds. This makes builds much faster and reduces the load from the job they produced for our [Jenkins CI server](https://jenkins.glimpse-editor.org).

## Website updates
Bobby Moss has been drafting the release notes for Glimpse 0.1.0 and a future "downloads" page. You can follow their progress here: https://github.com/glimpse-editor/getglimpse-web/pull/48

You can now also type `www.` at the start of our URL and still be redirected to the right place!

Christopher Davis has set up an automated staging and testing process for this website using [Netlify](https://www.netlify.com/) in preparation for further development.

## Can you help Exiv2?
We and a number of other free software projects depend on a project that is currently in a state of limbo. If you think you can help, the Exiv2 team urgently need your assistance: https://github.com/Exiv2/exiv2/issues/1018
