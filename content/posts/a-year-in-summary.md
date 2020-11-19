---
title: "A Year In Summary"
date: 2020-11-07T15:00:00+00:00
draft: false
---
**DO NOT PUBLISH. FIGURES WILL NEED TO UPDATED RIGHT UP UNTIL PUBLISH ON 2020-11-21**
(Figures in current draft calculated on 2020-11-07)

TODO: Intro section here that summarises our achievements through the year.

- All primary and secondary objectives have been achieved
- At least 83000 downloads across three releases
- $500 USD raised for the GNU Image Manipulation Program developers

## Contents {#contents}
- [Features delivered so far](#features-delivered-so-far)
- [Download figures update](#download-figures-update)
- [Financial summary](#financial-summary)
- [Goals for 2021](#goals-for-2021)
- [Long term plans](#long-term-plans)

## Features delivered so far {#features-delivered-so-far}
Since August 2019 we have maintained a [Development Priorities](https://github.com/glimpse-editor/Glimpse/wiki/Development-Priorities) wiki page. As we have produced three releases in the past year, we felt it was a good time to review how many of our original objectives have actually been delivered.

Our conclusion is that the primary objectives have all been delivered, our secondary objectives have been delivered as far as we can with the resources we have available, and we have made some initial progress on our tertiary objectives.

### Primary Objectives
- Fix the software's problematic "gimp" name **(Delivered)** [#9](https://github.com/glimpse-editor/Glimpse/issues/9) [#51](https://github.com/glimpse-editor/Glimpse/pull/51) [#71](https://github.com/glimpse-editor/Glimpse/pull/71) [#92](https://github.com/glimpse-editor/Glimpse/issues/92)
- Replace the Wilber mascot with a professional logo **(Delivered)** [#1](https://github.com/glimpse-editor/Glimpse/issues/1) [#31](https://github.com/glimpse-editor/Glimpse/issues/31) [#47](https://github.com/glimpse-editor/Glimpse/issues/47) [#186](https://github.com/glimpse-editor/Glimpse/issues/186) ([Branding repo](https://github.com/glimpse-editor/branding))
- Update the software's translations so the new name is used throughout the user interface **(Delivered)** [#210](https://github.com/glimpse-editor/Glimpse/issues/210) [#219](https://github.com/glimpse-editor/Glimpse/pull/219) [#279](https://github.com/glimpse-editor/Glimpse/pull/279) [#424](https://github.com/glimpse-editor/Glimpse/issues/424)

### Secondary Objectives
- Clean up the user interface so it looks more visually attractive and professional **(Partially Delivered)** [#51](https://github.com/glimpse-editor/Glimpse/pull/51) [#134](https://github.com/glimpse-editor/Glimpse/pull/134) [#286](https://github.com/glimpse-editor/Glimpse/pull/286)
- Keep applying our changes to stable upstream releases on a predictable release schedule **(Delivered)** [#189](https://github.com/glimpse-editor/Glimpse/issues/189) [#329](https://github.com/glimpse-editor/Glimpse/issues/329) [#330](https://github.com/glimpse-editor/Glimpse/issues/330) [#341](https://github.com/glimpse-editor/Glimpse/issues/341) ([Milestones](https://github.com/glimpse-editor/Glimpse/milestones))
- Preserve compatibility with existing plug-ins, themes and third-party components **(Mostly Delivered, Missing Python support on Windows, Inherited regressions in 0.2.0)** [#132](https://github.com/glimpse-editor/Glimpse/issues/132) [#232](https://github.com/glimpse-editor/Glimpse/issues/232) ([Plugin instructions on Developer Wiki](https://github.com/glimpse-editor/Glimpse/wiki#third-party-plugin-installation-guides)) 

### Tertiary Objectives
- Improve overall end user experience for Windows (and if possible macOS) users **(Partially Delivered on Windows, Not Delivered on macOS)** [#58](https://github.com/glimpse-editor/Glimpse/issues/58) [#119](https://github.com/glimpse-editor/Glimpse/issues/119) [#178](https://github.com/glimpse-editor/Glimpse/issues/178)
- Fix usability and accessibility problems in the existing user interface **(Partially Delivered, More Planned for 0.2.2)** [#347](https://github.com/glimpse-editor/Glimpse/pull/347) [#412](https://github.com/glimpse-editor/Glimpse/issues/412)
- Address longstanding code and documentation problems that upstream have been unable or unwilling to address **(Not Delivered on code, Partially Delivered on docs)** ([Windows & Linux packaging instructions on Developer Wiki](https://github.com/glimpse-editor/Glimpse/wiki)) 
- Ensure upstream contributions are still appropriately acknowledged in the user interface **(Delivered)** [#291](https://github.com/glimpse-editor/Glimpse/pull/291) [#300](https://github.com/glimpse-editor/Glimpse/issues/300)
- Include useful plug-ins (or similar functionality) that are hard to find or install by default **(Not Delivered, Planned for 0.2.2 & 0.3.0)**

### Clarifications
We view our custom installer based on [WiX Toolset](https://wixtoolset.org) as a Windows experience improvement because it completes the installation faster and the end result uses less hard disk space when compared to the GNU Image Manipulation Program 2.10.18. We are aware that some may disagree as the GUI wizard we introduced in 0.2.0 still needs artwork and has not yet been translated to other languages.

We consider missing Python support on Windows a "Won't Fix" issue as [Python 2 is now end of life](https://www.python.org/doc/sunset-python-2/) and not including it seems to improve the application startup time.

We also inherited regressions that broke compatibility with [Liquid Rescale](https://github.com/glimpse-editor/Glimpse/wiki/How-to-Install-the-Liquid-Rescale-Plugin) when we re-based on GNU Image Manipulation Program 2.10.18 for Glimpse Image Editor 0.2.0, but we intend to backport patches from 2.10.20 to fix that in 0.2.2. [Source](https://gitlab.gnome.org/GNOME/gimp/-/issues/4496)

At the present time we lack the capacity to [create a native macOS port](https://github.com/glimpse-editor/Glimpse/issues/402) or produce code changes that directly assist the GNU Image Manipulation Program developers. However, we are optimistic that [Glimpse NX](/about/#what-is-glimpse-nx) will deliver on those objectives instead because it is attracting more interest from potential contributors, and it will require us to port useful upstream components to [GTK4](https://gitlab.gnome.org/GNOME/gtk/-/milestones/1).

[Return to top](#contents)

## Download figures update {#download-figures-update}
All figures were correct on the day this blog post was published and sources have been provided so that you can independently verify them. Any **+** or **-** change is calculated from the previous figures published on 2020-07-21. [Source](posts/beta-testing-underway-for-0-2-0/)

If the figures are accurate then we believe that since 2020-07-21... **TBD Conclusion**.

We know that Glimpse Image Editor has been downloaded at least **83622** (+29597) times across all platforms, versions and download sources since the software was first released on 2019-11-22. A detailed breakdown is provided below, and the figures we have provided should be viewed as indicators only because we are relying on the accuracy of external tools.

We have deliberately not provided any estimates about the total size of our active user base because there is no universally agreed methodology for extrapolating that figure from download statistics. However, we have made some educated guesses about any discrepencies we spotted to lend context that you might find useful.

### Linux
There have been **12236** (+39) active users over the past month that have installed Glimpse Image Editor from the [the Snap Store](https://snapcraft.io/glimpse-editor/). These figures are only available through a private dashboard, so we have [provided a screenshot](/glimpse-snap-2020-07-21.png). **TODO: Update Screenshot**

Glimpse Image Editor has been downloaded **34103** (+16075) times from [Flathub](https://flathub.org/apps/details/org.glimpse_editor.Glimpse) across all versions since it was first released on 2019-11-22, and there have been **20209** (+8853) recent requests for updates. 

We believe the true rise in active installations on Flathub since 2020-07-21 is around half the stated change, because we released 0.2.0 twice; Once with GNOME Platform SDK 3.36, and then a second time with GNOME Platform SDK 3.38.

We use [a third-party tool](https://gitlab.com/ahayzen/flathub-api-stats-generator) to get Flathub statistics, and this is the command we run:
```
$ python3 main.py --report downloads_by_app --type data --output out.dat --report-args app-id=org.glimpse_editor.Glimpse
```

We also have download statistics for standalone Linux builds we provided on Github. [Source](https://somsubhra.com/github-release-stats/?username=glimpse-editor&repository=Glimpse)

- Standalone bundle flatpaks we provided for Glimpse Image Editor 0.2.0 have been downloaded **539** times since they were released on 2020-08-25.
- Distribution tarballs we provided for Glimpse Image Editor 0.1.2 have been downloaded **563** (+25) times since they were released on 2020-03-02.

We have omitted statistics for our [Linux AppImage](https://github.com/glimpse-editor/Glimpse/releases/tag/continuous), as that is pre-release software with a download counter that resets every time we make a change to the `dev-g210` branch. We also do not have the figures for other community-supported Linux download sources.

### Windows
We have combined download figures for both signed and unsigned MSI installers downloaded from Github. We did not count pre-release versions of the software. [Source](https://somsubhra.com/github-release-stats/?username=glimpse-editor&repository=Glimpse)

- Glimpse Image Editor 0.2.0 (x64 MSI) has been downloaded **5935** times from Github since its release on 2020-08-25. 
- Glimpse Image Editor 0.2.0 (x86 MSI) has been downloaded **3557** times from Github since its release on 2020-08-25.
- Glimpse Image Editor 0.1.2 (x86 MSI) has been downloaded **20707** (+2748) times from Github since its release on 2020-03-02.
- Glimpse Image Editor 0.1.0 (x86 MSI) has been downloaded **5130** (+50) times from Github since its release on 2019-11-21.

There are also unofficial third-party download sources for Windows users that provide download statistics:

* **406** downloads from [Chocolatey](https://chocolatey.org/packages/glimpse/)
* **201** (+83) downloads from [Softpedia](https://www.softpedia.com/dyn-search.php?search_term=glimpse)
* **245** (+140) downloads from [SourceForge](https://sourceforge.net/projects/glimpse-image-editor/files/stats/timeline)

Unfortunately we cannot access download statistics from [WinGet](https://winget.run/pkg/Glimpse/Glimpse). Work is also still ongoing to bring Glimpse Image Editor to the [Scoop](https://scoop.sh/) package manager: [#65](https://github.com/glimpse-editor/Glimpse/issues/65)

[Return to top](#contents)

## Financial summary {#financial-summary}

**TODO**: Will collate figures from our Open Collective profile.

[Return to top](#contents)

## Goals for 2021 {#goals-for-2021}
We have provided two great blog posts that lay out our plans for the coming year: [First Steps Towards the Future](/posts/first-steps-towards-the-future/) and [An Exciting Year Ahead](/posts/an-exciting-second-year-ahead/).

In addition, these are our goals for 2021:
- Maintain primary/secondary objectives and deliver tertiary objectives in two new releases
- Reach at least 120000 downloads for Glimpse Image Editor across all five releases
- Raise another $500 USD for the GNU Image Manipulation Program developers (reaching $1000 USD in total since the project started)
- Deliver the first alpha quality Glimpse NX release

We would also like to make it clear that Glimpse Image Editor 0.2.2 will be the final release where we produce Windows installers for both the x64 and x86 architectures. We plan to deprecate support for x86 versions of Windows in July 2021. [More information](https://github.com/glimpse-editor/Glimpse/wiki/Supported-Platform-Versions-%28Windows%29)

Glimpse Image Editor 0.3.0 is likely to break binary compatibility with third-party plugins and existing packaging processes so we can resolve conflicts in Linux/BSD package managers. [#7](https://github.com/glimpse-editor/Glimpse/issues/7) 

To mitigate that problem, we plan to start maintaining patched versions of third-party plugins in full compliance with their original licenses. The practical benefit for users should be fewer compatibility problems ongoing and more third-party plugins included with Glimpse Image Editor by default in future releases. [#414](https://github.com/glimpse-editor/Glimpse/issues/414) [#441](https://github.com/glimpse-editor/Glimpse/issues/441) [#465](https://github.com/glimpse-editor/Glimpse/issues/465) [#466](https://github.com/glimpse-editor/Glimpse/issues/466) [#467](https://github.com/glimpse-editor/Glimpse/issues/467)

Finally, we have dropped the "Glimpse Redux" initiative. As laid out in the next section, we have chosen to focus our attention and resources on [Glimpse NX](/about/#what-is-glimpse-nx) instead of porting our changes to a potential future GNU Image Manipulation Program 3.0.0 release.

[Return to top](#contents)

## Long term plans {#long-term-plans}
We understand that the GNU Image Manipulation Program developers  may stop developing 2.10.x in the summer of 2021, and could focus all their efforts on 3.0.x before the end of 2021. [Source](http://libregraphicsworld.org/blog/entry/gimp-2-99-2-vs-2-10-which-one-do-you-pick).

After we have released Glimpse Image Editor 0.3.0, there will be no new feature updates. Instead we will provide smaller "micro" releases that provide bug-fixes, backports and security updates.

In July 2022 we will release Glimpse Image Editor 0.4.0 as a "sunset" release that informs users they should switch to Glimpse NX or the GNU I.M.P 3.0.x.

 We currently have no plans to re-base Glimpse Image Editor on the GNU I.M.P 3.0.x because we do not know precisely when it will be released, and we also want to focus our attention and resources on delivering [Glimpse NX](/about/#what-is-glimpse-nx) instead.
 
 [Return to top](#contents)