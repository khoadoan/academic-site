---
title: "LIRA: Learnable, Imperceptible and Robust Backdoor Attacks"
publication_types:
  - "1"
authors:
  - Khoa D Doan
  - Yingjie Lao
  - Weijie Zhao
  - Ping Li
publication: "*Proceedings of 2021 International Conference on Computer Vision*"
abstract: Recently, machine learning models have been demonstrated to be
  vulnerable to backdoor attacks, primarily due to the lack of transparency in
  black-box models such as deep neural networks. A third-party model can be
  poisoned such that it works adequately in normal conditions but behaves
  maliciously on samples with specific trigger patterns. However, in most
  existing backdoor attack methods, the trigger injection function is manually
  defined, e.g., placing a small patch of pixels on an image or slightly deform
  the image before poisoning the model. This results in a two-stage approach
  with a sub-optimal attack success rate and a lack of complete stealthiness
  under human inspection.  In this paper, we propose a novel and stealthy
  backdoor attack framework, LIRA, which jointly learns the optimal, stealthy
  trigger injection function and poisons the model. We formulate such an
  objective as a non-convex, constrained optimization problem. Under this
  optimization framework, the trigger generator function will learn to
  manipulate the input with imperceptible noise, with the goal of preserving the
  model performance on the clean data and maximizing the attack success rate on
  the poisoned data. Then, we solve this challenging optimization problem with
  an efficient, two-stage stochastic optimization procedure. Finally, the
  proposed attack framework achieves 100% success rates in several benchmark
  datasets, including MNIST, CIFAR10, GTSRB, and Tiny-ImageNet, while
  simultaneously bypassing existing backdoor defense methods and human
  inspection.
draft: false
featured: false
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2021-07-22T23:44:31.591Z
---
