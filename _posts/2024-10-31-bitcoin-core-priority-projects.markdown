---
layout: post
title: "Evolution of Bitcoin Core Priority Projects"
date: 2024-10-31 13:57:39 -0500
categories: bitcoin coredev priorities
permalink: /bitcoin-core-priority-projects
---

In April 2023, Bitcoin Core developers initiated the Priority Projects experiment to address a recognized bias in the development process towards smaller patches over more significant projects. The initiative aimed to help maintainers prioritize significant projects when facing competing demands for review attention.

## First Iteration: A Promising Start

The initial implementation used a straightforward approach:

* Projects were voted on using a whiteboard tally system
* Selections were discussed in subsequent IRC meetings
* Each project required a dedicated champion
* Champions provided weekly progress updates in IRC meetings

The [first round](https://github.com/bitcoin-core/bitcoin-devwiki/wiki/Priorities) proved highly successful:

* AssumeUTXO, previously stalled for years, was successfully merged
* BIP324 reached completion and was merged
* The Kernel project made substantial progress
* Only Package Relay faced significant challenges

## Second Iteration: Structural Changes

The second round selected:

* Package Relay (again)
* Multiprocess
* Silent Payments

Changes to the selection process included:

* Project selection moved from the Core Dev meetup to the broader Bitcoin GitHub Organization
* [Gathering](https://github.com/bitcoin/bitcoin/issues/28599) and [voting](https://github.com/bitcoin/bitcoin/issues/28642) occurred through GitHub issues
* Results were mixed, with Silent Payments showing exceptional progress due to increased in-person collaboration
* Notably, Silent Payments maintained momentum even after being removed as a priority project, demonstrating the effectiveness of the working group model

## Third Iteration: Continued Challenges

The third round selected:

* Package Relay (again!)
* Cluster Mempool
* Legacy Wallet Removal

Observations from this phase:

* [Gathering](https://github.com/bitcoin/bitcoin/issues/29439) and [voting](https://github.com/bitcoin/bitcoin/issues/29465) remained on GitHub issues
* Overall progress remained below expectations
* Core Developers emphasized that priority selection should represent a commitment to review and support, not merely feature preference
* While progress reporting was valuable, priority status didn't significantly increase reviewer participation

## Trying Something Else: Working Groups

Recent Core Dev discussions led to a structural shift toward a more organic approach:

* Adoption of the [Working Groups model](https://github.com/bitcoin-core/bitcoin-devwiki/wiki/Working-Groups), building on proven collaborative patterns
* Retention of key elements:
  * Project champions maintain responsibility for progress
  * Regular progress IRC reporting continues (see [IRC report dates column](https://github.com/bitcoin-core/bitcoin-devwiki/wiki/Working-Groups))
  * Champions coordinate communication and serve as primary contacts
* Changes:
  * Elimination of formal voting process
  * Removal of artificial limits on priority project numbers

### Working Group Best Practices

* Focus on practical collaboration over formal processes
* No requirement to seek consensus from those not actively contributing to the work. Thoughtful review and criticisms should be taken into account no matter the source, but those with "skin in the game" should ultimately have the loudest voices.
* Communication methods:
  * Signal groups have proven effective and remain accessible to interested participants
  * Weekly video calls enhance motivation and improve team communication
  * Public IRC channels showed limited utility and were eventually abandoned
* Project management essentials:
  * Track tasks and deliverables (e.g. Bitcoin Core GitHub issues) 
  * Maintain regular meeting notes, ideally in a public and accessible way unless there is a compelling reason not to
  * Work can happen outside the Bitcoin Core repo to reduce friction and avoid cluttering the main repository

There are trade-offs between public transparency and private collaboration, but it's clear there is no substitute for the efficacy of in-person meetings focused on specific goals. For example, the silent payments and kernel working groups have assembled a few times to do a week together, in a physical location. These weeks have been reported to be extremely productive and could serve as a model for other working groups. When planning in-person meetups, perhaps consider holding these in accessible (visa / distance), inexpensive, varied location types to encourage attendance.

## Looking Forward

It remains to be seen whether this new iteration will yield better results, but Core Devs are Bitcoin Core optimists who strive to foster collaboration and drive forward impactful features. Many past contributors have expressed their frustration of not being able to ship significant features on a timeline they found reasonable. Our hope is that this experimentation will help.
