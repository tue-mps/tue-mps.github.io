---
title: Towards Modeling Vehicles Interactions for the purpose of Path Prediction
date: 2021-08-19
categories: ["Internship"]

image:
  caption: 'Vehicles trajectories. Image credit: [**The rounD Dataset**](https://round-dataset.com/)'
  focal_point: ""
  preview_only: false
---
**Important note: this project is provisional, and the details may be subject to change.**

**Summary:** During this project, you will be able to model the interactions between vehicles to improve trajectory prediction of those vehicles.

<!--more-->
**Type:** Internship

**Starting date:** September 2021

**Supervisor:** Ariyan Bighashdel

**General description:**

Developing Advanced Driving Assistance Systems (ADAS) can play a crucial role in reducing the number of injuries and deaths, related to motor vehicle accidents. Although this is encouraging, ADAS still have significant challenges when it comes to driving in more crowded
areas. In these situations, forecasting the future movements of vehicles is a vital task in producing collision-free paths. However, trajectory prediction of the vehicles has remained a complex problem due to numerous factors, one of which is the interactions between the vehicles.

In the last decades, the subject of interaction modeling has been extensively addressed in the literature for pedestrian path prediction purposes. For many years, researchers heavily relied on traditional approaches with hand-crafted models to interpret the interactions between humans in crowded areas. After the dawn of deep learning, researchers had the opportunity to rely on more learning-based methods to infer the interactions. The developed learning-based methods have shown promising results for pedestrian path prediction in various scenarios with dominating human-human interactions. 

To date, few studies have examined the association between human-human and vehicle-vehicle interaction modeling methods. Therefore, the goal of this project is to develop a vehicle trajectory prediction framework with various interaction modeling methods which are inspired from human-human interaction modeling, and compare them in a well-controlled study. 

**Task description:**
During this project, you will accomplish the following goals:
- Implementing a vehicle path prediction model with an encoder-decoder LSTM network.
- Implementing three human-human interaction modeling methods: 1) discrete social pooling [1] 2) continuous social pooling [2] and 3) graph attention [3], in the vehicle path prediction model.
- Evaluation and comparison of the three interaction modeling methods on the rounD vehicle trajectory dataset [4].

**Prerequisites:**
- Experience with the implementation of recurrent neural networks.

**Interested?** Send an email to a.bighashdel@tue.nl, containing:
- Brief motivation letter
- List of relevant courses and grades


**References**

[1] A. Alahi, K. Goel, V. Ramanathan, A. Robicquet, L. Fei-Fei, and S. Savarese, "Social lstm: Human trajectory prediction in crowded spaces," in Computer Pision and Pattern Recognition (CVPR), 2016, pp. 961-971.

[2] A. Gupta, J. Johnson, L. Fei-Fei, S. Savarese, and A. Alahi, "Social gan: Socially acceptable trajectories with generative adversarial networks," in Computer Pision and Pattern Recognition (CVPR), 2018, pp. 2255-2264.

[3] Y. Huang, H. Bi, Z. Li, T. Mao, and Z. Wang, "Stgat: Modeling spatial-temporal interactions for human trajectory prediction," in International Conference on Computer Vision (ICCV), 2019, pp. 6272-6281.

[4] R. Krajewski, T. Moers, J. Bock, L. Vater, and L. Eckstein, "The rounD Dataset: A Drone Dataset of Road User Trajectories at Roundabouts in Germany," in International Conference on Intelligent Transportation Systems (ITSC), 2020, pp. 1-6.
