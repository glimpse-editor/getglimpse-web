---
title: "About (FAQs)"
date: 2020-10-09T21:10:00+01:00
draft: false
menu: "main"
---
## Contents {#contents}
Glimpse Image Editor 0.2.0 is an open source image editing program based on the GNU Image Manipulation Program 2.10.18. You can read more about our development priorities and our target userbase here: https://github.com/glimpse-editor/Glimpse/wiki/Development-Priorities

Glimpse NX aims to create a lightweight new interface for pre-existing GNU Image Manipulation Program libraries and frameworks. We will provide more details about that project in coming months.

The goal of both projects is to experiment with new ideas and expand the use of free/libre and open source software.

### Introduction
- [What is the correct name for your project?](#what-is-the-correct-name-for-your-project)
- [What is Glimpse Image Editor?](#what-is-glimpse-image-editor)
- [What is Glimpse NX?](#what-is-glimpse-nx)
- [What is Glimpse Redux?](#what-is-glimpse-redux)
- [What is wrong with the "GIMP" name?](#what-is-wrong-with-the-gimp-name)
- [Are there any disabled people involved with the project?](#are-there-any-disabled-people-involved-with-the-project)
- [Why are you forking?](#why-are-you-forking)
- [Do you intend to replace the GNU Image Manipulation Program?](#do-you-intend-to-replace-the-gnu-image-manipulation-program)
- [Why do you call yourself "open source"?](#why-do-you-call-yourself-open-source)
- [Did you know that name is used elsewhere?](#did-you-know-that-name-is-used-elsewhere)
- [What if I find the word "Glimpse" offensive?](#what-if-i-find-the-word-glimpse-offensive)

### Technical Questions
- [How does your release numbering work?](#how-does-your-release-numbering-work)
- [Which operating systems do you support?](#which-operating-systems-do-you-support)
- [Who signs the Windows installer?](#who-signs-the-windows-installer)
- [Can I install Glimpse and GNU Image Manipulation Program on the same machine?](#can-i-install-glimpse-and-gnu-image-manipulation-program-on-the-same-machine)
- [Are you going to publish this for my favorite Linux distribution?](#are-you-going-to-publish-this-for-my-favorite-linux-distribution)
- [Will you support BSD, Haiku, Solaris or other UNIX platforms?](#will-you-support-bsd-haiku-solaris-or-other-unix-platforms)
- [Why are you using Github instead of Gitlab?](#why-are-you-using-github-instead-of-gitlab)
- [Could you just run "find and replace" to fix the name?](#could-you-just-run-find-and-replace-to-fix-the-name)
- [When are you going to implement the bug-fix or feature I asked for?](#when-are-you-going-to-implement-the-feature-i-asked-for)
- [Can you make Glimpse look like Adobe Photoshop?](#can-you-make-glimpse-look-like-adobe-photoshop)
- [How do I install third-party plugins?](#how-do-i-install-third-party-plugins)
- [How do I migrate my settings from Glimpse 0.1.x to 0.2.x?](#how-do-i-migrate-my-settings-from-glimpse-0-1-x-to-0-2-x)

### Money Matters
- [Why do you need monetary donations?](#why-do-you-need-monetary-donations)
- [Do you plan to sell Glimpse Image Editor?](#do-you-plan-to-sell-glimpse-image-editor)
- [How much do you earn from this project?](#how-much-do-you-earn-from-this-project)
- [Are you scamming me?](#are-you-scamming-me)
- [Will you adopt a cryptocurrency or blockchain reward system?](#will-you-adopt-a-cryptocurrency-or-blockchain-reward-system)

### Project Governance
- [Where is the Glimpse code of conduct?](#where-is-the-glimpse-code-of-conduct)
- [How does your project govern itself?](#how-does-this-project-govern-itself)
- [What are all the Matrix channels for?](#what-are-all-the-matrix-channels-for)
- [How do I stay up-to-date with this project?](#how-do-i-stay-up-to-date-with-this-project)
- [How do I contribute to this project?](#how-do-i-contribute-to-this-project)

---

## What is the correct name for your project? {#what-is-the-correct-name-for-your-project}
The open source software we produce is called "Glimpse Image Editor", but we sometimes shorten that to just "Glimpse". We refer to our governance structure, core contributors and participants on our public Matrix channel as "the Glimpse project". We often call our social media followers, donors and end users "the Glimpse Community".

Glimpse NX is a separate project we plan to start soon where we will create a lightweight new interface for pre-existing GNU Image Manipulation Program libraries and frameworks. You may sometimes see it referred to as "the rewrite". We will provide more information about that project in coming weeks and months.

If you are a blogger or a member of the technology industry press, we do not yet have branding guidelines in place. However we have provided screenshots, our branding assets and instructions for their basic usage here: https://github.com/glimpse-editor/branding. You may also contact us directly [by email](mailto:glimpse.editor@icloud.com) for further information about the project.

[Return to top](#contents)

## What is Glimpse Image Editor? {#what-is-glimpse-image-editor}
Glimpse Image Editor is a "fork" or "respin" of the [GNU Image Manipulation Program](https://www.gimp.org/), and it is also a free/libre and open source image editing application.

This project was originally started due to long-standing disagreements between the GNU Image Manipulation Program developers and some of the software's users about who the target audience is, the priority of usability/accessibility changes, and whether it is still appropriate to call a 25 year old software program "the Gimp" as a joke.

Forking (or "remixing") an existing software program is a long-established way to resolve such disputes. In fact, the [GNU manifesto](https://www.gnu.org/gnu/manifesto.en.html) encourages users to modify the applications they use to better suit their needs so long as they are also respectful to the community and make those changes available to others.

While there was some controversy surrounding our project in the months after we first started it in July 2019, we believe that a long and independently-verifiable record of positive actions towards the GNU Image Manipulation Program developers and the wider free/libre and open source communities make our position and positive intentions clear.

[Return to top](#contents)

## What is Glimpse NX? {#what-is-glimpse-nx}
Glimpse NX will be a free/libre software application using [GNOME](https://www.gnome.org/) technologies that provides a more lightweight and accessible user interface for the same underlying components that the GNU Image Manipulation Program uses. It will also be ported to Windows and MacOS.

We are still deciding which programming language to use, but [Rust](https://www.rust-lang.org/) is the most likely candidate. As we will be using components that are licensed under the [GNU LGPLv3](https://www.gnu.org/licenses/lgpl-3.0.html), we expect the project itself will be provided under the GNU General Public License v3 or a similar compatible license.

Further information for this exciting new spin-off project will be provided in coming months.

As stated in previous blog posts, we did originally consider the possibility of creating a new bespoke cross-platform user interface toolkit and then writing an entirely new BSD-licensed program based on it with the more estoteric [D](https://dlang.org/) programming language. A group of contributors investigated that solution, but after six months of incubation we collectively agreed that such an ambitious project cannot be delivered in a two year timeframe with the resources we have available.

[Return to top](#contents)

## What is Glimpse Redux? {#what-is-glimpse-redux}
"Glimpse Redux" is the codename we are using for the preparation work we are doing for an eventual re-fork on the (still to be released) GNU Image Manipulation Program 3.0.

Currently Glimpse Image Editor is based on GNU Image Manipulation Program 2.10.18, and our stable releases will continue to be based on upstream 2.10.x releases for as long as the upstream project continues to produce them. We will not produce formal releases for our fork of the GNU Image Manipulation Program 3.0 code base until after it has been released by the upstream developers first.

The reason why we need to work on this effort separately is because the GNU Image Manipulation Program 3.0 uses a different technology stack and has a slightly different featureset. It is also highly likely that 3.0 will deprecate most existing plugins and break many of the features we have already implemented.

So that our own users do not have to wait 12+ months for us to catch up after the GNU Image Manipulation Program 3.0 is released, we intend to create a new Github repository that follows the correct upstream branch so that we can gradually reimplement our customizations on that code ahead of time. When the GNU Image Manipulation 3.0 is eventually released, we will plan and schedule a smooth transition from the existing Glimpse Image Editor code to the Glimpse Redux code.

Initially the Github repository for Glimpse Redux will only be visible to our core contributors. Once we have produced the appropriate developer documentation and working reproducible builds, we will make the repository visible to the public so that we can open up this effort to third-party plugin developers and community software packagers.

To confirm, we will not be renaming Glimpse Image Editor. "Glimpse Redux" is a temporary codename we are using for the preparation work described above.

[Return to top](#contents)

## What is wrong with the "GIMP" name? {#what-is-wrong-with-the-gimp-name}
It was originally chosen by Spencer Kimball and Peter Mattis as a joke reference to a questionable scene in an 18 certificate movie called "Pulp Fiction". The word "gimp" also has [other meanings](https://www.merriam-webster.com/dictionary/gimp) that may be considered ableist.

While we cannot provide a solution that resolves the wider societal discussion about what is considered appropriate and "politically correct" in every situation, we can provide an alternative option that helps people who are offended or made uncomfortable by the name, and assist open source advocates that encounter barriers when they recommend the GNU Image Manipulation Program to friends, family, coworkers and employers.

Our project also offers a more constructive path forward to people that have become frustrated by the GNU Image Manipulation Program developers' [long-standing decision](https://www.gimp.org/docs/userfaq.html#i-dont-like-the-name-gimp-will-you-change-it) to not change the name of their software. That means fewer people yelling at each other on social media, and more people working on the code.

[Return to top](#contents)

## Are there any disabled people involved with the project? {#are-there-any-disabled-people-involved-with-the-project}
Yes. However, our contributors are not under any obligation to disclose their status as a disabled person or the nature of their impairment(s) to you, as that is private medical information.

We encourage free/libre and open source software developers **of all political stripes** to better prioritize fixing accessibility and usability problems, because seemingly small changes can make a big difference and it is not reasonable to constantly expect disabled people to fight you for them first.

While there are many improvements we all need to make on the legacy systems we maintain, even limited efforts made in good faith can send a positive message that disabled people are welcome in our community and their needs matter to us.

[Return to top](#contents)

## Why are you forking? {#why-are-you-forking}
We want to expand the use of free/libre and open source software, and we think we can make some cool changes to the already excellent functionality in the GNU Image Manipulation Program to achieve that objective.

You can read more about our development priorities and our target userbase here: https://github.com/glimpse-editor/Glimpse/wiki/Development-Priorities

[Return to top](#contents)

## Do you intend to replace the GNU Image Manipulation Program? {#do-you-intend-to-replace-the-gnu-image-manipulation-program}
No, this project does not intend to replace or supplant the GNU Image Manipulation Program. We aim to expand the userbase for that software, and modifying the code to make it more appealing to a broader audience is already helping us to achieve that objective.

The Glimpse project is run entirely by passionate enthusiasts. Development on the GNU Image Manipulation Program has continued as normal with the same core group of developers that were working on it before, and their progress has not been hindered by this project at all.

We also frequently link to the GNU Image Manipulation Program developers' [donations page](https://www.gimp.org/donating/) throughout our documentation, and you can review the donations we periodically make ourselves here: https://opencollective.com/glimpse/expenses?tag=donation

We anticipate in the coming months and years that Glimpse will be a place where people can experiment with fixes that upstream may not have had the resources to work on and new ideas that upstream may have felt unable or unwilling to try for legacy reasons. You can read more about our [development priorities](https://github.com/glimpse-editor/Glimpse/wiki/Development-Priorities) on the project wiki.

Whenever we make improvements or spot a bug, we discuss them with the GNU Image Manipulation Program developers directly on [their IRC channel](https://www.gimp.org/irc.html). The biggest wins have been on Windows, where we helped the upstream developers significantly reduce hard disk usage on that platform, and we make them aware of any native build problems that we spot on [MSYS2](https://www.msys2.org/).

[Return to top](#contents)

## Why do you call yourself "open source"? {#why-do-you-call-yourself-open-source}
Glimpse Image Editor is licensed under the [GNU General Public License version 3](https://www.gnu.org/licenses/gpl-3.0.en.html), and that is an [Open Source Initiative](https://opensource.org/) approved "open source" license.

You can read the full definition for what "open source" means and how that impacts your rights as a user here: https://opensource.org/docs/osd

You can also review the GNU definition of "free software" here: https://www.gnu.org/philosophy/free-sw.html

We standardize on the term "open source" to make it clear to end users who may not be familiar with the GNU-sanctioned definition of "free software" that we do not follow the same "freeware", "shareware" or "adware" models that they usually encounter in commercial app stores for Windows, macOS and mobile platforms.

[Return to top](#contents)

## Did you know that name is used elsewhere? {#did-you-know-that-name-is-used-elsewhere}
We are aware of a number of other unrelated projects called "Glimpse". We have made changes based on feedback from our critics such as changing our website's domain name and defining "Glimpse" as a shortened version of "Glimpse Image Editor".

The project's current stance is that while we are theoretically open to changing our name, there is very limited support in favor of actually doing so. We granted our critics time to find an alternative name that addresses the concerns they raised, fulfils our project's requirements and enjoys popular support. Even with three months and our assistance they were not able to do so, so we consider the matter closed for the time being.

See ["How does your project govern itself?"](#how-does-this-project-govern-itself) for more details about why we now limit discussion about this topic on our Matrix channels.

[Return to top](#contents)

## What if I find the word "Glimpse" offensive? {#what-if-i-find-the-word-glimpse-offensive}
That seems unlikely given we checked its meaning in every known language, but if you have a legitimate concern then let us know.

If you are offended by the fact we forked a project, we suggest you continue using the [GNU Image Manipulation Program](https://www.gimp.org) instead of annoying our contributors and making more work for our moderators.

[Return to top](#contents)

## How does your release numbering work? {#how-does-your-release-numbering-work}
Glimpse Image Editor 0.1.0 and 0.1.2 were based on the GNU Image Manipulation Program 2.10.12. These initial releases made minor cosmetic changes and helped us learn how to build and package the application.

Glimpse Image Editor 0.2.0 is based on the GNU Image Manipulation Program 2.10.18, and it introduces additional plugins and functional changes. All 0.2.x releases will add our changes, back port useful functionality and update key dependencies on the same 2.10.18 base.

We intend to continue providing "maintenance updates" with patches and updated dependencies for at least a year after each 0.x.0 release. We aim to produce one major release every six months.

"Beta test" and "Stable" release versions always end in an even number. Odd numbered versions are "Unstable" builds created from our development branch.

Glimpse Image Editor 1.0.0 is currently reserved in case we decide to fork the GNU Image Manipulation Program 3.x.

Glimpse NX (the interface rewrite) will have its own version scheme.

[Return to top](#contents)

## Which operating systems do you support? {#which-operating-systems-do-you-support}
We support systems running Windows 7 or newer, and modern variants of Linux.

Unfortunately Glimpse Image Editor is not supported on MacOS. We recommend either running the Windows version in a virtualized environment or sticking with [the GNU Image Manipulation Program](https://www.gimp.org/downloads/). 

You may also be interested in trying [Seashore](https://apps.apple.com/us/app/seashore/id1448648921?mt=12), an older fork of the GNU Image Manipulation Program designed specifically for MacOS. While it does have fewer features, it may still be suitable for your intended use case.

[Return to top](#contents)

## Who signs the Windows installer? {#who-signs-the-windows-installer}
[Cynthia Revström](https://cynthia.re/), a renowned security researcher. She signs our Windows installers with an Extended Validation (EV) code signing certificate belonging to a registered company called [Qs.nu](https://qs.nu/).

If we do not sign our MSI installer then potential users can run into a number of problems. Certain web browsers block the download of "untrusted" files, Windows SmartScreen creates error screens that non-technical people find difficult to override, and anti-virus programs incorrectly flagging Glimpse Image Editor as "malware" can interfere with the installation process and normal operation of the program.

We initially tried a self-signed certificate, but that did not resolve the problem. The Glimpse project is not a registered company and cannot afford to reimburse individuals for certificate authority notarization requirements, so we cannot provide our own code signing certificate. As a result we rely on a trusted individual to voluntarily sign each MSI installer we release on our behalf.

[Return to top](#contents)

## Can I install Glimpse and GNU Image Manipulation Program on the same machine? {#can-i-install-glimpse-and-gnu-image-manipulation-program-on-the-same-machine}
On Windows, you can safely install and run both applications at the same time.

On Linux, the Flatpak and Snapcraft builds that we support and maintain are fully self-contained and should not interfere with any installed versions of the GNU Image Manipulation Program. If you discover that is not the case on your system, please [report it as a bug](https://github.com/glimpse-editor/Glimpse/issues).

If you are using a Linux build from a third party source that we do not directly support (such as AUR or your distribution's package repositories) then it is unlikely because there may be package and file name conflicts. You should ask the people responsible for maintaining those packages for confirmation and any help you might need.

[Return to top](#contents)

## Are you going to publish this for my favorite Linux distribution? {#are-you-going-to-publish-this-for-my-favorite-linux-distribution}
You can see all the Linux installation methods we are aware of for Glimpse Image Editor on [our downloads page](/downloads/).

We intend to provide our own directly-supported AppImage builds very soon. You can track the progress here: [#108](https://github.com/glimpse-editor/Glimpse/issues/108).

We already publish builds on [Flathub](https://flathub.org/apps/details/org.glimpse_editor.Glimpse) and [Snapcraft](https://snapcraft.io/glimpse-editor).

All other installation mechanisms for Linux are considered "community supported". That means we do not have any say about how they are built, packaged or maintained. We link to them, but if you raise bug tickets with us we may direct you back to those sources instead.

At the request of package maintainers, we have run `make dist` against source tarballs from Glimpse Image Editor 0.1.2 onwards.

[Return to top](#contents)

## Will you support BSD, Haiku, Solaris or other UNIX platforms? {#will-you-support-bsd-haiku-solaris-or-other-unix-platforms}
Other UNIX systems are treated the same way as any individual Linux distribution. We do not directly support the individual packaging formats and publishing platforms for each variant of UNIX because we don't have the knowledge or resources to support and maintain them all.

However, we will accept code fixes that enhance UNIX compatibility and will assist any third party package maintainers that want to port Glimpse Image Editor to operating systems like BSD, Haiku, Solaris and other UNIX variants.

[Return to top](#contents)

## When are you going to implement the bug-fix or feature I asked for? {#when-are-you-going-to-implement-the-feature-i-asked-for}
The first place to check is our [Github Issues list](https://github.com/glimpse-editor/Glimpse/issues).

We aim to tag each bug and feature request to a [release milestone](https://github.com/glimpse-editor/Glimpse/milestones) so that you have a rough idea of when we think we can feasibly deliver the functionality. Those estimates are subject to change based on our shifting project priorities and any technical hurdles we come across. We also do our best to add regular comments to every issue so that you can see the most up-to-date information about them.

If the functionality you want is not listed, the next place to check is [the roadmap page](https://wiki.gimp.org/wiki/Roadmap) for the GNU Image Manipulation Program. Because that project has more contributors and resources than we do as a downstream fork, we are normally a release or two behind them. If they are implementing a fix or change though, then we will eventually inherit it.

Finally, if the change you want isn't requested in either place then feel free to raise it as a bug or a feature request! Alternatively you can contact us by using the links on our [Contribute](/contribute/) page.

[Return to top](#contents)

## Can you make Glimpse look like Adobe Photoshop? {#can-you-make-glimpse-look-like-adobe-photoshop}
Technically yes, but we are not going to do that. If you still want to do it though, try the [PhotoGIMP](https://github.com/glimpse-editor/Glimpse/wiki/How-to-Install-the-PhotoGIMP-Plugin) plugin.

We understand why it is important for Glimpse Image Editor to feel familiar to users of existing image editing applications, but we also think it's important for us to do our own thing. Not only will that lead to more new and interesting ideas, it should also avoid any potential legal problems.

The developers of the GNU Image Manipulation Program have the same stance on this, and they go into much more detail on [their FAQ page](https://www.gimp.org/docs/userfaq.html#i-dont-like-gimps-user-interface-why-cant-you-just-copy-adobe-photoshop).

[Return to top](#contents)

## Why are you using Github instead of Gitlab? {#why-are-you-using-github-instead-of-gitlab}
That was a choice made early on for practical reasons such as project discoverability, ease-of-use, user familiarity and cost. We also support [Github Sponsors](https://github.com/sponsors/glimpse-editor), rely on [Github Actions](https://github.com/glimpse-editor/Glimpse/actions) for automated builds, and use their servers as a [release mirror](https://github.com/glimpse-editor/Glimpse/releases).

As a project we are aware that some people have ethical concerns about using Github, and that other projects appear above us in [the search results](https://github.com/search?utf8=%E2%9C%93&q=glimpse&type=). For those reasons we periodically discuss how our contributors feel about using it, as well as the merits and drawbacks of potential alternatives.

There are no plans to move our code, and we believe the time and resources required to do so at the present time significantly outweigh the benefits. However, we are open to potentially mirroring our project to other platforms if that can be balanced against the maintenance burden of doing so.

[Return to top](#contents)

## Could you just run "find and replace" to fix the name? {#could-you-just-run-find-and-replace-to-fix-the-name}

We could, but that would completely destroy plug-in compatibility and break the upstream subcomponents on which we rely. That would also cause serious problems with all the build scripts and be very time-consuming to fix.

To preserve compatibility we had to maintain existing file names, variable names, constants, class names, methods and APIs. This meant we had to provide our own files, variables and constants, then identify where we wanted to use them, swap in those values wherever that did not break compatibility, and find a suitable replacement wherever we referred to upstream code that we had not modified (we settled on "GNU I.M.P"). That cannot be achieved using find-and-replace tools or regular expressions alone.

In addition to changing the name we also wanted to change the project logo. We commissioned an artist to do that for us, and subsequently had to make code fixes to the application to swap in our own art assets.

Finally, we also had to ensure that our changes were applied appropriately in the existing translation files and did not break the automated mechanisms in the build systems that keep them up-to-date.

In short, it is not easy to rebrand the GNU Image Manipulation Program. Similarly, the reason why this project is not just "one man and his Github repository" is because we do have other objectives and intend to create software that other people actually want to use.

[Return to top](#contents)

## How do I install third-party plugins? {#how-do-i-install-third-party-plugins}
We provide a full listing for how to install various third-party plugins on this wiki page: https://github.com/glimpse-editor/Glimpse/wiki#third-party-plugin-installation-guides

If there is a third party plugin you would like us to support better, feel free to raise an issue on our Github project: https://github.com/glimpse-editor/Glimpse/issues

[Return to top](#contents)

## How do I migrate my settings from Glimpse 0.1.x to 0.2.x? {#how-do-i-migrate-my-settings-from-glimpse-0-1-x-to-0-2-x}
Follow the instructions on our wiki for instructions on how to do that on [Windows](https://github.com/glimpse-editor/Glimpse/wiki/How-to-migrate-configuration-settings-from-Glimpse-Image-Editor-0.1.x-to-0.2.x-%28Windows%29) and [Linux](https://github.com/glimpse-editor/Glimpse/wiki/How-to-migrate-configuration-settings-from-Glimpse-Image-Editor-0.1.x-to-0.2.x-%28Linux%29).

[Return to top](#contents)

## Why do you need monetary donations? {#why-do-you-need-monetary-donations}
Just like many other free/libre and open source software projects we need to host the collaboration tools we use to develop and share the project. We have to purchase domain names, cloud servers, code signing certificates and subscriptions from service providers to make this project a success. In addition we also intend to pay the artists we commission for the re-brand, market our software, and eventually help our contributors represent us at conferences.

If you would like to donate some money to Glimpse project, you can do so by donating on [Open Collective](https://opencollective.com/glimpse). Our [Github Sponsors](https://github.com/sponsors/glimpse-editor) page is directly linked to our Open Collective profile. 

We also encourage those who want to support the GNU Image Manipulation Program to use [their donation page](https://www.gimp.org/donating/) to do so. We also pass along a portion of our own donations upstream periodically: https://opencollective.com/glimpse/expenses?tag=donation

[Return to top](#contents)

## Do you plan to sell Glimpse Image Editor? {#do-you-plan-to-sell-glimpse-image-editor}
No. Glimpse Image Editor is an open source application, and we have no plans to sell copies of the software. The same will also apply to Glimpse NX.

If that policy ever changes, it will go through the usual governance channels for this project, and our community will be consulted about it first. In practice, there is little or no support within the Glimpse project to start charging for copies of the software, so it is extremely unlikely to ever happen.

As for the project itself, we have not built a formal organization or legal entity around it. We are a group of volunteers that share the same online infrastructure and follow mutually agreed procedures.

[Return to top](#contents)

## How much do you earn from this project? {#how-much-do-you-earn-from-this-project}
Nothing. This is a strictly not-for-profit venture. Any money that we do not use to cover our own costs is [eventually passed along](https://opencollective.com/glimpse/expenses?tag=donation) to the GNU Image Manipulation Program developers. 

[Return to top](#contents)

## Are you scamming me? {#are-you-scamming-me}
No. Unfortunately there are people on the Internet who disagree with our project existing for political reasons, and in the absence of any reasonable arguments against what we are doing, some of them have tried to smear the Glimpse project and our contributors with false accusations.

To determine for yourself if we have delivered on the objectives we have set out, you can compare your current experience of the software against our [Development Priorities](https://github.com/glimpse-editor/Glimpse/wiki/Development-Priorities), the `NEWS` file provided with [the source code](https://github.com/glimpse-editor/Glimpse), and the release notes we produce on [our blog](/posts/).

You can also review how much we have received in donations and the ways we have spent that money on [our Open Collective profile](https://opencollective.com/glimpse). Open Collective is a 501(c) charity based in the United States, and they collect all donations on our behalf. We cannot access that money without raising an invoice for work or providing receipted evidence of an expense. Open Collective automatically publishes records of every donation we receive and expense claim we file publicly, and in real time. 

Our [Github Sponsors](https://github.com/sponsors/glimpse-editor) page is directly linked to our Open Collective profile via [Stripe](https://stripe.com/), so all donations received from that channel are also collected and recorded by Open Collective without our intervention.

**The Glimpse project is strictly not-for-profit, and we periodically donate surplus funds to the GNU Image Manipulation Program developers**. You can review those donations here: https://opencollective.com/glimpse/expenses?tag=donation

It is also our policy to provide a link to the [GNU Image Manipulation Program donation page](https://www.gimp.org/donating/) whenever we provide links to our own donation page so that it is clear to prospective donors that there are two separate projects. 

We also state wherever possible that Glimpse Image Editor is based on the GNU Image Manipulation Program, and clarify which version Glimpse Image Editor is based on. You can review the source code and compliance with applicable licenses on [our Github repository](https://github.com/glimpse-editor/Glimpse). We also display the names of upstream contributors in the **Help** > **About** > **Credits...** section of the software with a "(GNU I.M.P)" tag next to each applicable entry.

Whenever we provide download figures, we always provide links to the tools and websites we used so that (wherever possible) you can independently verify that the numbers we have published and our interpretation of them are correct.

Finally, you can review all of our previous blog posts to understand how our project has evolved and changed since it first started. Our project's website is also [kept under version control](https://github.com/glimpse-editor/getglimpse-web), so you can also review any changes that we have made to specific pages and posts.

While we doubt we will convince everyone, we hope that our commitment to transparency will help reassure those with an open mind that there is no sinister conspiracy, nefarious agenda, or evil plan. We are just a group of well-meaning volunteers trying to solve a problem in our spare time.

[Return to top](#contents)

## Will you adopt a cryptocurrency or blockchain reward system? {#will-you-adopt-a-cryptocurrency-or-blockchain-reward-system}
The current answer is "no", and we have no interest in our project being used as the experimental basis for such an initiative.

If you would like to make the case for this idea, ensure you have read our [Matrix channel rules](https://github.com/glimpse-editor/Glimpse/wiki/Good-Practices#membership-of-the-matrix-channel-is-a-privilege-not-a-right) and the [Code of Conduct](/code-of-conduct/) before proceeding. You should also read ["How does your project govern itself?"](#how-does-this-project-govern-itself) so you understand why our moderators may limit debate on some topics.

[Return to top](#contents)

## Where is the Glimpse code of conduct? {#where-is-the-glimpse-code-of-conduct}
You will find it on [this page](/code-of-conduct/). Our code of conduct is based on [the contributor covenant](https://www.contributor-covenant.org/) and will be developed and amended over time as the need arises. As this project spawned from [the fediverse](https://joinmastodon.org/) our experiences in that online space are going to inform the project's future governance and direction.

There is no [benevolent dictator for life](https://en.wikipedia.org/wiki/Benevolent_dictator_for_life) in the traditional sense for this fork because we believe in the merits of collective decision-making. They might sometimes take longer to make decisions, but a group is often less fallible, makes better-considered choices and reflects the will of the wider community more accurately than an individual.

That approach has worked well for us so far, and you can read more about our governance structure here: ["How does your project govern itself?"](#how-does-this-project-govern-itself)

We also want to make it clear that we value and encourage diverse representation in leadership positions within our community, and we believe that is the best way to enforce a code of conduct that protects all contributors and promotes wider participation. At this early stage our initial governance team is formed entirely of individuals from marginalized communities, and that makes our project [very atypical](https://opensource.com/article/17/9/diversity-and-inclusion-innovation). That emerged organically as a result of the project starting on [the fediverse](https://fediverse.party/).

We know how important it is to enact the right code of conduct and enforce the rules pro-actively. We want to promote a safe and inclusive environment, not a toxic one. If you have ideas to help us do that and want to get involved with this discussion then please join us in the project's communication channels.

[Return to top](#contents)

## How does your project govern itself? {#how-does-this-project-govern-itself}
The Glimpse Project is run by a self-appointed board called "the governance team", and it is currently made up of three members: [Bobby Moss](https://twitter.com/trechnex), [Christopher Davis](https://social.libre.fi/users/brainblasted), and [Luna](https://twitter.com/Clipsey5). Decisions are made with a majority vote after consultation with project contributors and any other interested parties.

Most day-to-day discussion for the forked code happens in the **#glimpse:matrix.org** (or "Glimpse Community") Matrix channel. Anyone can join so long as they comply with our [code of conduct](/code-of-conduct/) and [follow the rules](https://github.com/glimpse-editor/Glimpse/wiki/Good-Practices#membership-of-the-matrix-channel-is-a-privilege-not-a-right). This is where most of the decision-making happens, and our community has the opportunity to voice their opinions or share their domain-specific knowledge there.

We also host a separate [Discord server](https://discord.gg/hZhRceq) for Glimpse NX development and technical support queries. The governance team also discusses project moderation decisions in a private channel on that server. You can read the rules for joining this server's public channels on the `#rules-and-info` channel.

[Github Issues](https://github.com/glimpse-editor/Glimpse/issues) are used to track bug reports, suggestions and questions from the wider community, and items we have agreed as a project need action. Action items are allocated to a milestone to give an indication of their priority and likely timeline, but these are always provisional until the work is done.

No decision is ever set in stone and can be revisited if new information comes to light or there is enough support within the project to do so. The governance team will generally only block the re-opening of an issue or delay a decision if the discussion is becoming too heated or obstructs the day-to-day running of the project. The governance team also reserves the right to end a discussion if, after giving an idea a fair hearing, there is clearly a lack of support within the Glimpse project in favor of it being worked on or developed any further.

Finally, the project may from time to time run polls on social media to canvas opinion for specific issues if there is support for doing so. They are always non-binding and only intended to facilitate the existing decision-making process.

[Return to top](#contents)

## What are all the Matrix channels for? {#what-are-all-the-matrix-channels-for}
All of our channels are on matrix.org. You can get access to the invite-only channels by asking for it on the "Glimpse Community" channel.

- **#glimpse**: "Glimpse Community" channel that anyone can join so long as they [follow the rules](https://github.com/glimpse-editor/Glimpse/wiki/Good-Practices#membership-of-the-matrix-channel-is-a-privilege-not-a-right) and comply with our [code of conduct](/code-of-conduct/)
- **#glimpse-offtopic**: Off-topic chatter between well-known members of our community in a safe, welcoming environment.

There is also a separate [Discord server](https://discord.gg/hZhRceq) for our project moderation channels and the technical support queries. You can read their rules by following the links on the `#rules-and-info` channel.

[Return to top](#contents)

## How do I stay up-to-date with this project? {#how-do-i-stay-up-to-date-with-this-project}
You can follow us on [the fediverse](https://mastodon.art/@glimpse) and [Twitter](https://twitter.com/glimpse_editor). This blog also has a full text [RSS feed](https://getglimpse.app/index.xml). We also recently setup a [Facebook page](fb.me/glimpse.editor).

Our [Open Collective](https://opencollective.com/glimpse) backers also get regular updates about the project. 

Our Matrix and Discord channels are primarily intended for contributors and prospective contributors.

[Return to top](#contents)

## How do I contribute to this project? {#how-do-i-contribute-to-this-project}
All of our contribution links are available on our [Contribute](/contribute/) page.

Please ensure that you read our [code of conduct](/code-of-conduct/) before you join our community. Regardless of your past experience and the usefulness of your contributions you are expected to comply with it.

[Return to top](#contents)
