---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'mpNet: variable depth unfolded neural network for massive MIMO channel estimation'
subtitle: ''
summary: ''
authors:
- Taha Yassine
- Luc Le Magoarou
tags:
- Channel estimation
- Neural networks
- Manifolds
- Signal to noise ratio
- Matching pursuit algorithms
- Estimation
- Analytical models
- MIMO channel estimation
- sparse recovery
- matching pursuit (MP)
- neural network
- deep unfolding
- online learning
- unsupervised learning
categories: []
date: '2022-01-01'
lastmod: 2023-07-17T16:16:52+02:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2023-07-17T14:16:51.635747Z'
publication_types:
- '2'
abstract: Massive multiple-input multiple-output (MIMO) communication systems have
  a huge potential both in terms of data rate and energy efficiency, although channel
  estimation becomes challenging for a large number of antennas. Using a physical
  model allows to ease the problem by injecting a priori information based on the
  physics of propagation. However, such a model rests on simplifying assumptions and
  requires to know precisely the configuration of the system, which is unrealistic
  in practice. In this paper we present mpNet, an unfolded neural network specifically
  designed for massive MIMO channel estimation. It is trained online in an unsupervised
  way. Moreover, mpNet is computationally efficient and automatically adapts its depth
  to the signal-to-noise ratio (SNR). The method we propose adds flexibility to physical
  channel models by allowing a base station (BS) to automatically correct its channel
  estimation algorithm based on incoming data, without the need for a separate offline
  training phase. It is applied to realistic millimeter wave channels and shows great
  performance, achieving a channel estimation error almost as low as one would get
  with a perfectly calibrated system. It also allows incident detection and automatic
  correction, making the BS resilient and able to automatically adapt to changes in
  its environment.
publication: '*IEEE Trans. Wireless Commun.*'
doi: 10.1109/TWC.2022.3142737
---
