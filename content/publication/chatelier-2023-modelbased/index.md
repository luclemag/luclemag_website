---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Model-based learning for location-to-channel mapping
subtitle: ''
summary: ''
authors:
- Baptiste Chatelier
- Luc Le Magoarou
- Vincent Corlay
- Matthieu Crussière
tags: []
categories: []
date: '2023-01-01'
lastmod: 2023-09-05T11:41:05+02:00
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
publishDate: '2023-09-05T09:40:44.898678Z'
publication_types:
- '3'
abstract: Modern communication systems rely on accurate channel estimation to achieve
  efficient and reliable transmission of information. As the communication channel
  response is highly related to the user's location, one can use a neural network
  to map the user's spatial coordinates to the channel coefficients. However, these
  latter are rapidly varying as a function of the location, on the order of the wavelength.
  Classical neural architectures being biased towards learning low frequency functions
  (spectral bias), such mapping is therefore notably difficult to learn. In order
  to overcome this limitation, this paper presents a frugal, model-based network that
  separates the low frequency from the high frequency components of the target mapping
  function. This yields an hypernetwork architecture where the neural network only
  learns low frequency sparse coefficients in a dictionary of high frequency components.
  Simulation results show that the proposed neural network outperforms standard approaches
  on realistic synthetic data.
publication: ''
links:
- name: arXiv
  url: https://arxiv.org/abs/2308.14370
---
