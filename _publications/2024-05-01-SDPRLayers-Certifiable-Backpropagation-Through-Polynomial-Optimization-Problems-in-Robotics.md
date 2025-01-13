---
title: "SDPRLayers: Certifiable Backpropagation Through Polynomial Optimization Problems in Robotics"
collection: publications
permalink: /publication/2024-05-01-SDPRLayers-Certifiable-Backpropagation-Through-Polynomial-Optimization-Problems-in-Robotics
date: 2024-05-01
venue: 'arXiv:2405.19309'
citation: ' Connor Holmes,  Frederike D{\&quot;u}mbgen,  Timothy Barfoot, &quot;SDPRLayers: Certifiable Backpropagation Through Polynomial Optimization Problems in Robotics.&quot; arXiv:2405.19309, 2024.'
---

**Abstract**: Differentiable optimization is a powerful new paradigm capable of reconciling model-based and learning-based approaches in robotics. However, the majority of robotics optimization problems are non-convex and current differentiable optimization techniques are therefore prone to convergence to local minima. When this occurs, the gradients provided by these existing solvers can be wildly inaccurate and will ultimately corrupt the training process. On the other hand, any non-convex robotics problems can be framed as polynomial optimization problems and, in turn, admit convex relaxations that can be used to recover a global solution via so-called certifiably correct methods. We present SDPRLayers, an approach that leverages these methods as well as state-of-the-art convex implicit differentiation techniques to provide certifiably correct gradients throughout the training process. We introduce this approach and showcase theoretical results that provide conditions under which correctness of the gradients is guaranteed. We demonstrate our approach on two simple-but-demonstrative simulated examples, which expose the potential pitfalls of existing, state-of-the-art, differentiable optimization methods. We apply our method in a real-world application: we train a deep neural network to detect image keypoints for robot localization in challenging lighting conditions. An open-source, PyTorch implementation of SDPRLayers will be made available upon paper acceptance.

Use [Google Scholar](https://scholar.google.com/scholar?q=SDPRLayers:+Certifiable+Backpropagation+Through+Polynomial+Optimization+Problems+in+Robotics){:target="_blank"} for full citation