---
layout: post
title: "How does Fine-tuning change a model's provenance?"
description: ""
category: ai
comments: true
tags: [LLM]
---

I've been digging into model provenance, or how we trace where large AI models (like LLMs) come from, who trained them, and what they're built on.

One question I've encountered:
*Does fine-tuning change a model's provenance?*

The short answer: **No**

Why? The infrastructure, data, and team behind pretraining leave a lasting fingerprint. Fine-tuning can shape behavior, but it can't erase this history embedded into model weights.

In particular -

**🧪 Behavioral fingerprints linger:** Even after fine-tuning, models retain statistically detectable similarities to their source model. One recent research paper I found shows that black-box testing can identify whether a model is derived from another, even without access to its weights or code.

**🧬 Watermarks can embed identity:** Some developers use training-time watermarking (sometimes via data poisoning) to insert hidden "signatures" into a model's behavior. These marks can persist even through light adaptation, offering a potential way to trace or verify lineage.

**Why this matters:**
It's still the wild west for model selection, modification, and the risks this introduces. As the ecosystem matures and open models become more remixable, we'll need stronger ways to assess ownership, licensing, compliance, and trust.
