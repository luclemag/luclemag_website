---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Efficient Deep Unfolding for SISO-OFDM Channel Estimation
subtitle: ''
summary: ''
authors:
- Baptiste Chatelier
- Luc Le Magoarou
- Getachew Redieteab
tags: []
categories: []
date: '2023-06-01'
lastmod: 2023-12-08T09:58:00+01:00
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
publishDate: '2023-12-08T08:57:57.364513Z'
publication_types:
- '1'
abstract: "In modern communication systems, channel state information is of paramount\
  \ importance to achieve capacity. It is then crucial to accurately estimate the\
  \ channel. It is possible to perform SISO-OFDM channel estimation using sparse recovery\
  \ techniques. However, this approach relies on the use of a physical wave propagation\
  \ model to build a dictionary, which requires perfect knowledge of the system's\
  \ parameters. In this paper, an unfolded neural network is used to lighten this\
  \ constraint. Its architecture, based on a sparse recovery algorithm, allows SISO-OFDM\
  \ channel estimation even if the system's parameters are not perfectly known. Indeed,\
  \ its unsupervised online learning allows to learn the system's imperfections in\
  \ order to enhance the estimation performance. The practicality of the proposed\
  \ method is improved with respect to the state of the art in two aspects: constrained\
  \ dictionaries are introduced in order to reduce sample complexity and hierarchical\
  \ search within dictionaries is proposed in order to reduce time complexity. Finally,\
  \ the performance of the proposed unfolded network is evaluated and compared to\
  \ several baselines using realistic channel data, showing the great potential of\
  \ the approach."
publication: '*ICC 2023 - IEEE International Conference on Communications*'
doi: 10.1109/ICC45041.2023.10278825
---
