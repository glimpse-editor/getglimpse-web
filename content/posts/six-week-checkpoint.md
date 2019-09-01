---
title: "Six Week Checkpoint"
date: 2019-08-21T17:53:00+01:00
draft: false
---
It has been a busy couple of weeks! Thank you for bearing with us while we continue to work hard on producing the first Glimpse release.

We now expect it to arrive some time in September 2019. Our developers are still puzzling out how to package the built code for different operating systems, and the artwork for the rebrand is not quite ready yet. Despite this, you can expect there to be a code freeze before the end of August 2019 so we can focus our energies on solving both of those problems.

## Code changes
 Mathieu Bridon has been updating the Flatpak packaging our Linux build will rely on. He is also fixing GNOME desktop integrations for it.

Bobby Moss helped newcomers to the codebase at Clipsey's suggestion by adding the GEGL, BABL and MyPaint dependencies as submodules. He also added Vagrant support so newcomers can get a working build environment up-and-running as quickly as possible. To build our code and then run the current in-development version of Glimpse (you will need [an XServer installed](https://sourceforge.net/projects/xming/) for the final command if you are not using Linux as a host):

```bash
$ vagrant up
$ vagrant ssh
$ cd /vagrant
$ sh glimpse-vagrant.sh
$ ./glimpse-prefix/bin/glimpse
```

Bobby also provisioned a new Jenkins build server at https://jenkins.getglimpse.app and will be implementing an automated build job for the Glimpse source code over the next week or two.

## A new versioning scheme
We discussed as a community how we should version and market our fork over the coming months and years.

Glimpse 0.1 is the first release, scheduled for some time in September 2019, and further "soft fork" releases will start with 0.x

Glimpse 1.0 will be the first "hard fork". We expect this to be fully ported to GTK3 and provide its own Documentation. It likely won't happen until GNU Image Manipulation Program 3.0 has been released some time in 2020.

Further "hard fork" releases will start with 1.x, and these will have more ambitious changes that do not need to be re-applied to an upstream codebase.

As discussed in the last post there will also be a front-end UI rewrite happening in parallel. The name for this has not yet been confirmed, but initially it will have versions that start with 2.x as the plan would be to switch over to it once it achieves feature parity with the current application. We estimate that will take until 2021 to achieve even if we started right away, but the long term benefit would be worth it.

## Plans for the distant future
Chaomodus has continued to develop the new MediaWiki server at https://wiki.getglimpse.app, and they along with meltheadorable, Christopher Davis and others have been examining which plug-ins we should keep or remove in subsequent 0.x releases.

Those same people have used the same server to upload screenshots of existing image editing application user interfaces. This is intended to help them analyse what is good and bad about current image editing applications, then produce their own design mockups to compare and discuss.

The choice of programming language for the rewrite was also discussed. That is being tracked on this Github issue: https://github.com/glimpse-editor/Glimpse/issues/70

## Website updates
The website is now hosted on the new Jenkins build server. This ensures we keep our costs low and that our website re-builds properly when we add new posts.
