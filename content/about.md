---
title: "About"
date: 2019-09-29T06:14:00+01:00
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
- [Did you know that name is used elsewhere?](#did-you-know-that-name-is-used-elsewhere)
- [What if I find the word "Glimpse" offensive?](#what-if-i-find-the-word-glimpse-offensive)
- [Why do you need monetary donations?](#why-do-you-need-monetary-donations)
- [How do I stay up-to-date with this project?](#how-do-i-stay-up-to-date-with-this-project)
- [How do I contribute to this project?](#how-do-i-contribute-to-this-project)

### Technical Questions
- [Which operating systems do you support?](#which-operating-systems-do-you-support)
- [Will you contribute changes back upstream?](#will-you-contribute-changes-back-upstream)
- [This project is big! Will it take a long time to rebrand?](#this-project-is-big-will-it-take-a-long-time-to-rebrand)
- [Why are you using Github instead of Gitlab?](#why-are-you-using-github-instead-of-gitlab)
- [Why did you end support for the project IRC channel?](#why-did-you-end-support-for-the-project-irc-channel)

### Project Governance
- [Where is the Glimpse code of conduct?](#where-is-the-glimpse-code-of-conduct)
- [How does your project govern itself?](#how-does-this-project-govern-itself)
- [What are all the Matrix channels for?](#what-are-all-the-matrix-channels-for)

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

No, this project does not intend to supplant the GNU Image Manipulation Program. You may have noticed we already link to their donations page throughout our documentation and intend to donate at least 10% of our Patreon contributions we receive for each release to the upstream project regardless of our own costs.

This project is also being run entirely by passionate enthusiasts. Development on the GNU Image Manipulation Program will continue as normal with same core group of developers and be entirely unhindered by this project.

We anticipate in the coming months and years that Glimpse will be a place where people can experiment with fixes that upstream may not have had the resources to work on and new ideas that upstream may have felt unable or unwilling to try for legacy reasons.

If we come up with some popular improvements that really enhance the user experience then we would assist with contributing them back upstream so the wider community can benefit.

[Return to top](#contents)

## Is forking the project a duplication of effort? {#is-forking-the-project-a-duplication-of-effort}
No, because we are not reimplementing a 20 year old codebase from scratch. Also once we "hard fork" from GNU Image Manipulation Program v3.0 we still intend to apply useful upstream changes rather than completely reimplementing them.

From our point of view we are simply exercising [our software freedoms](https://www.gnu.org/philosophy/free-sw.html) by forking the project and redistributing a modified version for others to benefit from. This is fully in accordance with the spirit and requirements of the [GNU General Public License](https://www.gnu.org/licenses/gpl-3.0.en.html) and [GNU Lesser General Public License](https://www.gnu.org/licenses/lgpl-3.0.en.html) as they both apply to this project.

There are early plans to write a new GUI front-end with more modern technologies in parallel to our current efforts, but that will take a number of years to produce and will still rely on the same GEGL and BABL libraries that the GNU Image Manipulation Program developers maintain.

[Return to top](#contents)

## Did you know that name is used elsewhere? {#did-you-know-that-name-is-used-elsewhere}
We are aware of six other software programs and projects that use the "Glimpse" name. We have taken this feedback on board and already fixed our web domain because of this problem.

Our current stance on this issue is that "Glimpse" is a codename we will use for our project and the 0.x releases based on GNU Image Manipulation Program 2.x, but we will consider changing it from 1.0 onwards if we can find a better alternative.

We have also made changes based on feedback such as changing our website's domain name and defining "Glimpse" as  shortened version of "Glimpse Image Editor".

We welcome suggestions for a future product name and have set aside a Github issue to track it here: https://github.com/glimpse-editor/Glimpse/issues/92

[Return to top](#contents)

## What if I find the word "Glimpse" offensive? {#what-if-i-find-the-word-glimpse-offensive}
This seems unlikely given we checked its meaning in every known language, but if you have a legitimate concern then let us know.

If you are offended by the fact we renamed the project, we suggest you continue using the [GNU Image Manipulation Program](https://www.gimp.org) instead of annoying our contributors and making more work for our moderators.

[Return to top](#contents)

## Why do you need monetary donations? {#why-do-you-need-monetary-donations}
Just like many other free software projects we need to host the collaboration tools we use to develop and share the project. We have to purchase domain names, cloud servers and subscriptions from service providers to make this project a success. In addition we also intend to pay the artists we commission for the re-brand and reward our contributors for the value they add.

The accusation we sometimes receive is that we are "stealing money from the GNU Image Manipulation Program". That is completely untrue, and we encourage those that want to support the upstream project to use [this donation page](https://www.gimp.org/donating/). Our project is also already discussing if some of the money we receive should be shared with the upstream project once we have covered our own costs.

If you would like to donate some money to Glimpse project, you can do so by donating on [Open Collective](https://opencollective.com/glimpse) or [Patreon](https://www.patreon.com/glimpse).

[Return to top](#contents)

## How do I stay up-to-date with this project? {#how-do-i-stay-up-to-date-with-this-project}
You can follow us on [the fediverse](https://bobadon.co.uk/@glimpse) and [Twitter](https://twitter.com/glimpse_editor). This blog also has a full text [RSS feed](https://getglimpse.app/index.xml). We also recently setup a [Facebook page](fb.me/glimpse.editor).

Our [Open Collective](https://opencollective.com/glimpse) and [Patreon](https://www.patreon.com/glimpse) backers also get regular updates about the project. Our more in-depth daily discussions can be viewed [on Matrix]([#glimpse:matrix.org](https://matrix.to/#/#glimpse:matrix.org)).

[Return to top](#contents)

## How do I contribute to this project? {#how-do-i-contribute-to-this-project}
All of our contribution links are available on our [Contribute](/contribute/) page.

Please ensure that you read our [code of conduct](/code-of-conduct/) before you join our community. Regardless of your past experience and the usefulness of your contributions you are expected to comply with it.

[Return to top](#contents)

## Which operating systems do you support? {#which-operating-systems-do-you-support}
We support systems running Windows 7 or newer, and modern variants of GNU/Linux.

Unfortunately we are not able to support MacOS at this time. We recommend [Seashore](http://libregraphicsworld.org/blog/entry/meet-seashore-free-image-editor-for-macos) as an alternative.

[Return to top](#contents)

## Will you contribute changes back upstream? {#will-you-contribute-changes-back-upstream}
Absolutely! We intend to be good free software citizens, and as soon as we have made changes that the upstream project want to include in their codebase we will be willing to assist them however we can. We have also committed to donating at least 10% of the donations we receive for each new release to the GNU Image Manipulation Program developers.

While both projects may not agree on some things, it is clear to us that an adversarial attitude will not help either of us. If we work together then the whole free software community can benefit from this fork that attracts new contributors, breathes new life into an ageing codebase and shares free software with a whole new audience.

[Return to top](#contents)

## This project is big! Will it take a long time to rebrand? {#this-project-is-big-will-it-take-a-long-time-to-rebrand}
The 0.x releases are a "soft fork" of the GNU Image Manipulation Program v2.x that provides a cosmetic rebrand and minor tweaks to the user interface.

The 1.x releases will be a "hard fork" of the GNU Image Manipulation Program v3.x that attempts more ambitious changes on the existing codebase. That will enable us to benefit from the port to GTK3 and more modern Meson build system.

The 2.x releases will use a brand new GUI we have written from scratch while still relying on the underlying GEGL and BABL libraries that GNU Image Manipulation Program does. That effort will take a number of years, so it is likely this will be worked on in parallel while we make the 1.x releases.

We have been overwhelmed by the positive support we have received, and that is continuing to help us progress the project faster than anticipated.

[Return to top](#contents)

## Why are you using Github instead of Gitlab? {#why-are-you-using-github-instead-of-gitlab}

That was a choice made early on for entirely practical reasons such as project discoverability, ease-of-use, user familiarity and cost.

As a project we are aware some people have ethical concerns about using Github, and that other projects shows up above us in [the search results](https://github.com/search?utf8=%E2%9C%93&q=glimpse&type=). For those reasons we periodically discuss how our contributors feel about using it, as well as the merits and drawbacks of potential alternatives.

There are no immediate plans to move our code or mirror it elsewhere, but we are not opposed to the idea.

[Return to top](#contents)

## Why did you end support for the project IRC channel? {#why-did-you-end-support-for-the-project-irc-channel}

We initially set up an IRC channel on Freenode as a way of bringing people together and making some initial decisions for the Glimpse project during the first few days of its existence. One of the very first decisions the community made was that we should switch to something else, and we stopped supporting IRC after just a few weeks.

Our moderators monitored and supported the #glimpse channel while we made the switch to Matrix, and by the time we stopped doing so all project contributors had moved across and there had been little or no activity on IRC for over a week.

We did consider supporting IRC over the longer term with a Matrix bridge but it was determined that the delay on both sides would be frustrating for our contributors, and supporting multiple communication channels would be too time-consuming for our moderators.

As stated in a previous FAQ we do not believe in decisions that can never be overturned and are always open to suggested alternatives. So far the feedback we have received on Matrix has been mostly positive and there are more participants on our supported communication channels than ever before.

[Return to top](#contents)

## Where is the Glimpse code of conduct? {#where-is-the-glimpse-code-of-conduct}
You will find it on [this page](/code-of-conduct/). Our code of conduct is based on [the contributor covenant](https://www.contributor-covenant.org/) and will be developed and amended over time as the need arises. As this project spawned from [the fediverse](https://joinmastodon.org/) our experiences in that online space are going to inform the project's future governance and direction.

There is no [benevolent dictator for life](https://en.wikipedia.org/wiki/Benevolent_dictator_for_life) in the traditional sense for this fork because we believe in the merits of collective decision-making. They might sometimes take longer to make decisions, but a group is often less fallible, makes better-considered choices and reflects the will of the wider community more accurately than an individual.

That approach has worked well for us so far, and you can read more about our governance structure here: ["How does your project govern itself?"](#how-does-this-project-govern-itself)

We also want to make it clear that we value and encourage diverse representation in leadership positions within our community, and we believe that is the best way to enforce a code of conduct that protects all contributors and promotes wider participation. At this early stage our initial governance team is formed entirely of individuals from marginalized communities, and that makes our project [very atypical](https://opensource.com/article/17/9/diversity-and-inclusion-innovation). That emerged organically as a result of the project starting on [the fediverse](https://fediverse.party/).

We know how important it is to enact the right code of conduct and enforce the rules properly. We want to promote a safe and inclusive environment, not a toxic one. If you have ideas to help us do that and want to get involved with this discussion then please join us in the project's communication channels.

[Return to top](#contents)

## How does your project govern itself? {#how-does-this-project-govern-itself}
The way we govern ourselves is something that evolves over time based on feedback we receive and what we find works and does not work. The summary provided in this answer is intended to illustrate how we currently make decisions and are held accountable by our community.

[Github Issues](https://github.com/glimpse-editor/Glimpse/issues) are used to track bug reports, suggestions and questions from the wider community, and items we have agreed as a project need action. Action items are allocated to a milestone to give an indication of their priority and likely timeline, but these are always provisional until the work is done.

Most day-to-day discussion happens in the **#glimpse:matrix.org** (or "Glimpse Community") Matrix channel. Anyone can join so long as they comply with our code of conduct, support the basic premise behind this project existing and don't spam the channel with off-topic chatter or shameless self-promotion. This is where most of the actual decision-making happens, and our community has the opportunity to voice their opinions or share their domain-specific knowledge there.

Anyone named in the `AUTHORS` file is eligible to join the **#glimpse-contributors:matrix.org** (or "Glimpse Contributors") Matrix channel. They make the low-level technical decisions necessary to deliver items that have already been agreed. It is also used as a fallback communication channel between contributors when the "Glimpse General" Matrix channel is busy with the decision-making process so that development work is not obstructed by it.

While they might make some time-sensitive moderation decisions as individuals, all other decisions are not considered "agreed" until they have been discussed on the "Glimpse Community" channel and a consensus has been achieved between all members of the "governance team". Initiatives originating from the governance team instead of the community are sometimes discussed on the "Glimpse Contributors" Matrix channel first.

No decision is ever set in stone and can be revisited if new information comes to light or there is enough support within the project to do so. The governance team will generally only block the re-opening of an issue or delay a decision if the discussion is becoming too heated or obstructs the day-to-day running of the project.

There are currently three people in our governance team: [Bobby Moss](https://bobadon.co.uk/@trechnex) (started the fork), [Christopher Davis](https://social.libre.fi/users/brainblasted) (posted the renaming issue on upstream gitlab repository) and [Clipsey](https://bobadon.co.uk/@clipsey) (started the "UI rewrite" planning).

Finally, the project may from time to time run polls on social media to canvas opinion for specific issues if there is support for doing so. They are always non-binding and only intended to facilitate the existing decision-making process.

[Return to top](#contents)

## What are all the Matrix channels for? {#what-are-all-the-matrix-channels-for}
All of our channels are on matrix.org. You can get access to the invite-only channels by asking for it on the "Glimpse Community" channel.

- **#glimpse**: "Glimpse Community" channel that anyone can join so long as they keep discussion on topic, support the project and comply with our code of conduct
- **#glimpse-offtopic**: Off-topic chatter between members of our project and the community in a safe, welcoming environment
- **#glimpse-github**: Matrix alternative to receiving Github notifications by email
- **#glimpse-2x**: Focussed discussion for the Glimpse 2.x "UI rewrite" working group
- **#glimpse-contributors**: "Glimpse Contributors" channel for core contributors. Only people listed in our `AUTHORS` file are eligible to join.
- **#glimpse-admin**: "Glimpse Admin" channel for our moderators to support each other. This is a private channel used by members of the governance team.

[Return to top](#contents)
