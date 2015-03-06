---
layout: post
title: "An Ode to Snake Lines"
description: ""
category: optimization
comments: true
tags: [simulation, operations research, teaching,queueing]

---

Recently I guest-taught a class on Business Process Management (unfortunate name for an actually interesting class) at [CU](http://www.colorado.edu/leeds/) for my colleague. 

I went over some basics of creating discrete event simulation models with the students, using a grocery store as a guiding example. We talked about queueing, and compared a snake line (a single line that feeds all cash registers) to separate parallel queues at each cash register.

The following video depicts my biggest problem with having separate queues: lack of fairness and the horrible feeling that you chose the slowest line ever, which causes (at least for me) extreme stress and discontent.

<center><a href="http://www.youtube.com/watch?feature=player_embedded&v=eQa9fPXk9Tw" target="_blank"><img src="http://img.youtube.com/vi/eQa9fPXk9Tw/0.jpg" 
alt="why snake lines are the best" width="70%" border="2"/></a></center>

I asked the students which queueing system is more efficient (has lower average wait time per customer), assuming that once you get in line you can't switch. The answer wasn't really clear to the students! Some thought the snake line would be more efficient (which is correct), but some thought the separate queues would be more efficient because each line is shorter.

And this reasoning is (among other reasons) why we have separate queues in grocery stores. At the cost of fairness, people (incorrectly) perceive that their wait time is shorter. So they are less likely to leave the grocery store due to long lines. And maybe if you're really good at selecting the speediest checkout clerk you can game the system, but I'm apparently supremely bad at that.