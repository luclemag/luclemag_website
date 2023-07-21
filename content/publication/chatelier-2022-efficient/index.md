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
date: '2022-01-01'
lastmod: 2023-07-21T09:42:12+02:00
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
publishDate: '2023-07-21T07:42:11.639453Z'
publication_types:
- '3'
abstract: 'In modern communication systems, channel state information is of paramount importance to achieve capacity. It is then crucial to accurately estimate the channel. It is possible to perform SISO-OFDM channel estimation using sparse recovery techniques. However, this approach relies on the use of a physical wave propagation model to build a dictionary, which requires perfect knowledge of the system parameters. In this paper, an unfolded neural network is used to lighten this constraint. Its architecture, based on a sparse recovery algorithm, allows SISO-OFDM channel estimation even if the system parameters are not perfectly known. Indeed, its unsupervised online learning allows to learn the system imperfections in order to enhance the estimation performance. The practicality of the proposed method is improved with respect to the state of the art in two aspects: constrained dictionaries are introduced in order to reduce sample complexity and hierarchical search within dictionaries is proposed in order to reduce time complexity. Finally, the performance of the proposed unfolded network is evaluated and compared to several baselines using realistic channel data, showing the great potential of the approach.'
publication: ''
links:
- name: arXiv
  url: https://arxiv.org/abs/2210.06588
---
