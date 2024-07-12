---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Optimizing Multicarrier Multiantenna Systems for LoS Channel Charting
subtitle: ''
summary: ''
authors:
- Taha Yassine
- Luc Le Magoarou
- Matthieu Crussière
- Stéphane Paquelet
tags:
- Vectors;Antenna measurements;Antennas;Wireless communication;Euclidean distance;Bandwidth;Task
  analysis;channel charting;dimensionality reduction;MIMO signal processing;machine
  learning;physical model
categories: []
date: '2024-01-01'
lastmod: 2024-07-12T09:17:41+02:00
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
publishDate: '2024-07-12T07:17:41.012079Z'
publication_types:
- '2'
abstract: 'Channel charting (CC) consists in learning a mapping between the space of raw channel observations, made available from pilot-based channel estimation in multicarrier multiantenna system, and a low-dimensional space where close points correspond to channels of user equipments (UEs) close spatially. Among the different methods of learning this mapping, some rely on a distance measure between channel vectors. Such a distance should reliably reflect the local spatial neighborhoods of the UEs. The recently proposed phase-insensitive (PI) distance exhibits good properties in this regards, but suffers from ambiguities due to both its periodic and oscillatory aspects, making users far away from each other appear closer in some cases. In this paper, a thorough theoretical analysis of the said distance and its limitations due to ambiguities is provided. Consequently, a new channel distance especially designed to remove ambiguities is proposed. Guidelines for designing systems capable of learning quality charts with the proposed distance are also derived. Experimental validation is then conducted on synthetic and realistic data in different scenarios.'
publication: '*IEEE Transactions on Wireless Communications*'
doi: 10.1109/TWC.2024.3417892
links:
- name: arXiv
  url: https://arxiv.org/abs/2310.03762
- name: ieeeXplore
  url: https://ieeexplore.ieee.org/document/10577595
---
