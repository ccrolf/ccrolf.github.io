---
layout: post
title: "If AI is so productive, where are the products?"
date: 2026-05-01
---

Under all the conversation about AI productivity, there's an honest question without a good answer: if the productivity gains are real, where are the products?

We've all shipped hobby projects and prototypes ten times faster than in the past. But enterprise delivery metrics haven't moved. The tools are the same, so the gap is something else.

# The productivity-risk relationship

Think of software delivery as having two levers: productivity and risk. They are coupled, increase output and you increase risk. More features means more operational surface area and more failure modes. Increase risk and your productivity goes down. Higher risk means more incidents, more post-incident reviews, and tired developers.  

This relationship explains most of the technology transitions in software engineering, and it explains the AI productivity gap.

Java made large engineering organizations possible. Performant garbage collection removed an entire class of production failures. The verbosity came with legibility and safety that enabled larger teams to move faster. A low price to pay for the safety it brought at scale.

Python and Javascript made startups fast. Dynamic typing and less verbosity accelerated prototyping. But they also introduced new production risks. It was a good fit for startups and a poor fit for enterprises.

The productivity gain from any technology is real. But it's conditional on whether your risk tolerance matches what that technology requires.

And AI demands a far higher risk tolerance than anything before it.

A solo developer working on a hobby project captures the productivity gain at the extreme risk tolerance. Startups building MVPs can still capture huge gains. But an enterprise with a huge userbase and high reliability commitments struggles to gain much at all.


# The lever that hasn't been pulled

The productivity gain at enterprise scale doesn't come from generating production code faster. It comes from shifting where AI gets used. Using AI for prototyping features with PM, design, and customers in the room eliminates the need for multiple design iterations. Features that previously became great through multiple iterations spanning severla months can now be validated in hours.

The productivity gain isn't in writing production code faster. It's in shifting perspective to the customer outcome. Instead of measuring lines of code produced, measure the time from an idea to happy customers.

That's why the products aren't here yet. Nobody has pointed the productivity at the right part of the cycle yet.

