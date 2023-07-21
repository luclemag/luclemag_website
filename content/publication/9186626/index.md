---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Channel Estimation: Unified View of Optimal Performance and Pilot Sequences'
subtitle: ''
summary: ''
authors:
- Luc Le Magoarou
- Stéphane Paquelet
tags:
- Channel estimation;Estimation;MIMO communication;Channel models;Covariance matrices;Noise
  measurement;Parametric statistics;Channel estimation;Cramér-Rao bound;parametric
  model
categories: []
date: '2020-00-01'
lastmod: 2023-07-21T09:41:49+02:00
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
publishDate: '2023-07-21T07:41:48.336094Z'
publication_types:
- '2'
abstract: Channel estimation is of paramount importance in most communication systems
  in order to optimize the data rate/energy consumption tradeoff. In modern systems,
  the possibly large number of transmit/receive antennas and subcarriers makes this
  task difficult. Designing pilot sequences of reasonable size yielding good performance
  is thus critical. Classically, the number of pilots is reduced by viewing the channel
  as a random vector and assuming knowledge of its distribution. In practice, this
  requires estimating the channel covariance matrix, which can be computationally
  costly and not adapted to scenarios with high mobility. In this paper, an alternative
  view is considered, in which the channel is a function of unknown deterministic
  parameters. In this setting, the problem of designing optimal pilot sequences of
  smallest possible size is studied for any parametric channel model. To do so, the
  Cramér-Rao bound (CRB) for this general channel estimation problem is given, highlighting
  its key dependency on the introduced variation space. Then, the minimal size of
  pilot sequences and minimal value of the CRB are determined. Moreover, a general
  strategy to build optimal minimal length power constrained pilots sequences is given,
  based on an estimation of the variation space. The theoretical results are finally
  illustrated in a massive MIMO system context. They conveniently allow to retrieve
  well known previous results, but also to exhibit minimal length optimal pilot sequences
  for a new strategy based on a nonlinear physical model.
publication: '*IEEE Transactions on Signal Processing*'
doi: 10.1109/TSP.2020.3021559

links:
- name: arXiv
  url: https://arxiv.org/abs/2002.04481

---
