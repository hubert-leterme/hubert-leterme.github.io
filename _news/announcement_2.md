---
name: talk_rutgers
layout: post
title: Talk at Rutgers University, NJ. Video available!
date: 2022-06-29 14:00:00-0000
youtubeId: ENAktoBzjJs
inline: false
---

Back from CVPR in New Orleans, I had the pleasure to visit [Yassine Laguel](https://yassine-laguel.github.io/) at [Rutgers Business School](https://www.business.rutgers.edu/) in New Brunswick, NJ. I gave a talk about **shift invariance of feature extractors in convolutional neural networks**.

### Abstract

When trained on natural image datasets, convolutional neural networks (CNNs) tend to learn first-layer parameters that closely resemble oriented Gabor filters. By leveraging the properties of discrete Gabor-like convolutions, we provide a shift invariance measure for the first max pooling hidden layer. To support our theoretical results, we build a mathematical twin implementing the dual-tree complex wavelet packet transform, a particular case of discrete Gabor-like decomposition with perfect reconstruction properties. We discovered that replacing the max pooling layer by a more stable modulus operator leads to increased predictive power, when trained on ImageNet.

### Video

{% include youtubePlayer.html id=page.youtubeId %}
