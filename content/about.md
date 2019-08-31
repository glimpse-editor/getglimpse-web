---
title: "About"
date: 2019-07-08T20:25:21+01:00
draft: false
menu: "main"
---
## Contents {#contents}

### Introduction
- [What is wrong with the "GIMP" name?](#what-is-wrong-with-the-gimp-name)
- [What initially motivated you to fork?](#why-are-you-forking)
- [Are you just forking because of the name?](#are-you-just-forking-because-of-the-name)
- [Do you intend to replace the GNU Image Manipulation Program?](#do-you-intend-to-replace-the-gnu-image-manipulation-program)
- [Is forking the project a duplication of effort?](#is-forking-the-project-a-duplication-of-effort)
- [Why did you change the mascot?](#why-did-you-change-the-mascot)
- [Are you open to changing the "Glimpse" name?](#are-you-open-to-changing-the-glimpse-name)
- [Did you know that name is used elsewhere?](#did-you-know-that-name-is-used-elsewhere)
- [What if I find the word "Glimpse" offensive?](#what-if-i-find-the-word-glimpse-offensive)
- [Where is the Glimpse code of conduct?](#where-is-the-glimpse-code-of-conduct)
- [Why is there no lead developer on this project?](#why-is-there-no-lead-developer-on-this-project)
- [Why do you need monetary donations?](#why-do-you-need-monetary-donations)
- [How do I stay up-to-date with this project?](#how-do-i-stay-up-to-date-with-this-project)
- [How do I contribute to this project?](#how-do-i-contribute-to-this-project)

### Technical Questions
- [Which operating systems do you support?](#which-operating-systems-do-you-support)
- [Will you contribute changes back upstream?](#will-you-contribute-changes-back-upstream)
- [This project is big! Will it take a long time to rebrand?](#this-project-is-big-will-it-take-a-long-time-to-rebrand)
- [Why are you using Github instead of Gitlab?](#why-are-you-using-github-instead-of-gitlab)
- [Why did you end support for the project IRC channel?](#why-did-you-end-support-for-the-project-irc-channel)

## What is wrong with the "GIMP" name? {#what-is-wrong-with-the-gimp-name}
If English is not your first language, then you may not have realised that the word "gimp" is problematic. In some countries it is considered a slur against disabled people and a playground insult directed at unpopular children. It can also be linked to certain "after dark" activities performed by consenting adults.

You may think that this is "political correctness gone mad" and that those who have been complaining about it for more than a decade are "over-sensitive", but this choice does have real-life consequences. In addition to the pain it can cause to marginalized communities many of us have our own free software advocacy stories about the GNU Image Manipulation Program not being taken seriously as an option by bosses or colleagues in professional settings.

Educational institutions and public libraries may feel unable to provide or recommend the program to students due to possible legal or moral concerns. It can also be difficult for a teacher to keep a class of school-age children disciplined and focussed if they are distracted by the name of the computer program they have been asked to use.

We believe free software should be accessible to everyone, and in this case a re-brand is both a desirable and very straightforward fix that could attract a whole new generation of users and contributors.

[Return to top](#contents)

## What initially motivated you to fork? {#why-are-you-forking}
In recent versions of the upstream software you may have noticed that the window titles have switched to "GNU Image Manipulation Program" and the documentation [suggests expanding the acronym](https://www.gimp.org/docs/userfaq.html#i-dont-like-the-name-gimp-will-you-change-it) as a work-around for the bad name. However, we do not think that adequately addresses the issue because the website domain, documentation and wider community still refers to it as "the Gimp" just as they have done for the last two decades.

Feature requests have been raised about the problem multiple times on the project's communication channels over the last 13 years, but each time they are ignored, dismissed and/or the discussions get spammed by those with strong political views.

It is unfortunate that we have to fork the whole project to change the name, but we feel that discussions about the issue are at an impasse and that this is the most positive way forward.

[Return to top](#contents)

## Are you just forking because of the name? {#are-you-just-forking-because-of-the-name}

No, but it did provide the motivation for many of us to fork the project in the first place.

We all love the GNU Image Manipulation Program, but it only has finite resources and so has to prioritise some changes over others. Decisions may have also been made historically for sound reasons that need to be revisited but cannot for the same reason. This can mean that good user interface improvements and functional changes that the community suggests can go unaddressed for years.

What this project aims to do is inject some new ideas, energy, contributions and money into a tool that most of us take for granted. We also want to expand the adoption of a great piece of free software.

[Return to top](#contents)

## Do you intend to replace the GNU Image Manipulation Program? {#do-you-intend-to-replace-the-gnu-image-manipulation-program}

No, this project does not intend to supplant the GNU Image Manipulation Program. You may have noticed we already link to their donations page throughout our documentation and intend to donate at least 10% of our Patreon contributions to the upstream project each time we release regardless of our own costs.

This project is also being run entirely by passionate enthusiasts. Development on the GNU Image Manipulation Program will continue as normal with the same core group of developers and be entirely unhindered by this project.

We anticipate in the coming months and years that Glimpse will be a place where people can experiment with fixes that upstream may not have had the resources to work on and new ideas that upstream may have felt unable or unwilling to try for legacy reasons.

If we come up with some popular improvements that really enhance the user experience then we would assist with contributing them back upstream so the wider community can benefit.

[Return to top](#contents)

## Is forking the project a duplication of effort? {#is-forking-the-project-a-duplication-of-effort}
No, because we are not reimplementing a 20 year old codebase from scratch. Also once we "hard fork" from GNU Image Manipulation Program v3.0 we still intend to apply useful upstream changes rather than completely reimplementing them.

From our point of view we are simply exercising [our software freedoms](https://www.gnu.org/philosophy/free-sw.html) by forking the project and redistributing a modified version for others to benefit from. This is fully in accordance with the spirit and requirements of the [GNU General Public License](https://www.gnu.org/licenses/gpl-3.0.en.html) and [GNU Lesser General Public License](https://www.gnu.org/licenses/lgpl-3.0.en.html) as they both apply to this project.

There are early plans to write a new GUI front-end in parallel to our current efforts, but that will take a number of years to produce and will still rely on the same GEGL and BABL libraries that the GNU Image Manipulation Program developers maintain.

[Return to top](#contents)

## Why did you change the mascot? {#why-did-you-change-the-mascot}
We wanted the project to forge its own identity. It is important we use this opportunity to foster new ideas and ways of working, and it may be harder to do that if we are still tied to old decisions made by a different project decades ago.

[Return to top](#contents)

## Are you open to changing the "Glimpse" name? {#are-you-open-to-changing-the-glimpse-name}

We do not believe in decisions that can never be overturned, but we consider this matter settled for the foreseeable future.

Whenever the discussion about whether we have chosen the right name is re-opened it takes up a lot of our moderators' time and distracts from more constructive tasks. Unfortunately we do not have the resources to repeatedly debate peoples' concerns about the same issue, particularly when those concerns are based primarily on individual tastes and preferences that may not be shared by everyone else.

Any name change has to weigh up the costs of doing so with the potential benefits. Currently the community we have cultivated broadly supports the "Glimpse" name, there has been no compelling reason suggested that makes a change of name particularly urgent, and there has been no alternative suggested that has excited our project contributors enough to strongly advocate for it so far.

We believe that using "Glimpse Image Editor" as the full name of the application makes its primary function clear enough to end users, while also enabling people to use "Glimpse" or "GIE" as a shorter name in casual everyday conversation.

[Return to top](#contents)

## Did you know that name is used elsewhere? {#did-you-know-that-name-is-used-elsewhere}
Users have made us aware of a few software projects that share the same name as this fork. That is always a risk when you use an English language word, but we do not believe that it will cause problems for end users or hinder the adoption of this program.

[Glimpse](https://apps.apple.com/us/app/glimpse/id423562777), [Glimpse](https://play.google.com/store/apps/details?id=com.clickherelabs.glimpseapp&hl=en_US) and [Glympse](https://www.glympse.com/) are mobile applications we are aware of. We believe the fact they all do something completely different, run on a different device category entirely and have their own branding means that end users will not be confused.

[GLobal IMPlicit SEarch](https://packages.debian.org/sid/text/glimpse) is a file searching utility ported from UNIX that has been spotted buried in Debian's "unstable" repository (it is also mirrored in Ubuntu's "universe" repository). It was abandoned for over a decade, then in 2016 it was picked up again by a maintainer who has since [applied minor patches](https://metadata.ftp-master.debian.org/changelogs//main/g/glimpse/glimpse_4.18.7-4_changelog). A related tool called [WebGlimpse](http://webglimpse.net/) was last updated in 2014. We dispute the idea that this is a "very popular" command line utility, but out of common courtesy we will ensure that package maintainers we assist avoid name clashes.

[Glimpse-soft](https://sourceforge.net/projects/glimpse-soft/) is also an image manipulation program, but it uses completely different code written in Microsoft Visual C++ and has had no new releases since 2004. The sole developer last updated the project's SourceForge page in 2015 but we believe that project has been abandoned for quite some time and does not have an active userbase.

[Glimpse](https://github.com/glimpse/glimpse) is a diagnostic platform whose source code is available on Github, and also uses the getglimpse.com domain name. We are currently reviewing this project to assess whether this clash is a problem.

We believe that once we have worked on search engine optimization (SEO) for our website, finalized the branding and the project has started to build up its own user base then it will rise up the Google search rankings accordingly.

[Return to top](#contents)

## What if I find the word "Glimpse" offensive? {#what-if-i-find-the-word-glimpse-offensive}
This seems unlikely given we checked its meaning in every known language, but if you have a legitimate concern then let us know.

If you are offended by the fact we renamed the project, we suggest you continue using the [GNU Image Manipulation Program](https://www.gimp.org) instead of annoying our contributors and making more work for our moderators.

[Return to top](#contents)

## Where is the Glimpse code of conduct? {#where-is-the-glimpse-code-of-conduct}
You will find it on [this page](../code-of-conduct/). Our code of conduct is based on [the contributor covenant](https://www.contributor-covenant.org/) and will be developed and amended over time as the need arises. As this project spawned from [the fediverse](https://joinmastodon.org/) our experiences in that online space are going to inform the project's future governance and direction.

There is no [benevolent dictator for life](https://en.wikipedia.org/wiki/Benevolent_dictator_for_life) for this fork because we value collective decision-making. We believe a governing group is less fallible, makes better-considered choices and reflects the will of the wider community more accurately. That approach will help us form a robust and fair code of conduct, and we have elaborated more on our current governance structure here: ["Why is there is no lead developer on this project?"](#why-is-there-no-lead-developer-on-this-project)

We also want to make it clear that we value and encourage diverse representation in leadership positions within our community, and we believe that is the best way to form a code of conduct that protects all contributors, promotes wider participation and ensures the rules are fairly enforced. At this early stage our initial governance team is formed entirely of individuals from marginalized communities, and that makes our project [very atypical](https://opensource.com/article/17/9/diversity-and-inclusion-innovation).

We know how important it is to enact the right code of conduct and enforce the rules properly. We want to promote a safe and inclusive environment, not a toxic one. If you have ideas to help us do that and want to get involved with this discussion then please join us in the project's communication channels.

[Return to top](#contents)

## Why is there no lead developer on this project? {#why-is-there-no-lead-developer-on-this-project}
In most free software projects this is a single individual that decides if issues should be ignored, cancelled or implemented. Granting someone that kind of power would effectively make them our "benevolent dictator", and we do not want one of those!

At this early stage we prefer to discuss things with the community first, then make decisions based on consensus between the members of the governance team. It is likely that as Glimpse develops there will be a more formal separation of responsibilities, an agreed way to assess community opinion and a documented path for contributors to participate in the decision-making process.

Our vision for the future is that the community will always have a say in the direction of this project, no choices will ever be impossible to overturn and everyone responsible for decision-making will be held accountable by their fellow contributors. The value or quantity of someone's contributions will not confer any "special status" on them or grant any immunity if they violate our project's code of conduct.

[Return to top](#contents)

## Why do you need monetary donations? {#why-do-you-need-monetary-donations}
Just like many other free software projects we need to host the collaboration tools we use to develop and share the project. We have to purchase domain names, cloud servers and subscriptions from service providers to make this project a success. In addition we also intend to pay the artists we commission for the re-brand and reward our contributors for the value they add.

The accusation we sometimes receive is that we are "stealing money from the GNU Image Manipulation Program". That is completely untrue, and we encourage those that want to support the upstream project to use [this donation page](https://www.gimp.org/donating/). Our project is also already discussing if some of the money we receive should be shared with the upstream project once we have covered our own costs.

If you would like to donate some money to Glimpse project, you can do so by [becoming a patron](https://www.patreon.com/glimpse) on Patreon.

[Return to top](#contents)

## How do I stay up-to-date with this project? {#how-do-i-stay-up-to-date-with-this-project}
You can follow us on [the fediverse](https://bobadon.co.uk/@glimpse) and [Twitter](https://twitter.com/glimpse_editor). This blog also has a full text [RSS feed](https://getglimpse.app/index.xml).

Our [Patreon](https://www.patreon.com/glimpse) backers also get regular updates about the project. Our more in-depth daily discussions can be viewed [on Matrix]([#glimpse:matrix.org](https://matrix.to/#/#glimpse:matrix.org)).

[Return to top](#contents)

## How do I contribute to this project? {#how-do-i-contribute-to-this-project}
You can spread the word when we share news on [the fediverse](https://bobadon.co.uk/@glimpse) and [Twitter](https://twitter.com/glimpse_editor). You can also donate to our [Patreon](https://www.patreon.com/glimpse) campaign.

Join us on [#glimpse:matrix.org](https://matrix.to/#/#glimpse:matrix.org) if you want to participate in the project's decision-making process. You can also raise bugs and work on tasks via our [Github Issues](https://github.com/glimpse-editor/Glimpse/issues) page.

Please ensure that you read our [code of conduct](../code-of-conduct/) before you join our project's community. Regardless of your past experience and the usefulness of your contributions you are expected to comply with it.

[Return to top](#contents)


## Which operating systems do you support? {#which-operating-systems-do-you-support}
*This answer is provisional and subject to change*

We intend to support recent desktop versions of Windows, Mac and Linux.

Linux users will be able to install Glimpse as a [Flatpak](https://flatpak.org/) or an [AppImage](https://appimage.org/).

A source tarball will be provided for package maintainers of Linux, BSD and Solaris distributions.

[Return to top](#contents)

## Will you contribute changes back upstream? {#will-you-contribute-changes-back-upstream}
Absolutely! We intend to be good free software citizens, and as soon as we have made changes that the upstream project want to include in their codebase we will be willing to assist them however we can. We may also donate some of the money we receive from Patreon backers to the upstream project, and the community will determine how much and how often.

While both projects may not agree on some things, it is clear to us that an adversarial attitude will not help either of us. If we work together then the whole free software community can benefit from this fork that attracts new contributors, breathes new life into an ageing codebase and shares free software with a whole new audience.

[Return to top](#contents)

## This project is big! Will it take a long time to rebrand? {#this-project-is-big-will-it-take-a-long-time-to-rebrand}
The 0.x releases will be a "soft fork" of the GNU Image Manipulation Program that provides a cosmetic rebrand and minor tweaks to the user interface.

The 1.x releases will be a "hard fork" of the GNU Image Manipulation Program that attempts more ambitious changes on the existing codebase. Glimpse 1.0 will likely happen around the release of upstream v3.0 so we can benefit from the full GTK3 port.

The 2.x releases will use a brand new GUI we have written from scratch while still relying on the underlying GEGL and BABL libraries that GNU Image Manipulation Program does. That effort will take a number of years, so it is likely this will be worked on in parallel while we make the 1.x releases.

We have been overwhelmed by the positive support we have received, and that is definitely helping us progress the project faster than anticipated.

[Return to top](#contents)

## Why are you using Github instead of Gitlab? {#why-are-you-using-github-instead-of-gitlab}

That was a choice made early on for entirely practical reasons such as project discoverability, ease-of-use, user familiarity and cost.

As a project we are aware some people have ethical concerns about using Github. For this reason we periodically discuss how our contributors feel about using it, as well as the merits and drawbacks of potential alternatives.

Currently there are no plans to move our code or mirror it elsewhere, but we are not opposed to the idea.

[Return to top](#contents)

## Why did you end support for the project IRC channel? {#why-did-you-end-support-for-the-project-irc-channel}

We initially set up an IRC channel on Freenode as a way of bringing people together and making some initial decisions for the Glimpse project during the first few days of its existence. One of the very first decisions the community made was that we should switch to something else, and we stopped supporting IRC after just a few weeks.

Our moderators monitored and supported the #glimpse channel while we made the switch to Matrix, and by the time we stopped doing so all project contributors had moved across and there had been little or no activity on IRC for over a week.

We did consider supporting IRC over the longer term with a Matrix bridge but it was determined that the delay on both sides would be frustrating for our contributors, and supporting multiple communication channels would be too time-consuming for our moderators.

As stated in a previous FAQ we do not believe in decisions that can never be overturned and are always open to suggested alternatives. So far the feedback we have received on Matrix has been mostly positive and there are more participants on our supported communication channels than ever before.

[Return to top](#contents)
