---
title: "A Second Month Closes"
date: 2019-09-03T19:27:00+01:00
draft: false
---
Here is a quick reminder of where you can find us on social media and our project tools:

- Twitter: https://twitter.com/glimpse_editor
- Fediverse: https://bobadon.co.uk/@glimpse
- Patreon: https://www.patreon.com/glimpse
- Matrix: https://matrix.to/#/#glimpse:matrix.org
- Github: https://github.com/glimpse-editor/Glimpse
- Wiki: https://wiki.glimpse-editor.org
- FAQs: https://glimpse-editor.org/about/

We also encourage those who can to donate to the GNU Image Manipulation Program, as that funds the components Glimpse depends on: https://www.gimp.org/donating/

## Addressing a common misconception
We would like to take a moment to clarify that contrary to what some of you may have heard we did not "split from" the GNU Image Manipulation Program, and their project's resources have not been "divided" between us both.

The Glimpse project is made up of a group of enthusiasts from outside the upstream project running their own fork and learning the codebase as they work on it. The same contributors that originally developed the GNU Image Manipulation Program are still doing so now and are entirely unimpeded by this fork.

For more information, read this FAQ: https://glimpse-editor.org/about/#do-you-intend-to-replace-the-gnu-image-manipulation-program

## We were discussed on The Register
Bobby Moss was interviewed by Tim Anderson, and you can read the resulting article here: https://www.theregister.co.uk/2019/08/28/gimp_open_source_image_editor_forked_to_fix_problematic_name/

## The "Glimpse" name was discussed in detail
We have opened a Github issue for the community to provide suggestions and discuss new names here: https://github.com/glimpse-editor/Glimpse/issues/92

After several days of intense discussion on Matrix it was determined that "Glimpse" should be treated as a code name for the 0.x "soft fork" releases based on the GNU Image Manipulation Program v2. A potential change of name would be applied from 1.0, the first release that "hard forks" from GNU Image Manipulation Program v3 (scheduled some time in 2020).

Making the decision on whether we should change the name a "blocking" issue for 0.1 turned out to be a major distraction that could have delayed our first binary release indefinitely, so we feel that allowing more time to find a solution is a sensible compromise. Debate on this subject is still permitted on the **#glimpse:matrix.org** (or "Glimpse Community") Matrix channel so long as it does not filibuster other project decisions and day-to-day business.

If an alternative our community supports and does not clash with other organizations/projects/applications is found before 1.0 is released then the name will be changed. If a new name that fulfils that criteria cannot be found in time, then we believe there is enough support within the project and wider community for us to consider the matter settled and stick with "Glimpse Image Editor".

## Code changes
Bobby Moss updated the code-level documentation. `README.md` no longer links to an IRC channel we do not support anymore, `NEWS` lists all the code level changes made so far and `HACKING` has been updated with Glimpse-specific instructions. He has also started working on the macOS build and packaging process.

## Project decisions
There was further discussion on the choice of programming language for the 2.x "UI Rewrite" stream running in parallel. There was a considerable uptick in support for using D instead of Rust in the comments section of this Github issue: https://github.com/glimpse-editor/Glimpse/issues/70

Further progress was made on the application logo and icon designs. [Jaames](https://twitter.com/rakujira) made some interesting suggestions and has started developing those ideas for us. We look forward to seeing what they come up with!

We also determined that we should pledge to donate at least 10% of the Patreon donations we receive for each new release to the GNU Image Manipulation Program as a way of saying thank you for the contributions our fork relies on. That will be in addition to any other contributions we assist them with.

## Website updates
- Bobby Moss updated the FAQs page to reflect recent project decisions and elaborate on how the Glimpse project is governed.
- Clipsey wrote a new page with handy links for potential contributors: https://glimpse-editor.org/contribute/
- Melody generously donated the glimpse-editor.org and glimpse-editor.com domains to the project to fix the clash between getglimpse.app and getglimpse.com.
- The project received several offers to help with the overall website design, and we look forward to seeing the results.
