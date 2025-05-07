---
layout: post
title: "The Decentralized Development Paradox"
date: 2025-04-23 01:57:39 -0500
categories: bitcoin coredev decentralization paradox
permalink: /bitcoin-core-decentralization-paradox
---

The decentralized development paradox is simple – decentralized development processes that give bitcoin its strength and resilience come at a significant cost to efficiency and effectiveness. The tension this creates looms over [Bitcoin Core](https://github.com/bitcoin/bitcoin/) the software project, where nobody is "in charge," and therefore, nobody is compelled to do anything.

This raises a series of challenging questions:

1. How does the project coordinate priorities when everyone has absolute freedom to choose what they work on?

2. Who maintains abandoned code when contributors move on?

3. When should features be removed versus preserved?

4. How do you balance accountability in a system where everyone's supposed to help but no one is obligated?

## **What’s a Core Dev?**

Bitcoin Core is not an organization with a formal structure. It's a software project. There is a [GitHub Org](https://github.com/bitcoin/) and maintainers with merge keys. There is a [website](https://bitcoincore.org/) where binaries are posted. There is a [coredev](https://coredev.tech/) in-person gathering. But there is no official designation of who is a core dev or not. When people refer to "core devs," they usually mean individuals who work full-time on the Bitcoin Core codebase. The current group of contributors spans six continents, supported by a variety of funding sources, with varying levels of education and professional backgrounds.

What's remarkable is that despite this loose structure, Bitcoin Core has maintained an impressively stable track record. This achievement masks a concerning reality – an embarrassingly small team maintains the infrastructure that supports an asset with the market cap comparable to the seventh most valuable company. CVEs have been handled by a small group [without public disclosures](https://groups.google.com/g/bitcoindev/c/Q2ZGit2wF7w/m/RqqmU2B9AAAJ). Priorities [have been opaque](https://gist.github.com/adamjonas/aa5e7a46bff8111a1b41285a195c0937). You could be forgiven for imagining that this is run by a bunch of volunteers because… well, it is.

## **Bitcoin’s Volunteer Firefighters**

Meet bitcoin's volunteer fire department.

![bitcoin's volunteer fire department](/images/core-dev-firefighters.png)

I'm from a small town so these are my kind of people, but you cannot expect them to cover much more than a rural village. It's not fair to them and it's dangerous for anyone living in a densely populated area. Bitcoin has grown from a niche experiment to a global financial asset, but its development infrastructure hasn't scaled accordingly.

At the heart of the decentralization paradox lies an existential question: Who is Bitcoin Core for? Is it for raspberry pi users in Kenya, is it a "scratch your itch" project where the core devs work for themselves, or is it for a more general audience including the exchanges and the ETFs?

The "scratch your own itch" approach is mostly how we got here. Developers naturally want to write code. Professional freedom is a primary reason why core devs choose this line of work. But each new feature added to Bitcoin Core creates a maintenance burden.

Funding drives much of this. Grant applications typically require developers to produce something tangible. Few neophytes would dare to request funding simply to review and test other's work or braver yet, to take something out of the codebase. This creates a problematic incentive structure where adding features is rewarded, while the crucial work of maintenance, review, and simplification goes unaccounted for and undervalued.

![grant applications](/images/grant-applications.png)

## **The Fear of Centralizing Influence**

There are real reasons to defend the decentralization properties that make bitcoin unique, but perhaps the most insidious aspect of the decentralized development paradox is the accompanying anxiety that core devs experience around the optics of exerting centralized control. In their attempts to maintain bitcoin's decentralized ethos, developers err on hesitating to provide strong direction, even when it would benefit the project. Despite the *many* conspiracy theories, Core devs are so sensitive to the mere appearance of bad intentions or centralized authority that they mostly keep their opinions to themselves. And so, very few responsibilities actually get assigned to anyone.

This fear creates a leadership deficit where necessary functions like allocating resources to critical areas, directing new contributors to useful work, or paying for essential infrastructure like who pays the bill for the CI are left to signal chats. This means even basic coordination becomes an outsized challenge. Experiments with [priority projects](https://gist.github.com/adamjonas/aa5e7a46bff8111a1b41285a195c0937) and working groups are handicapped because they conflict with the principle that every contributor has absolute choice over what they think is most important. This results in a frustratingly slow pace of development.

When developers do speak up about project direction, such as pushing back against [adding new features](https://github.com/bitcoin/bitcoin/pull/27854#issuecomment-1586988190) due to maintenance concerns, they risk being labeled as obstructionists rather than pragmatic stewards of the codebase.

## **Two Paths Forward**

![two paths](/images/two-paths.png)

Bitcoin Core faces a critical juncture. It either needs to commit to serving the masses with a project that is generic, boring and safe (which means saying no to more and stomaching the idea of leaving real people out) or increase development capacity by bringing more contributors. I spend a lot of time recruiting new devs, but I’m not optimistic that we can onboard them fast enough to deal with today's reality, let alone tomorrow’s.

The decentralization paradox may never be fully resolved. It may, in fact, be essential to Bitcoin Core's identity. But understanding this tension hopefully helps us appreciate just how incredible Bitcoin Core is as a project. A global financial system that runs 24/7 maintained by a diverse group of individuals working together without centralized authority. It’s a frickin’ miracle.
