---
title: "A Year In Summary"
date: 2020-11-07T15:00:00+00:00
draft: false
---
**DO NOT PUBLISH. FIGURES WILL NEED TO UPDATED RIGHT UP UNTIL PUBLISH ON 2020-11-21**
(Figures in current draft calculated on 2020-11-07)

TODO: Intro section here that summarises our achievements through the year.

## Contents {#contents}
- [Download figures update](#download-figures-update)
- [Project finances summary](#project-finances-summary)
- [Contribution statistics](#contribution-statistics)

## Download figures update {#download-figures-update}
All figures were correct on the day this blog post was published and sources have been provided so that you can independently verify them. Any **+** or **-** change is calculated from the previous figures published on 2020-07-21. [Source](posts/beta-testing-underway-for-0-2-0/)

If the figures are accurate then we believe that since 2020-07-21... **TBD Conclusion**.

We know that Glimpse Image Editor has been downloaded at least **83622** (+29597) times across all platforms, versions and download sources since the software was first released on 2019-11-22. A detailed breakdown is provided below.

We have deliberately not provided any estimates about the total size of our active user base because there is no universally agreed methodology for extrapolating that figure from download statistics. However, we have made some educated guesses about any discrepencies we spotted to lend context that you might find useful.

### Linux
There are currently **12236** (+39) active weekly devices that have installed Glimpse Image Editor through [the Snap Store](https://snapcraft.io/glimpse-editor/). These figures are only available through a private dashboard, so we have [provided a screenshot](/glimpse-snap-2020-07-21.png). **TODO: Update Screenshot**

Glimpse Image Editor has been downloaded **34103** (+16075) times from [Flathub](https://flathub.org/apps/details/org.glimpse_editor.Glimpse) across all versions since it was first released on 2019-11-22, and there have been **20209** (+8853) recent requests for updates. 

We believe the true rise in active installations on Flathub is around half the stated change, because we released 0.2.0 twice; Once with GNOME Platform 3.36, and then a second time with GNOME Platform 3.38.

We use [a third-party tool](https://gitlab.com/ahayzen/flathub-api-stats-generator) to get Flathub statistics, and this is the command we run: 
```
$ python3 main.py --report downloads_by_app --type data --output out.dat --report-args app-id=org.glimpse_editor.Glimpse
```

We also have download statistics for standalone Linux builds we provided on Github. [Source](https://somsubhra.com/github-release-stats/?username=glimpse-editor&repository=Glimpse)

- Standalone bundle flatpaks we provided for Glimpse Image Editor 0.2.0 have been downloaded **539** times since they were released on 2020-08-25.
- Distribution tarballs we provided for Glimpse Image Editor 0.1.2 have been downloaded **563** (+25) times since they were released on 2020-03-02.

We have omitted statistics for the Linux AppImage, as that is pre-release software with a download counter that resets every time we make a change to the `dev-g210` branch. We also do not have the figures for other community-supported Linux download sources.

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

Unfortunately we cannot access download statisics from [WinGet](https://winget.run/pkg/Glimpse/Glimpse). Work is also still ongoing to bring Glimpse Image Editor to the [Scoop](https://scoop.sh/) package manager: [#65](https://github.com/glimpse-editor/Glimpse/issues/65)

We are pleased with the download figures for Glimpse Image Editor 0.2.0 on Windows so far. Reaching almost 10000 downloads within three months suggests we now have a dedicated user base on the platform that is gradually migrating across from Glimpse Image Editor 0.1.2.

[Return to top](#contents)

## Project finances summary {#project-finances-summary}

### Finances November 2019 to November 2020
TODO. Information will come from [our Open Collective profile](https://opencollective.com/glimpse).

### Finances July 2019 to October 2019
For completeness, we have also provided figures from the first four months our project existed.

TODO.

[Return to top](#contents)

## Contribution statistics {#contribution-statistics}
TODO. Information will likely come from Github stats, but would need to filter out upstream stats brought in due to imported commit history.

[Return to top](#contents)
