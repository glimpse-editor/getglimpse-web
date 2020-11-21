---
title: "A Year In Summary"
date: 2020-11-21T23:21:00+00:00
draft: false
---
We released Glimpse Image Editor 0.1.0 on 2019-11-21, so to commemorate the anniversary of our first release we have chosen to make this month's blog post all about reviewing our progress, celebrating our achievements, and exploring our plans for the future.

We would like to thank everyone that has contributed to the Glimpse project and supported us since we first started it on 2019-07-05. We know that the negative reactions we received from some parts of the [FOSS](https://en.wikipedia.org/wiki/Free_and_open-source_software) community in the first six months  after our project started did not make that easy, and we are grateful to everyone that still continues to put their faith in us and encourage our contributors to deliver what our users have asked for.

These are our headline achievements, and you can review the full breakdown with cited sources in this blog post:
- All primary objectives and most secondary objectives defined in August 2019 have been delivered as promised
- There have been at least 86000 downloads across three releases
- We have raised $500 USD for the GNU Image Manipulation Program developers
- We also have some very cool plans for the future.

Finally, this is your regular reminder that it has never been our goal to replace or supplant the GNU Image Manipulation Program. [More Information](/about/#do-you-intend-to-replace-the-gnu-image-manipulation-program)

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

We consider missing Python support on Windows a "Won't Fix" issue as [Python 2 is now end of life](https://www.python.org/doc/sunset-python-2/) and not including it seems to improve the application startup time. It was originally a bug in the upstream build documentation that we were unable to fix. [Source](https://gitlab.gnome.org/GNOME/gimp/-/issues/4286)

We also inherited regressions that broke compatibility with [Liquid Rescale](https://github.com/glimpse-editor/Glimpse/wiki/How-to-Install-the-Liquid-Rescale-Plugin) when we re-based on GNU Image Manipulation Program 2.10.18 for Glimpse Image Editor 0.2.0, but we intend to backport patches from 2.10.20 to fix that in 0.2.2. [Source](https://gitlab.gnome.org/GNOME/gimp/-/issues/4496)

At the present time we lack the capacity to [create a native macOS port](https://github.com/glimpse-editor/Glimpse/issues/402) or produce code changes that directly assist the GNU Image Manipulation Program developers. However, we are optimistic that [Glimpse NX](/about/#what-is-glimpse-nx) will deliver on those objectives instead because it is attracting more interest from potential contributors, and it will require us to port useful upstream components to [GTK4](https://gitlab.gnome.org/GNOME/gtk/-/milestones/1).

[Return to top](#contents)

## Download figures update {#download-figures-update}
All figures were correct on the day this blog post was published and sources have been provided so that you can independently verify them. Any **+** or **-** change is calculated from the previous figures published on 2020-07-21. [Source](posts/beta-testing-underway-for-0-2-0/)

If the figures are accurate then we believe that since 2020-07-21 then there has been some modest growth in the number of Linux users running Glimpse Image Editor, and we are starting to develop a smaller dedicated following on Windows. We are also pleased to see the software distributed from more third party sources than ever before.

We know that Glimpse Image Editor has been downloaded at least **86159** (+32134) times across all platforms, versions and download sources since the software was first released on 2019-11-22. A detailed breakdown is provided below, and the figures we have provided should be viewed as indicators only because we are relying on the accuracy of external tools.

We have deliberately not provided any estimates about the total size of our active user base because there is no universally agreed methodology for extrapolating that figure from download statistics. However, we have made some educated guesses about any discrepencies we spotted to lend context that you might find useful.

### Linux
There have been **11992** (-205) active users over the past month that have installed Glimpse Image Editor from the [the Snap Store](https://snapcraft.io/glimpse-editor/). These figures are only available through a private dashboard, so we have [provided a screenshot](/glimpse-snap-2020-07-21.png).

Glimpse Image Editor has been downloaded **35201** (+17173) times from [Flathub](https://flathub.org/apps/details/org.glimpse_editor.Glimpse) across all versions since it was first released on 2019-11-22, and there have been **20501** (+9145) recent requests for updates.

We use [a third-party tool](https://gitlab.com/ahayzen/flathub-api-stats-generator) to get Flathub statistics, and this is the command we run:
```
$ python3 main.py --report downloads_by_app --type data --output out.dat --report-args app-id=org.glimpse_editor.Glimpse
```

We also have download statistics for standalone Linux builds we provided on Github. [Source](https://somsubhra.com/github-release-stats/?username=glimpse-editor&repository=Glimpse)

- Standalone bundle flatpaks we provided for Glimpse Image Editor 0.2.0 have been downloaded **578** times since they were released on 2020-08-25.
- Distribution tarballs we provided for Glimpse Image Editor 0.1.2 have been downloaded **666** (+128) times since they were released on 2020-03-02.

We have omitted statistics for our [Linux AppImage](https://github.com/glimpse-editor/Glimpse/releases/tag/continuous), as that is pre-release software with a download counter that resets every time we make a change to the `dev-g210` branch. We also do not have the figures for other community-supported Linux download sources.

### Windows
We have combined download figures for both signed and unsigned MSI installers downloaded from Github. We did not count pre-release versions of the software. [Source](https://somsubhra.com/github-release-stats/?username=glimpse-editor&repository=Glimpse)

- Glimpse Image Editor 0.2.0 (x64 MSI) has been downloaded **6994** times from Github since its release on 2020-08-25. 
- Glimpse Image Editor 0.2.0 (x86 MSI) has been downloaded **3790** times from Github since its release on 2020-08-25.
- Glimpse Image Editor 0.1.2 (x86 MSI) has been downloaded **20899** (+2940) times from Github since its release on 2020-03-02.
- Glimpse Image Editor 0.1.0 (x86 MSI) has been downloaded **5134** (+54) times from Github since its release on 2019-11-21.

There are also unofficial third-party download sources for Windows users that provide download statistics:

* **436** downloads from [Chocolatey](https://chocolatey.org/packages/glimpse/)
* **213** (+95) downloads from [Softpedia](https://www.softpedia.com/dyn-search.php?search_term=glimpse)
* **256** (+151) downloads from [SourceForge](https://sourceforge.net/projects/glimpse-image-editor/files/stats/timeline)

Unfortunately we cannot access download statistics from [WinGet](https://winget.run/pkg/Glimpse/Glimpse). Work is also still ongoing to bring Glimpse Image Editor to the [Scoop](https://scoop.sh/) package manager: [#65](https://github.com/glimpse-editor/Glimpse/issues/65)

[Return to top](#contents)

## Financial summary {#financial-summary}
At the time this blog was published, our balance [on Open Collective](https://opencollective.com/glimpse) was $642.22 USD. If you subtract the total expenditure from the total income, you will arrive at that figure. 

The governance team's current policy is to keep the Glimpse project's balance over $500 USD to ensure its ongoing financial security. That balance is held by a 501(c) charity called Open Collective, and our project is strictly not-for-profit. [More Information](https://glimpse-editor.github.io/about/#why-do-you-need-monetary-donations)

Figures on the Open Collective website begin in September 2019, but for completeness we have provided additional information about the amount we received through Patreon and how much it cost us to migrate those funds to Open Collective. All expense claims and invoiced spending has been published publicly.

### Income
- Donations received via Open Collective: $1348.68 USD
- Donations received via Patreon: $627 USD*
- Donations received via Github Sponsors: $156.95 USD

**Total**: $2132.63 USD

### Expenditure
- Donations to the GNU Image Manipulation Program developers: $500 USD
- Assorted fees charged by donation platforms & payment processors: $357.94 USD
- Server hosting (Website, Wiki, Jenkins, Gitea, Proxy): $326.89 USD
- Fees to disburse funds from Patreon & then donate as Incognito to Open Collective (via PayPal): $155.80 USD*
- Donations to [Mastodon.art](https://mastodon.art/@glimpse) for hosting our fediverse account: $54 USD
- Commissioned artist for Glimpse logo: $50 USD
- Web domains (getglimpse.app): $45.78 USD

**Total**: $1490.41 USD

### Clarifications
We closed our Patreon account in December 2019 because of an online disinformation campaign organised by trolls to spread lies about our project and contributors for several months. 

We chose to combat the baseless accusations being made by providing maximum transparency to our donors via [an Open Collective campaign](https://opencollective.com/glimpse) we started in September 2019. We believe that this approach, together with an independently verifiable record of us delivering on our promises, provides a strong rebuttal and demonstrates our good faith. [More Information](https://glimpse-editor.github.io/about/#are-you-scamming-me)

Figures related to the four transfers of funds from Patreon to Open Collective have been marked with an asterisk (*). On Open Collective it looks like a single incognito user has donated $514 USD, because you are viewing the figure **after** various Patreon and PayPal fees were charged but **before** Open Collective fees had been charged on the transferred amount.

We created [a Github Sponsors campaign](https://github.com/sponsors/glimpse-editor) in April 2020 because it could be linked to Open Collective. The first automatic transfers via Stripe started arriving in July 2020.

We do not track how many Glimpse Image Editor users donate directly to the GNU Image Manipulation Program via [their donation page](https://www.gimp.org/donating/), but we encourage them to do so whenever we can to support a project we still rely on as a downstream fork.

The glimpse-editor.org and glimpse-editor.com web domains were bought for us by melody. We are also grateful to renowned security researcher Cynthia Revström for signing our Windows installers with her own EV certificate.

[Return to top](#contents)

## Goals for 2021 {#goals-for-2021}
We have provided two great blog posts that lay out our plans for the coming year: [First Steps Towards the Future](/posts/first-steps-towards-the-future/) and [An Exciting Year Ahead](/posts/an-exciting-second-year-ahead/).

In addition, these are our goals for 2021:
- Maintain primary/secondary objectives and deliver tertiary objectives in two new releases
- Reach at least 130000 downloads for Glimpse Image Editor across all five releases
- Raise another $500 USD for the GNU Image Manipulation Program developers (reaching $1000 USD in total since the project started)
- Deliver the first alpha quality Glimpse NX release

We would also like to make it clear that Glimpse Image Editor 0.2.2 will be the final release where we produce Windows installers for both the x64 and x86 architectures. We plan to deprecate support for x86 versions of Windows in July 2021. [More information](https://github.com/glimpse-editor/Glimpse/wiki/Supported-Platform-Versions-%28Windows%29)

Glimpse Image Editor 0.3.0 is likely to break binary compatibility with third-party plugins and existing packaging processes so we can resolve conflicts in Linux/BSD package managers. [#7](https://github.com/glimpse-editor/Glimpse/issues/7) 

To mitigate that problem, we plan to start maintaining patched versions of third-party plugins in full compliance with their original licenses. The practical benefit for users should be fewer compatibility problems ongoing and more third-party plugins included with Glimpse Image Editor by default in future releases. [#414](https://github.com/glimpse-editor/Glimpse/issues/414) [#441](https://github.com/glimpse-editor/Glimpse/issues/441) [#465](https://github.com/glimpse-editor/Glimpse/issues/465) [#466](https://github.com/glimpse-editor/Glimpse/issues/466) [#467](https://github.com/glimpse-editor/Glimpse/issues/467)

Finally, we have dropped the "Glimpse Redux" initiative. As laid out in the next section, we have chosen to focus our attention and resources on [Glimpse NX](/about/#what-is-glimpse-nx) instead of porting our changes to a potential future GNU Image Manipulation Program 3.0.0 release.

[Return to top](#contents)

## Long term plans {#long-term-plans}
As with all long term plans, anything we say in this section is subject to change based on what happens upstream, feedback we receive from our users, how good we are at attracting/retaining contributors and how far we progress with developing [Glimpse NX](/about/#what-is-glimpse-nx).

We understand that the GNU Image Manipulation Program developers  could stop developing 2.10.x as soon as the middle of next year, and may then focus all of their efforts on 3.0.x before the end of 2021. [Source](http://libregraphicsworld.org/blog/entry/gimp-2-99-2-vs-2-10-which-one-do-you-pick).

We currently have no plans to re-base Glimpse Image Editor on the GNU I.M.P 3.0.x because we do not know precisely when it will be released. We also want to focus our attention and resources on delivering Glimpse NX instead because that project will deliver more of our objectives, is already attracting more contributor interest and should be more maintainable for us over the long term.

As a result of those things, it is likely that we will eventually phase out Glimpse Image Editor in favour of [Glimpse NX](/about/#what-is-glimpse-nx), which will hopefully be ready with its first stable release and supplementary migration tools in 2022.

We will provide more information about our switch from Glimpse Image Editor to Glimpse NX as we start to confirm our plans nearer the time.
 
 [Return to top](#contents)