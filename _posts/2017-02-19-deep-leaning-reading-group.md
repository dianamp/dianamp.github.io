---
layout: post
title: "Deep Learning: a study guide"
description: ""
category: machine learning
comments: true
tags: [deep learning, machine learning, data science]
---
![study-group](/images/people-coffee-notes-tea.jpg)

I've recently started a reading group with the friends focused on deep learning. We meet each week at a [great coffee shop](https://ozocoffee.com/), go over an assigned reading or project, and ask each other lots of questions. At least, that's the goal!

As background, everyone in the group has experience with machine learning and is pretty mathematically sophisticated. But the only real pre-requisite when I form a group like this is that everyone is friendly, collaborative, and a non-show off.

### Weekly readings
Here are the readings we've done each week. This may be useful if you'd also like a gentle way into deep learning or would like to form a study group of your own. Of course, with hind sight, we would have changed up some of the readings and order, but this is still a good place to start.

#### Week 1
Read [this](http://www.cs.toronto.edu/~hinton/absps/NatureDeepReview.pdf) survey paper and get on the same page about goals for the reading group.

#### Week 2
Go through [this](http://iamtrask.github.io/2015/07/12/basic-python-network/) super simple tutorial on implementing a neural network in very few lines of code. There's a part two that would also be appropriate to read here for those inclined.

#### Week 3
Read the chapter on [autoencoders](http://www.deeplearningbook.org/contents/autoencoders.html) from the [Deep Learning Book](http://www.deeplearningbook.org/). Autoencoders sort of blow my mind.

#### Week 4
Go through [this](https://github.com/aymericdamien/TensorFlow-Examples/blob/master/examples/3_NeuralNetworks/autoencoder.py) example of on autoencoder on the MNIST dataset. Involves Tensorflow so those who haven't tensorflow and read [this](https://www.tensorflow.org/tutorials/mnist/tf/) tutorial.

Had a great argument (heated discussion?) on whether autoencoders can be classified under supervised learning.

#### Week 5
Read Chapter 6 of the [Deep Learning Book](http://www.deeplearningbook.org/) - it's an introductory chapter on feedforward neural networks. Some of us also read the first 5 chapters of the book as a nice refresher and different perspective on linear algebra, numerical methods, machine learning, and probability. I also liked reading [this](http://colah.github.io/posts/2015-09-Visual-Information/) great explanation of information theory (makes cross entropy crystal clear).

I really loved this chapter! Highly recommended.

#### Week 6
Implement a feedforward neural network to train [NMIST](http://yann.lecun.com/exdb/mnist/). Similar to the autoencoder exercise, but this time try to do it from scratch using Tensorflow 1.0, which just came out, and is not exactly backwards compatible with the code we wrote beforehand. Also spend some time getting familiar with [Tensorboard](https://www.tensorflow.org/get_started/summaries_and_tensorboard).

##### Week 7
The plan is to move onto recurrent neural networks! Will post Part 2 with follow-on topics. I'm really psyched to auto-generate some poetry.
