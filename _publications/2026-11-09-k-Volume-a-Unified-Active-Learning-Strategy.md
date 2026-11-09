---
title: "k-Volume: a Unified Active Learning Strategy"
collection: publications
category: manuscripts
permalink: /publication/2026-11-09-k-Volume-a-Unified-Active-Learning-Strategy
excerpt: "This preprint introduces a novel active learning method based on density etimation with kNN. <br/><img src='/images/kVol_basics.png'>"
date: 2026-11-09
venue: 'ArXiv'
paperurl: 'https://arxiv.org/abs/2611.09388'
citation: 'Tron, E., Celisse, A., Denis, C., & Le Brigant, A. (2026). k-Volume: A Unified Active Learning Strategy (arXiv:2611.09388). arXiv. https://doi.org/10.48550/arXiv.2611.09388'
---

# Abstract

In the classification context where revealing the label of a sample is costly, we propose a new Active Learning (AL) strategy named k-Volume (kVol). It randomly selects a sample to be labeled according to the volume of the smallest ball containing its k nearest neighbors. kVol is highly versatile: it can be applied either in the input space or in the output space, and it enjoys the desirable properties of the three main families of AL strategies: density, diversity, and (when performed in the output space) uncertainty. From a theoretical perspective, we establish that kVol is asymptotically equivalent to uniform sampling over the support of the (input or output) data distribution. Based on experiments on various synthetic and real-life tabular datasets and images, we observe that kVol is surprisingly stable: whatever the classifier or the experimental setup, it still lies among the best AL strategies unlike other competitors that fail dramatically. In particular, kVol outperforms state-of-the-art competitors such as CoreSet, TypiClust or Uncertainty on several real-life datasets, at a low computational cost.

![Illustration image for the paper: k-Volume](http://eliot-tron.github.io/images/kVol_basics.png)
