---
layout: post
title: "Data ethics and explainability"
description: ""
category: data science
comments: true
tags: [data science, explainability]
---

I've been interested in data ethics, bias in machine learning, and explainability in ML/AI systems ever since I read Cathy O’Neil's book [Weapons of Math Destruction](https://www.amazon.com/Weapons-Math-Destruction-Increases-Inequality/dp/0553418831/) a couple years ago.

<!--![hexagons](/images/data_ethics.jpg)-->

There has definitely been more research activity around explainability recently (it even has an acronym: XAI!), and more discussion around it in industry.

Besides the above book, I recommend the following articles on the topic:

* [Optimization over Explanation](https://medium.com/berkman-klein-center/optimization-over-explanation-41ecb135763d) - this article out of the Berkman center proposes an alternative to requiring explainability by AI systems (since explainability (at least at this point) is often not technically possible). They propose that the optimization governing AI models should be made public, there should be a public body that oversees these optimization objectives/models when the outcome has a large impact on the public, and optimizations need to incorporate a notion of fairness, or some constraints around fairness.

* [Machine Bias](https://www.propublica.org/article/machine-bias-risk-assessments-in-criminal-sentencing) - Fascinating and astonishing article by ProPublica about machine learning models used for criminal sentencing that are racially biased yet completely opaque (people get sentenced with no explanation as to why, and with no ability to see the underlying model or code).

I have anecdotally heard startling reports from friends about autonomuos vehicles shipped with a terrifying lack of testing and confidence around safety. Sometimes safety issues drive change (as has historically been the case in the airline industry), and maybe that's what it will take to bring discussion, regulation, and education around the ethics of ML/AI systems.