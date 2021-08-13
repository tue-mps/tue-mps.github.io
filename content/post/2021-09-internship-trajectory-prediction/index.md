---
title: Pedestrian Path Prediction via Imitation Learning with Inverse Reinforcement Learning
date: 2021-08-13
categories: ["Internship"]

image:
  caption: 'Pedestrian Path Prediction. Image credit: [**Trajectory Dataset for Urban Traffic**](http://apolloscape.auto/trajectory.html)'
  focal_point: ""
  preview_only: false
---
**Important note: this project is provisional, and the details may be subject to change.**

**Summary:** During this project, you will apply a state-of-the-art imitation learning algorithm to the task of pedestrian path prediction.

<!--more-->
**Type:** Internship

**Starting date:** September 2021

**Supervisor:** Ariyan Bighashdel

**General description:**

Pedestrian path prediction is an important problem in computer vision, with various applications such as autonomous vehicles and video surveillance. Despite significant progress over the past years, pedestrian path prediction has remained a complex problem, far from being solved. 

The problem of pedestrian path prediction in the literature has been formulated in various ways, but conceptually all try to answer the following simple question:

"<em>Observing available information for a specific period of time, what will be the future positions of a target pedestrian in the next period of time?</em>"

The proposed formulations may fundamentally differ in providing an answer to the above question. Path prediction approaches can be generally formulated as either a supervised learning (SL) problem or an imitation learning (IL) one. In the SL formulation, the idea is to train a (deep) model with a set of training input-output pairs. On the other hand, in the IL formulation, the goal is to train an agent to mimic the behavior of pedestrian from a set of (expert) pedestrian demonstrations.

To date, the SL formulation of the pedestrian path prediction task has received scant attention in the research literature and there is a surprisingly little amount of studies comparing two proposed formulations. Therefore, the goal is to compare both formulations in a well-controlled study.

**Task description:**
During this project, you will accomplish the following goals:
- Running an available pedestrian path prediction model with the encoder-decoder LSTM network.
- Running an available deep reinforcement learning algorithm for a general robotics task.
- Implementation of a pedestrian path prediction model using Generative Adversarial Imitation Learning [1]. 
- Evaluation and comparison of the two prediction models in a well-controlled study.

**Prerequisites:**
- Experience with implementation of recurrent neural networks.
- General knowledge about reinforcement learning and/or high motivation to learn.
- Familiarity with simulation environments, (e.g. gym) and/or high motivation to learn


**Interested?** Send an email to a.bighashdel@tue.nl, containing:
- Brief motivation letter
- List of relevant courses and grades


**References**

[1] J. Ho and S. Ermon, “Generative adversarial imitation learning,” in Advances in Neural Information Processing Systems, 2016, pp. 4565–4573.
