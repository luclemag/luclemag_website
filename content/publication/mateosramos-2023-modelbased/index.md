---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Model-Based End-to-End Learning for Multi-Target Integrated Sensing and Communication
subtitle: ''
summary: ''
authors:
- José Miguel Mateos-Ramos
- Christian Häger
- Musa Furkan Keskin
- Luc Le Magoarou
- Henk Wymeersch
tags: []
categories: []
date: '2023-01-01'
lastmod: 2023-07-21T09:42:06+02:00
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
publishDate: '2023-07-21T07:42:05.479581Z'
publication_types:
- '3'
abstract: 'We study model-based end-to-end learning in the context of integrated sensing and communication (ISAC) under hardware impairments. A monostatic orthogonal frequency-division multiplexing (OFDM) sensing and multiple-input single-output (MISO) communication scenario is considered, incorporating hardware imperfections at the ISAC transceiver antenna array. To enable end-to-end learning of the ISAC transmitter and sensing receiver, we propose a novel differentiable version of the orthogonal matching pursuit (OMP) algorithm that is suitable for multi-target sensing. Based on the differentiable OMP, we devise two model-based parameterization strategies to account for hardware impairments: (i) learning a dictionary of steering vectors for different angles, and (ii) learning the parameterized hardware impairments. For the single-target case, we carry out a comprehensive performance analysis of the proposed model-based learning approaches, a neural-network-based learning approach and a strong baseline consisting of least-squares beamforming, conventional OMP, and maximum-likelihood symbol detection for communication. Results show that learning the parameterized hardware impairments offers higher detection probability, better angle and range estimation accuracy, lower communication symbol error rate (SER), and exhibits the lowest complexity among all learning methods. Lastly, we demonstrate that learning the parameterized hardware impairments is scalable also to multiple targets, revealing significant improvements in terms of ISAC performance over the baseline.'
publication: ''
links:
- name: arXiv
  url: https://arxiv.org/abs/2307.04111
---
