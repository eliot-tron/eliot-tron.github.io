---
title: "Adversarial attacks on neural networks through canonical Riemannian foliations"
collection: publications
category: manuscripts
permalink: /publication/2024-11-01-Adversarial-attacks-on-neural-networks-through-canonical-Riemannian-foliations
excerpt: "This paper explores neural network robustness through Riemannian geometry, presenting a novel adversarial attack that highlights the role of curvature in the data space.<br/><img src='/images/2024-TSSA.png'>"
date: 2024-11-01
venue: 'Machine Learning'
paperurl: 'https://arxiv.org/pdf/2203.00922'
citation: 'Tron Eliot, Couëllan Nicolas, Puechmorel Stéphane. (2024). &quot;Adversarial attacks on neural networks through canonical Riemannian foliations.&quot; <i>Machine Learning</i>.'
---

# Abstract
Deep learning models are known to be vulnerable to adversarial attacks. Adversarial learning is therefore becoming a crucial task. We propose a new vision on neural network robustness using Riemannian geometry and foliation theory. The idea is illustrated by creating a new adversarial attack that takes into account the curvature of the data space. This new adversarial attack, called the two-step spectral attack is a piece-wise linear approximation of a geodesic in the data space. The data space is treated as a (degenerate) Riemannian manifold equipped with the pullback of the Fisher Information Metric (FIM) of the neural network. In most cases, this metric is only semi-definite and its kernel becomes a central object to study. A canonical foliation is derived from this kernel. The curvature of transverse leaves gives the appropriate correction to get a two-step approximation of the geodesic and hence a new efficient adversarial attack. The method is first illustrated on a 2D toy example in order to visualize the neural network foliation and the corresponding attacks. Next, we report numerical results on the MNIST and CIFAR10 datasets with the proposed technique and state of the art attacks presented in Zhao et al. (2019) (OSSA) and Croce et al. (2020) (AutoAttack). The result show that the proposed attack is more efficient at all levels of available budget for the attack (norm of the attack), confirming that the curvature of the transverse neural network FIM foliation plays an important role in the robustness of neural networks. The main objective and interest of this study is to provide a mathematical understanding of the geometrical issues at play in the data space when constructing efficient attacks on neural networks. 

![Illustration image for the paper: Two Step Spectral Attack](http://eliot-tron.github.io/images/2024-TSSA.png)
