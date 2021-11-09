---
title: To Style or Not to Style? A Comparison Between Data Augmentation and
  Style Supression for Domain Generalization
date: 2021-08-25
featured: false
categories:
  - Internship
image:
  caption: "Current domain generalization approaches. Image credit: [1, 2]"
  focal_point: ""
  preview_only: false
---

**Important note: this project is provisional, and the details may be subject to change.**

**Summary:** During this project, you will use an existing network for semantic segmentation and study whether its generalization capacity can be improved by performing either data augmentation or style supression. 

<!--more-->
**Type:** Internship

**Starting date:** September 2021

**Supervisor:** Fabrizio J. Piva

**General description:**

When deep neural networks are trained on a given dataset, there is the assumption that the training and evaluation data are Independent and Identically Distributed (IID), i.e., both sets are independent and drawn from the same underlying distribution. This means that if we wanted to use a deep neural network for a real-world application, we would need to manually label lots of data from that particular scenario in order to build a proper training (and validation) set. However, in dense prediction tasks such as semantic segmentation, labeling large scale data becomes unbearable, and publicly available datasets very likely do not to comply to the IID assumption. On the other hand, ignoring this assumption would make the neural network unusable due to its low performance caused by the large difference between training and evaluation data.

In order to solve this problem, domain generalization methods aim to build and train a neural network with the goal of increasing the performance not only in the (seen) training dataset, but also on multiple (unseen) domains. Recently, several methods for domain generalization in semantic segmentation propose either to 1) augment the training data by creating multiple alternative representations with different style [1], or 2) supress the style component by descomposing the images in style and content, training only with the content [2]. Each approach has its strengths and weaknesses, but to this date no works have made a thorough comparison between these techniques.

Thus, the research question for this proposal is: to style or not to style? Throughout this internship you will find out the answer.

**Task description:**
In this project, you will use a standard semantic segmentation network (for instance, DeepLab v2 [3]) and implement style-based data augmentations as well as style supression techniques for domain generalization. This requires:
- Implementing a relatively fast style transfer method, extending it to multiple representations, ideally without reference image.
- Training the semantic segmentation network with these multiple representations.
- Adapt a style supression technique to the semantic segmentation network.
- Training the semantic segmentation network without the style component.
- Evaluating the resulting models on multiple datasets: seen as well as unseen.

**Prerequisites:**
- Theoretical knowledge about deep neural networks for computer vision.
- Experience with implementing a deep neural network for computer vision.

**Interested?** Send an email to f.j.piva@tue.nl, containing:
- Brief motivation letter
- List of relevant courses and grades


**References**

[1] X. Yue, Y. Zhang, S. Zhao, A. Sangiovanni-Vincentelli, K. Keutzer and B. Gong, "Domain Randomization and Pyramid Consistency: Simulation-to-Real Generalization Without Accessing Target Domain Data", IEEE/CVF International Conference on Computer Vision (ICCV), 2019, pp. 2100-2110.

[2] Choi, Sungha, Sanghun Jung, Huiwon Yun, J. Kim, Seungryong Kim and J. Choo. "RobustNet: Improving Domain Generalization in Urban-Scene Segmentation via Instance Selective Whitening." ArXiv abs/2103.15597, 2021.

[3] L. C. Chen, G. Papandreou, I. Kokkinos, K. Murphy and A. L. Yuille, "DeepLab: Semantic Image Segmentation with Deep Convolutional Nets, Atrous Convolution, and Fully Connected CRFs", IEEE Transactions on Pattern Analysis and Machine Intelligence, vol. 40, no. 4, pp. 834-848, 2018.
