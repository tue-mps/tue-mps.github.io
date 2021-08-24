---
title: Teach a driving agent what it cannot see
date: 2021-08-19
categories: ["Internship"]

image:
  caption: 'Risk-aware decision-making'
  focal_point: ""
  preview_only: false
---

**Important note: this project is provisional, and the details may be subject to change.**

**Summary:** During this project, you will implement, train and evaluate a Reinforcement Learning method for driving in a 3D simulation enviornment

<!--more-->
**Type:** Internship

**Starting date:** September 2021

**Supervisor:** Arash Roomi Zadeh

**General description:**

Safe navigation in urban environments remains a challenging problem for autonomous vehicles.  Reinforcement Learning (RL) algorithms have shown great success in many behavior generation applications when the agent has access to a  reliable state signal such as video game playing tasks. This motivates researchers to also use RL for decision-making for automated driving.  Despite these achievements, the state-of-the-art RL methods for automated driving still cannot achieve safety requirements for real-world autonomous driving. This is due to both non-practicality of training in the real world, the uncertain nature of the observations, and  the stochastic nature of the driving environment.  

Traditionally, RL algorithms choose actions that maximize mean return value. This is desired in domains in which failure has a low impact.  However, in real-world driving tasks,  events with low probability but a high impact (e.g., rare collision types) also play a critical role in policy generation. This motivates using risk evaluation for policy generation for decision-making. Risk-sensitive optimization of distributional DQN networks has been employed in fields in which risk-avoidance is critical and has got promising results. 

The first goal of this internship is to implement a Distributional Reinforcement Learning algorithm and use it for driving policy risk evaluation. Secondly, the aim is to provide this algorithm with extra information about uncertainty such as detection accuracy and occlusions, to generate safe driving policies. 

We use two environments for training and evaluation, a 2D gym environment and a realistic 3D simulation environment (CARLA). 

**Task description:**
During this project, you will carry out the following tasks:
- Implement and evaluate a baseline Distributional Reinforcement Learning (DRL) agent in the CARLA environment. For this task, you will need to integrate a scene understanding method such as semantic segmentation with a DRL agent.
- Train and evaluate a baseline agent in presence of observation uncertainties.
- Train and evlauate an agent provided with the observation uncertainty information.

**Prerequisites:**
- Good programming and neural networks implementation skills.
- Theoretical knowledge about neural networks.
- General knowledge about reinforcement learning and/or high motivation to learn.

**Interested?** Send an email to a.roomi.zadeh@tue.nl, containing:
- Brief motivation letter
- List of relevant courses and grades


**References and further reading**
- [1] [The CARLA Autonomous Driving Leaderboard](https://www.youtube.com/watch?v=-L9VuPpzVdQ)
- [2] M.G. Bellemare, W. Dabney, R. Munos, "A Distributional Perspective on Reinforcement Learning", International Conference on Machine Learning 2017.
