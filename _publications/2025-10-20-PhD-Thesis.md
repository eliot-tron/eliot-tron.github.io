---
title: "The geometry of neural networks : a Riemannian foliation perspective on robustness."
collection: publications
category: thesis
permalink: /publication/2025-10-20-PhD-Thesis
excerpt: "My PhD Thesis, which I defended on the 20th October 2025.<br/><img src='/images/2025-10-20-PhD_thesis_robustness.png'>"
date: 2025-10-20
venue: 'HAL'
paperurl: 'https://enac.hal.science/tel-05391126'
slidesurl: 'https://eliot-tron.github.io/files/Soutenance_Tron.pdf'
citation: 'Tron, E. (2025). The geometry of neural networks: A Riemannian foliation perspective on robustness. (Publication No. 2025ENAC0004) [Theses, ENAC Toulouse]. https://enac.hal.science/tel-05391126'
---

# Abstract
In this thesis we employ the tools of geometry and statistics to shed light on the relationship between data and neural network predictions. In particular, we draw inspiration from the field of information geometry which combines precisely these two approaches. We interpret the neural network’s output as the parameter of a probability distribution. By using the Data Information Matrix (DIM), a variation of the Fisher Information Matrix (FIM), we investigate the network’s input/output relationship and reveal its understanding of the data structure. This statistical framework yields a (degenerate) Riemannian metric that we use to analyze the geometry of the data. In particular, we lean on a foliation arising from the kernel of the DIM to conduct our study of the low-dimensional data in the high-dimensional input space. We first employ the language of Cartan moving frames to compute the connection and curvature of the DIM in a efficient way, and give some explanations on the response of a neural network through experiments. Unfortunately, in most practical cases of machine learning, the DIM is characterized by a non-constant rank and non-smoothness, making it difficult to yield a well defined foliation. To tackle this issue, we prove that for usual neural network architectures, this only happens in a nowhere dense set. Besides, we investigate these singularities as they may tell us about distances between datasets and efficiency of knowledge transfer. Finally, we apply this new geometrical framework given by the DIM to the analysis of the robustness of neural networks. We show that the curvature of the transverse to the kernel leaves can be utilized to improve adversarial attacks, indicating that the geometry of the data is key in the robustness of machine learning algorithms.

![Illustration image for the paper: robustness of neural networks](https://eliot-tron.github.io/images/2025-10-20-PhD_thesis_robustness.png)
