---
layout: post
title: "Try Less, Think More"
description: ""
category: events
comments: true
tags: [data, analyze boulder, machine learning]                                                                                                
---
Way back in December, [Owen Zhang](https://www.linkedin.com/pub/owen-zhang/51/aa0/363) of [Data Robot](http://www.datarobot.com) gave an excellent talk to [Analyze Boulder](http://www.meetup.com/Analyze-Boulder/)[^1] (which I co-organize). As the leaderboard winner at [Kaggle](http://www.kaggle.com/), his talk was ostensibly about how he wins data science competitions. But what I took away was an amazingly optimistic philosophy of machine learning. Optimistic in contrast to my fairly cynical (in the most loving way) view, which I have really questioned every since.

Whenever I work on a supervised learning task/project, I cynically take a “throw everything but the kitchen sink at the thing” approach wherein I furtively brainstorm/create tons of features, do a bunch of analysis on them, and then run pretty much the entire gammut of learning algorithms against the thing. I feel like I don't really know in advance what will work, since machine learning is so heuristic in nature (at least, when working with real world projects/data and not just perfectly coiffed used-for-teaching data sets).

It was refreshing to hear a completely different approach from Owen. One gem from Owen, which is directly counter to my “try everything” approach, is his guiding principle to “think more, try less” in order to create the best learners while avoiding over-fitting. Whenever he runs a learner against the Kaggle public test set, he considers that a loss of a degree of freedom, and tries to minimize these “peeks at the test data”. I definitely plan to take some inspiration from this on future projects. Or maybe I'll still try everything, but also spend a lot more time thinking (and acquiring some domain knowledge).

He also talked about using GBM (gradient boosting) as his “crutch” algorithm of choice, which I found interesting.

[^1]: This event was co-hosted with the [Leeds School of Business](http://www.colorado.edu/leeds/) at CU.