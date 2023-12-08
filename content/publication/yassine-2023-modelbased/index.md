---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Model-based Deep Learning for Beam Prediction based on a Channel Chart
subtitle: ''
summary: ''
authors:
- Taha Yassine
- Baptiste Chatelier
- Vincent Corlay
- Matthieu Crussière
- Stephane Paquelet
- Olav Tirkkonen
- Luc Le Magoarou
tags: []
categories: []
date: '2023-12-08'
lastmod: 2023-12-08T09:57:57+01:00
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
publishDate: '2023-12-08T08:57:37.422545Z'
publication_types:
- '3'
abstract: Channel charting builds a map of the radio environment in an unsupervised
  way. The obtained chart locations can be seen as low-dimensional compressed versions
  of channel state information that can be used for a wide variety of applications,
  including beam prediction. In non-standalone or cell-free systems, chart locations
  computed at a given base station can be transmitted to several other base stations
  (possibly operating at different frequency bands) for them to predict which beams
  to use. This potentially yields a dramatic reduction of the overhead due to channel
  estimation or beam management, since only the base station performing charting requires
  channel state information, the others directly predicting the beam from the chart
  location. In this paper, advanced model-based neural network architectures are proposed
  for both channel charting and beam prediction. The proposed methods are assessed
  on realistic synthetic channels, yielding promising results.
publication: ''
links:
- name: arXiv
  url: https://arxiv.org/abs/2312.02239
---
