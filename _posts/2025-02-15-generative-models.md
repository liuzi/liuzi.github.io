---
layout: post
title: Generative Models
date: 2025-02-15 21:10 +0800
math: true
---


## Introduction of Generative Models

When talking about **generative models**, we need to know how machine learnings is modeling a problem. Considering a classification problem that distinguishes between elephants and dogs, there are two ways to achieve it:

1. We can build a model to predict **classification labels** or to find **decision boundary** between elephants and dogs.
2. We can firstly build two models of what elephants and dogs look like respectively, and match the new coming animal against each model, to see **which one it looks more like**.

The first approach is called discriminative modeling, directly learning the probability of labels given features or input data $p(y|x)$ like logistic regression, or finding the decision boundary and mapping the new coming animal to the labels ${0, 1}$ like perceptron algorithm. And the second one is generative modeling, learning the joint distribution $p(x,y)$ or $p(x|y)$ (and the prior probability $p(y)$).  







## References

[1] Ng, Andrew. "CS229: Machine Learning Course Notes." Stanford University, 2018.


