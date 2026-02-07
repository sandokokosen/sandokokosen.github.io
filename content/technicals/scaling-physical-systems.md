---
author: ["Sandoko Kosen"]
title: "On scaling physical systems"
date: "2026-02-07"
tags: ["scaling"]
draft: true
showTableOfContents: true
showHeadingAnchors: true
---

It is rarely straightforward to take a physical system and build a “bigger” version of it, however one chooses to define bigger.

In our line of work, this is a recurring theme, and my own journey over the past few years has taught me one or two things about it. My understanding will evolve, and I hope to refine these thoughts over time.

First, let me be a bit more precise about what I mean.

By physical systems, I refer to systems whose behaviour is primarily governed by physical laws that we believe we understand reasonably well.

Why bother defining it in such an abstract way? Because scaling is usually hard, and it helps to know that we at least understand the rules of the game—or to be confident that those rules are within reach.

The first, and most important, step is to know where you stand: what lies in front of you, and what lies behind you.

With that in mind, I would start by exploring three classes of questions.

**First, we canvas the existing technological landscape. Think broadly, even if you are not explicitly required to.**
* What technologies, down to small-scale or proof-of-concept demonstrations, exhibit features similar to what we ultimately want to scale, and do so with demonstrably decent performance? This is meant to kick-start the process and to ground our thinking in what has already been achieved.

* For each of these, do we understand the mechanisms that underlie the demonstrated performance? Fundamentals matter. At least in my approach, it is useful to confront them early.

* Do we understand what limits their performance, and whether there are reasonable arguments that these limits can—or cannot—be pushed further? This point is subtle. It is not only about improving performance, if that is even possible, but about understanding the assumptions that may have been valid in the past and may no longer hold in the future.

* It is equally important to understand the technologies that were excluded because they were deemed unfeasible. Understand the what and the why. You do not want to be blindsided.

**Second, we go beyond scaling “quantity” and think more structurally.**

* Are there new topologies or features, beneficial or detrimental, that only emerge, or become apparent, at larger scales? This is often where innovation begins. Early pioneers, understandably, tend to focus on proof-of-concept demonstrations and may not explore questions like these in depth.

* Can these emergent features be leveraged, or must they be avoided? “Good” or “bad” is always relative to the metrics we care about, and those metrics themselves may become obsolete as scale increases or as neighbouring technologies evolve.

* Can we imagine combining multiple approaches, in an attempt to extract the best of several worlds into a single system?

* Of the technologies previously excluded, might some become relevant again at larger scales, either because earlier assumptions no longer apply or because the once-promising alternatives have revealed their own limitations?

* Will we still be able to achieve the desired functionality at the level of performance demonstrated today? If not, how might we push it to the required point? In practice, scaling performance is often much harder than scaling size.

* Are there new performance metrics that are negligible at small scales but become dominant at larger ones?

**Third, we look outward and consider how the system interacts with everything around it.**

* What external inputs are required to operate the system at this scale, and at what level of performance? If the system does not operate in isolation, then all supporting technologies must meet their own performance requirements.

* Is it reasonable to expect that these surrounding technologies will be ready, and mature enough, to support the system by the time it reaches the intended scale?

This list is intentionally broad. In practice, we rarely have the time or resources to explore every question in depth. Still, it should provide a wide enough exposure to help orient the thinking and to identify where deeper work is most needed.

I would also like to close by noting that there is rarely a single way to scale a system. Different scaling pathways are often not comparable in any absolute sense, as they are shaped by distinct constraints, assumptions, and performance metrics.

It is not always productive to see one part of a community criticising the scaling choices made by another. Without a clear understanding of the constraints they operate under, or the metrics they are optimising for, such comparisons are difficult to justify.

With enough exposure, one comes to appreciate the diversity of scaling strategies, and to observe how different choices can perform surprisingly better—or worse—than initially expected. There is value in allowing multiple paths to be explored in parallel, even when their merits are not immediately obvious.