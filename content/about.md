---
title: "About (FAQs)"
date: 2020-04-05T15:00:00+01:00
draft: false
menu: "main"
---
## Contents {#contents}
Glimpse is an open source image editor based on the GNU Image Manipulation Program. The goal is to experiment with new ideas and expand the use of free software.

### Introduction
- [What is the correct name for your project?](#what-is-the-correct-name-for-your-project)
- [Did you know that name is used elsewhere?](#did-you-know-that-name-is-used-elsewhere)
- [What is wrong with the "GIMP" name?](#what-is-wrong-with-the-gimp-name)
- [Why are you forking?](#why-are-you-forking)
- [Are you just forking because of the name?](#are-you-just-forking-because-of-the-name)
- [What if I find the word "Glimpse" offensive?](#what-if-i-find-the-word-glimpse-offensive)
- [Do you intend to replace the GNU Image Manipulation Program?](#do-you-intend-to-replace-the-gnu-image-manipulation-program)
- [Is forking the project a duplication of effort?](#is-forking-the-project-a-duplication-of-effort)

### Technical Questions
- [How does your release numbering work?](#how-does-your-release-numbering-work)
- [Which operating systems do you support?](#which-operating-systems-do-you-support)
- [Who signs the Windows installer?](#who-signs-the-windows-installer)
- [Can I install Glimpse and GNU Image Manipulation Program on the same machine?](#can-i-install-glimpse-and-gnu-image-manipulation-program-on-the-same-machine)
- [Are you going to publish this for my favorite Linux distribution?](#are-you-going-to-publish-this-for-my-favorite-linux-distribution)
- [Will you support BSD, Haiku, Solaris or other UNIX platforms?](#will-you-support-bsd-haiku-solaris-or-other-unix-platforms)
- [Will you contribute changes back upstream?](#will-you-contribute-changes-back-upstream)
- [Why are you using Github instead of Gitlab?](#why-are-you-using-github-instead-of-gitlab)
- [Could you just run "find and replace" to fix the name?](#could-you-just-run-find-and-replace-to-fix-the-name)
- [When are you going to implement the bug-fix or feature I asked for?](#when-are-you-going-to-implement-the-feature-i-asked-for)
- [Can you make Glimpse look like Adobe Photoshop?](#can-you-make-glimpse-look-like-adobe-photoshop)

### Project Governance
- [Where is the Glimpse code of conduct?](#where-is-the-glimpse-code-of-conduct)
- [How does your project govern itself?](#how-does-this-project-govern-itself)
- [What are all the Matrix channels for?](#what-are-all-the-matrix-channels-for)
- [Why do you need monetary donations?](#why-do-you-need-monetary-donations)
- [How do I stay up-to-date with this project?](#how-do-i-stay-up-to-date-with-this-project)
- [How do I contribute to this project?](#how-do-i-contribute-to-this-project)

---

## What is the correct name for your project? {#what-is-the-correct-name-for-your-project}
The free software we produce is called "Glimpse Image Editor", but we sometimes shorten that to just "Glimpse". We refer to our governance structure, core contributors and participants on our public Matrix channel as "the Glimpse project". We often call our social media followers, donors and end users "the Glimpse Community".

If you are a blogger or a member of the technology industry press, we do not yet have branding guidelines in place. However we have provided screenshots, our branding assets and instructions for their basic usage here: https://github.com/glimpse-editor/branding

[Return to top](#contents)

## Did you know that name is used elsewhere? {#did-you-know-that-name-is-used-elsewhere}
We are aware of a number of other unrelated projects called "Glimpse". We have made changes based on feedback from our critics such as changing our website's domain name and defining "Glimpse" as a shortened version of "Glimpse Image Editor".

The project's current stance is that while we are theoretically open to changing our name, there is very limited support in favor of actually doing so. We granted our critics time to find an alternative name that addresses the concerns they raised, fulfils our project's requirements and enjoys popular support. Even with three months and our assistance they were not able to do so, so we consider the matter closed for the time being.

See ["How does your project govern itself?"](#how-does-this-project-govern-itself) for more details about why we now limit discussion about this topic on our Matrix channels.

[Return to top](#contents)

## What is wrong with the "GIMP" name? {#what-is-wrong-with-the-gimp-name}
It was originally chosen by Spencer Kimball and Peter Mattis as a joke name that refers to a questionable scene in an 18 certificate movie called "Pulp Fiction". Within Linux enthusiast and hobbyist communities that whimsical '90s era "gross out" humor may still be appreciated by some people. However, like all "comedy", there is a time and a place for it.

We also believe that the casual ableism of the name is unwelcome, and it hinders efforts to expand participation and diversity within the free software community. That means the project could be missing out on new ideas, contributors and resources that would improve things for everyone.

Many of us have real world experience advocating free software as a serious choice in educational or workplace environments, and we believe that a joke name some find offensive and distracting presents an unnecessary obstacle to wider adoption.

[Return to top](#contents)

## Why are you forking? {#why-are-you-forking}
We do not believe that [upstream's suggestion](https://www.gimp.org/docs/userfaq.html#i-dont-like-the-name-gimp-will-you-change-it) to "expand the acronym" to fix their software's name adequately addresses the problem, and after 13+ years of users repeatedly asking we think the most constructive path forward is to fork the project.

In addition, the [dedicated UI design team](https://gui.gimp.org/index.php?title=Former_GUI_team) for GNU Image Manipulation Program stopped meeting in 2012. While development work on the GUI and installers still continued, we felt as end users that usability improvements were not receiving the same priority as niche power user tasks and code restructuring, so that is the area we want to focus on.

Finally there was a historic decision to remove the [third party plug-in registry](https://www.gimp.org/registry/) and in-built mechanism that supported it. While we lack the resources to reinstate that system, we plan to pre-bundle a selection of useful third party plug-ins that are difficult to find as an additional install option.

[Return to top](#contents)

## Are you just forking because of the name? {#are-you-just-forking-because-of-the-name}
No, but it did provide the motivation for many of us to fork the project in the first place.

Our contributors have used GNU Image Manipulation Program for a long time, but the upstream project only has finite resources and so has to prioritise some changes over others. Decisions may have also been made historically for sound reasons that need to be revisited but cannot for the same reason. This can mean that good user interface improvements and functional changes that the community suggests can go unaddressed for years.

What this project aims to do is inject some new ideas, energy, contributions and money into a tool that most of us take for granted. We also want to expand the adoption of a great piece of free software.

[Return to top](#contents)

## What if I find the word "Glimpse" offensive? {#what-if-i-find-the-word-glimpse-offensive}
That seems unlikely given we checked its meaning in every known language, but if you have a legitimate concern then let us know.

If you are offended by the fact we renamed the project, we suggest you continue using the [GNU Image Manipulation Program](https://www.gimp.org) instead of annoying our contributors and making more work for our moderators.

[Return to top](#contents)

## Do you intend to replace the GNU Image Manipulation Program? {#do-you-intend-to-replace-the-gnu-image-manipulation-program}
No, this project does not intend to supplant the GNU Image Manipulation Program. You may have noticed we already link to [their donations page](https://www.gimp.org/donating/) throughout our documentation and we periodically donate a portion of our own funds to the upstream project.

The Glimpse project is also run entirely by passionate enthusiasts. Development on the GNU Image Manipulation Program will continue as normal with same core group of developers and be entirely unhindered by this project.

We anticipate in the coming months and years that Glimpse will be a place where people can experiment with fixes that upstream may not have had the resources to work on and new ideas that upstream may have felt unable or unwilling to try for legacy reasons.

If we come up with some popular improvements that really enhance the user experience or fix bugs that impact both projects, then we would assist with contributing them back upstream so the wider community can benefit.

[Return to top](#contents)

## Is forking the project a duplication of effort? {#is-forking-the-project-a-duplication-of-effort}
No, because there are [at least three well-articulated problems](#why-are-you-forking) that justify our fork existing.

From our point of view we are simply exercising [our software freedoms](https://www.gnu.org/philosophy/free-sw.html) by forking the project and redistributing a modified version for others to benefit from. This is fully in accordance with the spirit and requirements of the [GNU General Public License](https://www.gnu.org/licenses/gpl-3.0.en.html) and [GNU Lesser General Public License](https://www.gnu.org/licenses/lgpl-3.0.en.html) as they both apply to this project.

There are early plans to write a new image editor with more modern technologies in parallel to our current efforts, but that will take a number of years to produce.

[Return to top](#contents)

## How does your release numbering work? {#how-does-your-release-numbering-work}
Glimpse Image Editor 0.1.0 is based on the GNU Image Manipulation Program 2.10.12. All 0.1.x releases add our changes, backport useful upstream functionality and update key dependencies on the same 2.10.12 base.

Glimpse Image Editor 0.2.0 will be rebased on whichever release of the GNU Image Manipulation Program is current and stable on 2020-07-05, and we intend to release it before September 2020.

Whenever we produce a 0.x.0 release, we will continue adding features to it every few months until July the following year. We then intend to provide "maintenance updates" providing patches and updated dependencies for up to a year afterwards if any severe bugs or security issues are reported to us.

"Beta test" and "Stable" release versions always end in an even number. Odd numbered versions are "Unstable" builds created from our development branch.

Glimpse Image Editor 1.0.0 will be a complete re-fork based on the GNU Image Manipulation Program 3.x. We feel this is necessary because of the major changes that will be included in that upstream release.

Glimpse Image Editor 2.0.0 will either be another fork of the GNU Image Manipulation Program, or we may switch to an entirely new image editing application that we wrote ourselves.

[Return to top](#contents)

## Which operating systems do you support? {#which-operating-systems-do-you-support}
We support systems running Windows 7 or newer, and modern variants of GNU/Linux.

Unfortunately we are not able to support MacOS at this time, but that is planned for the future. For the time being, we recommend using [Seashore](http://libregraphicsworld.org/blog/entry/meet-seashore-free-image-editor-for-macos) as an alternative.

[Return to top](#contents)

## Who signs the Windows installer? {#who-signs-the-windows-installer}
[Cynthia Revström](https://cynthia.re/), a renowned security researcher. She signs our Windows installers with an Extended Validation (EV) code signing certificate belonging to a registered company called [Qs.nu](https://qs.nu/).

If we do not sign our MSI installer then potential users can run into a number of problems. Certain web browsers block the download of "untrusted" files, Windows SmartScreen creates error screens that non-technical people find difficult to override, and anti-virus programs incorrectly flagging Glimpse Image Editor as "malware" can interfere with the installation process and normal operation of the program.

We initially tried a self-signed certificate, but that did not resolve the problem. The Glimpse project is not a registered company and cannot afford to reimburse individuals for certificate authority notarization requirements, so we cannot provide our own code signing certificate. As a result we rely on a trusted individual to voluntarily sign each MSI installer we release on our behalf.

There are plans to also package the software as an MSIX file and [submit it to the Microsoft Store](https://github.com/glimpse-editor/Glimpse/issues/180). We believe that the ability to run Glimpse Image Editor in a secure sandbox that has been audited/signed by Microsoft themselves and downloaded from a trusted source will satisfy the Windows security requirements for most organizations.

[Return to top](#contents)

## Can I install Glimpse and GNU Image Manipulation Program on the same machine? {#can-i-install-glimpse-and-gnu-image-manipulation-program-on-the-same-machine}
On Windows, you can safely install and run both applications at the same time.

On Linux, the Flatpak build that we support and maintain is fully self-contained and should not interfere with any installed versions of the GNU Image Manipulation Program. If you discover that is not the case on your system, please [report it as a bug](https://github.com/glimpse-editor/Glimpse/issues).

If you are using a Linux build from a third party source that we do not directly support (such as Snapcraft, AUR or your distribution's package repositories) then it is unlikely because there may be package and file name conflicts. You should ask the people responsible for maintaining those packages for confirmation and any help you might need.

[Return to top](#contents)

## Are you going to publish this for my favorite Linux distribution? {#are-you-going-to-publish-this-for-my-favorite-linux-distribution}
You can see all the Linux installation methods we are aware of for Glimpse Image Editor on [our downloads page](/downloads/).

We directly support a [Flatpak on Flathub](https://flathub.org/apps/details/org.glimpse_editor.Glimpse), and we plan to publish our own AppImage very soon. 

The Glimpse project does not endorse or "prefer" any specific packaging format or distribution. We have limited resources, so have chosen a primary format (Flatpak) and a fallback format (AppImage) as they are straightforward for us to maintain over a sustained period and will have wide compatibility within the Linux ecosystem over the next few years.

However, we support and encourage third party packagers wherever we can, and code changes that facilitate their work are accepted. An excellent example of that policy in action is the Snapcraft package, which is managed and maintained by [Heather Ellsworth](https://blogs.gnome.org/hellsworth/).

An alternative example is an individual that has not been in direct contact with our project at all maintaining [a community package on AUR](https://aur.archlinux.org/packages/glimpse-editor-git/) for Arch Linux users. Unlike our official releases it is built from our development branch instead of formal release tags, so we do not accept any bug reports from users that have chosen to install Glimpse Image Editor using that method.

At the request of package maintainers, we plan to provide a source tarball we have run `make dist` against from Glimpse Image Editor 0.1.2 onwards.

[Return to top](#contents)

## Will you support BSD, Haiku, Solaris or other UNIX platforms? {#will-you-support-bsd-haiku-solaris-or-other-unix-platforms}
The only UNIX operating system we currently have plans to directly support is macOS.

Other UNIX systems are treated the same way as any individual Linux distribution. We do not directly support the individual packaging formats and publishing platforms for each variant of UNIX because we don't have the knowledge or resources to support and maintain them all.

However, we will accept code fixes that enhance UNIX compatibility and will assist any third party package maintainers that want to port Glimpse Image Editor to operating systems like BSD, Haiku, Solaris and other UNIX variants.

[Return to top](#contents)

## Will you contribute changes back upstream? {#will-you-contribute-changes-back-upstream}
Absolutely! We intend to be good free software citizens, and as soon as we have made changes that the upstream project want to include in their codebase we will be willing to assist them however we can. We have also periodically donated a portion of the donations we have received to the GNU Image Manipulation Program developers.

While both projects may not agree on some things, it is clear to us that an adversarial attitude will not help either of us. If we work together then the whole free software community can benefit from this fork that attracts new contributors, breathes new life into an ageing codebase and shares free software with a whole new audience.

[Return to top](#contents)

## When are you going to implement the bug-fix or feature I asked for? {#when-are-you-going-to-implement-the-feature-i-asked-for}
The first place to check is our [Github Issues list](https://github.com/glimpse-editor/Glimpse/issues).

We aim to tag each bug and feature request to a [release milestone](https://github.com/glimpse-editor/Glimpse/milestones) so that you have a rough idea of when we think we can feasibly deliver the functionality. Those estimates are subject to change based on our shifting project priorities and any technical hurdles we come across. We also do our best to add regular comments to every issue so that you can see the most up-to-date information about them.

If the functionality you want is not listed, the next place to check is [the roadmap page](https://wiki.gimp.org/wiki/Roadmap) for the GNU Image Manipulation Program. Because that project has more contributors and resources than we do as a downstream fork, we are normally a release or two behind them. If they are implementing a fix or change though, then we will eventually inherit it.

Finally, if the change you want isn't requested in either place then feel free to raise it as a bug or a feature request! Alternatively you can contact us by using the links on our [Contribute](/contribute/) page.

[Return to top](#contents)

## Can you make Glimpse look like Adobe Photoshop? {#can-you-make-glimpse-look-like-adobe-photoshop}
Technically yes, but we are not going to do that.

We understand why it is important for Glimpse Image Editor to feel familiar to users of existing image editing applications, but we also think it's important for us to do our own thing. Not only will that lead to more new and interesting ideas, it should also avoid any potential legal problems.

The developers of the GNU Image Manipulation Program have the same stance on this, and they go into much more detail on [their FAQ page](https://www.gimp.org/docs/userfaq.html#i-dont-like-gimps-user-interface-why-cant-you-just-copy-adobe-photoshop).

[Return to top](#contents)

## Why are you using Github instead of Gitlab? {#why-are-you-using-github-instead-of-gitlab}

That was a choice made early on for entirely practical reasons such as project discoverability, ease-of-use, user familiarity and cost.

As a project we are aware some people have ethical concerns about using Github, and that other projects appear above us in [the search results](https://github.com/search?utf8=%E2%9C%93&q=glimpse&type=). For those reasons we periodically discuss how our contributors feel about using it, as well as the merits and drawbacks of potential alternatives.

There are no immediate plans to move our code, but there are early plans to host a separate code mirror for use with our build system.

[Return to top](#contents)

## Could you just run "find and replace" to fix the name? {#could-you-just-run-find-and-replace-to-fix-the-name}

We could, but that would completely destroy plug-in compatibility and break the upstream subcomponents on which we rely. That would also cause serious problems with all the build scripts and be very time-consuming to fix.

To preserve compatibility we had to maintain existing file names, variable names, constants, class names, methods and APIs. This meant we had to provide our own files, variables and constants, then identify where we wanted to use them, swap in those values wherever that did not break compatibility, and find a suitable replacement wherever we referred to upstream code that we had not modified (we settled on "GNU I.M.P"). That cannot be achieved by just using find-and-replace tools or regular expressions.

In addition to changing the name we also wanted to change the project logo. We commissioned an artist to do that for us, and subsequently had to make code fixes to the application to swap in our own art assets.

Finally, we also had to ensure that our changes were applied appropriately in the existing translation files and did not break the automated mechanisms in the build systems that keep them up-to-date.

In short, it is not easy to rebrand the GNU Image Manipulation Program. Similarly, the reason why this project is not just "one man and his Github repository" is because we do have other objectives and intend to create free software that other people actually want to use.

[Return to top](#contents)

## Where is the Glimpse code of conduct? {#where-is-the-glimpse-code-of-conduct}
You will find it on [this page](/code-of-conduct/). Our code of conduct is based on [the contributor covenant](https://www.contributor-covenant.org/) and will be developed and amended over time as the need arises. As this project spawned from [the fediverse](https://joinmastodon.org/) our experiences in that online space are going to inform the project's future governance and direction.

There is no [benevolent dictator for life](https://en.wikipedia.org/wiki/Benevolent_dictator_for_life) in the traditional sense for this fork because we believe in the merits of collective decision-making. They might sometimes take longer to make decisions, but a group is often less fallible, makes better-considered choices and reflects the will of the wider community more accurately than an individual.

That approach has worked well for us so far, and you can read more about our governance structure here: ["How does your project govern itself?"](#how-does-this-project-govern-itself)

We also want to make it clear that we value and encourage diverse representation in leadership positions within our community, and we believe that is the best way to enforce a code of conduct that protects all contributors and promotes wider participation. At this early stage our initial governance team is formed entirely of individuals from marginalized communities, and that makes our project [very atypical](https://opensource.com/article/17/9/diversity-and-inclusion-innovation). That emerged organically as a result of the project starting on [the fediverse](https://fediverse.party/).

We know how important it is to enact the right code of conduct and enforce the rules pro-actively. We want to promote a safe and inclusive environment, not a toxic one. If you have ideas to help us do that and want to get involved with this discussion then please join us in the project's communication channels.

[Return to top](#contents)

## How does your project govern itself? {#how-does-this-project-govern-itself}
The way we govern ourselves is something that evolves over time based on feedback we receive and what we find works and does not work. The summary provided in this answer is intended to illustrate how we currently make decisions and are held accountable by our community.

[Github Issues](https://github.com/glimpse-editor/Glimpse/issues) are used to track bug reports, suggestions and questions from the wider community, and items we have agreed as a project need action. Action items are allocated to a milestone to give an indication of their priority and likely timeline, but these are always provisional until the work is done.

Most day-to-day discussion happens in the **#glimpse:matrix.org** (or "Glimpse Community") Matrix channel. Anyone can join so long as they comply with our code of conduct, support the basic premise behind this project existing and don't spam the channel with off-topic chatter or shameless self-promotion. This is where most of the actual decision-making happens, and our community has the opportunity to voice their opinions or share their domain-specific knowledge there.

Anyone named in the `AUTHORS` file are eligible to join the **#glimpse-contributors:matrix.org** (or "Glimpse Contributors") Matrix channel. They make the low-level technical decisions necessary to deliver items that have already been agreed. It is also used as a fall-back communication channel between contributors when the "Glimpse Community" Matrix channel is busy with the decision-making process so that development work is not obstructed by it.

While they might make some time-sensitive moderation decisions as individuals, all other decisions are not considered "agreed" until they have been discussed on the "Glimpse Community" channel and a consensus has been achieved between all members of the "governance team". Initiatives originating from the governance team instead of the community are sometimes discussed on the "Glimpse Contributors" Matrix channel first.

No decision is ever set in stone and can be revisited if new information comes to light or there is enough support within the project to do so. The governance team will generally only block the re-opening of an issue or delay a decision if the discussion is becoming too heated or obstructs the day-to-day running of the project.

There are currently four people in our governance team: [Bobby Moss](https://mastodon.sdf.org/@trechnex) (started the fork), [Christopher Davis](https://social.libre.fi/users/brainblasted) (posted the renaming issue on upstream gitlab repository), [Luna](https://social.pixie.town/@Clipsey) (started the "UI rewrite" planning) and [chaomodus](https://radical.town/@chaomodus) (manages our server-side infrastructure).

Finally, the project may from time to time run polls on social media to canvas opinion for specific issues if there is support for doing so. They are always non-binding and only intended to facilitate the existing decision-making process.

[Return to top](#contents)

## What are all the Matrix channels for? {#what-are-all-the-matrix-channels-for}
All of our channels are on matrix.org. You can get access to the invite-only channels by asking for it on the "Glimpse Community" channel.

- **#glimpse**: "Glimpse Community" channel that anyone can join so long as they keep discussion on topic, support the project and comply with our code of conduct
- **#glimpse-offtopic**: Off-topic chatter between well-known members of our community in a safe, welcoming environment
- **#glimpse-github**: Matrix alternative to receiving Github notifications by email
- **#glimpse-2x**: Focussed discussion for the Glimpse 2.x "UI rewrite" working group
- **#glimpse-contributors**: "Glimpse Contributors" channel for core contributors. Only people listed in our `AUTHORS` file are eligible to join.
- **#glimpse-admin**: "Glimpse Admin" channel for our moderators to support each other. This is a private channel used by members of the governance team.

[Return to top](#contents)

## Why do you need monetary donations? {#why-do-you-need-monetary-donations}
Just like many other free software projects we need to host the collaboration tools we use to develop and share the project. We have to purchase domain names, cloud servers, code signing certificates and subscriptions from service providers to make this project a success. In addition we also intend to pay the artists we commission for the re-brand, market our software, and eventually help our contributors represent us at conferences.

If you would like to donate some money to Glimpse project, you can do so by donating on [Open Collective](https://opencollective.com/glimpse).

We also encourage those who want to support the GNU Image Manipulation Program to use [their donation page](https://www.gimp.org/donating/) to do so.

[Return to top](#contents)

## How do I stay up-to-date with this project? {#how-do-i-stay-up-to-date-with-this-project}
You can follow us on [the fediverse](https://mastodon.art/@glimpse) and [Twitter](https://twitter.com/glimpse_editor). This blog also has a full text [RSS feed](https://getglimpse.app/index.xml). We also recently setup a [Facebook page](fb.me/glimpse.editor).

Our [Open Collective](https://opencollective.com/glimpse) backers also get regular updates about the project. Our more in-depth daily discussions can be viewed [on Matrix]([#glimpse:matrix.org](https://matrix.to/#/#glimpse:matrix.org)).

[Return to top](#contents)

## How do I contribute to this project? {#how-do-i-contribute-to-this-project}
All of our contribution links are available on our [Contribute](/contribute/) page.

Please ensure that you read our [code of conduct](/code-of-conduct/) before you join our community. Regardless of your past experience and the usefulness of your contributions you are expected to comply with it.

[Return to top](#contents)
