---
title: "Nearly Beta-Ready"
date: 2019-10-08T19:00:00+01:00
draft: true
---
Instead of providing a weekly reminder of our social media and project links across the web, check out our all-new [Contribute](../../contribute/) page!

## Another release schedule update
The target date for Glimpse 0.1 to be "officially" released is some time this month (October 2019). However, you do not need to wait much longer to try the software out for yourself!

We have already started beta testing the Linux flatpak version, and later on this week the Windows beta builds will also be ready. We are continuing to update the instructions you need here: https://wiki.glimpse-editor.org/index.php?title=Testing_Glimpse

Please report any problems you find with our beta builds here: https://github.com/glimpse-editor/Glimpse/issues

## Snap support coming soon
psymole, EndrII and Heather Ellsworth have been doing some fantastic work ensuring we can build Glimpse with [snapcraft](https://snapcraft.io/). We previously believed we would not be able to support that packaging format, but thanks to their efforts it should be ready by the time Glimpse 0.1 is released.

You can follow their progress inside this merge request: https://github.com/glimpse-editor/Glimpse/pull/153

## Continued work on the Windows port
Bobby Moss has been working through problems related to packaging Glimpse 0.1 for Windows systems.

The [build process we currently follow](https://wiki.glimpse-editor.org/index.php?title=Building_Glimpse/Windows) dynamically links with components from MinGW, so time was set aside to determine which dependencies we needed to bundle with Glimpse and verify that the licenses relating to those components permitted us to do so.

We have succeeded in creating a pair of ZIP files, one for 32-bit Windows and another for 64-bit Windows. Unfortunately they currently trigger Windows Smartscreen and cause some anti-virus programs to block the running process! Bobby Moss is currently determining how to sign the executables so that they pass security checks and users can grant them the appropriate trust level with confidence.

The ZIP files are expected to be ready by Friday 11th October 2019, and Bobby Moss will start building our first MSI installers with the [WiX Toolset](https://wixtoolset.org/) over the weekend.

## Flatpak improvements
Mathieu Bridon has successfully removed the Webkit dependency from our flatpak development builds. This makes builds much faster and reduces the load from the job they produced for our [Jenkins CI server](https://jenkins.glimpse-editor.org).

## Website updates
Bobby Moss has been drafting the release notes for Glimpse 0.1.0 and a future "downloads" page. You can follow their progress here: https://github.com/glimpse-editor/getglimpse-web/pull/48

## Can you help Exiv2?
We and a number of other free software projects depend on a project that is currently in a state of limbo. If you think you can help, the Exiv2 team urgently need your assistance: https://github.com/Exiv2/exiv2/issues/1018
