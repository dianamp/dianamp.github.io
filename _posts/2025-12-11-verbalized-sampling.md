---
layout: post
title: "How to generate diverse LLM responses"
description: ""
category: ai
comments: true
tags: [LLM]
---

This paper on "verbalized sampling" describes a surprisingly simple and effective way to get diversity out of an LLM, avoiding mode collapse. It's a fun one!

Let's say you're trying to:
👉 generate synthetic data or personas for training (actual use case from one of my clients), or
👉 brainstorm ideas for writing (actual use case for… me).

Most of us do the classic thing:
*"Give me 5 ideas for X."*, or re-generate one response a few times

The model happily gives you… 5 copies of the same idea wearing different hats.
This paper explains why, and gives a dead-simple fix.

**🧩 The core issue: mode collapse**
Aligned (aka post-trained) models tend to collapse onto a single "most typical" answer.

The paper shows that this is due to **typicality bias** that is baked directly into human preference data: Humans upvote familiar, obvious answers → reward models sharpen toward those → your LLM outputs get narrower and narrower.
(See the authors' example: 5 identical coffee jokes 😬)

This is why creative tasks, brainstorming, persona generation, and synthetic data often feel… same-y.

**🪄 The fix: Verbalized Sampling**
Instead of asking for 5 ideas, you ask:

🎨 *"Generate 5 ideas with their probabilities."*

This one change pushes the model to internally explore a distribution of possible responses, which turns out to approximate the full diversity of the base model (aka the pre-trained but not post-trained model) rather than the post-trained one.

The result: **way more variety!** The paper reports **1.6-2.1x more diversity** in creative writing, without sacrificing quality.

Link to the paper: [Verbalized Sampling: How to Mitigate Mode Collapse and Unlock LLM Diversity](https://arxiv.org/abs/2510.01171)
