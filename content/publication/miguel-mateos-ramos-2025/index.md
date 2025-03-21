---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Model-Based End-to-End Learning for Multi-Target Integrated Sensing and Communication
  Under Hardware Impairments
subtitle: ''
summary: ''
authors:
- José Miguel Mateos-Ramos
- Christian Häger
- Musa Furkan Keskin
- Luc Le Magoarou
- Henk Wymeersch
tags:
- Hardware;Matching pursuit algorithms;Receivers;Integrated sensing and communication;Vectors;Mathematical
  models;Estimation;Wireless communication;OFDM;Data models;Hardware impairments;integrated
  sensing and communication (ISAC);machine learning;model-based learning;orthogonal
  matching pursuit (OMP)
categories: []
date: '2025-02-01'
lastmod: 2025-03-21T10:16:54+01:00
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
publishDate: '2025-03-21T09:16:53.591680Z'
publication_types:
- '2'
abstract: 'We study model-based end-to-end learning in the context of integrated sensing and communication (ISAC) under hardware impairments. Hardware impairments are usually addressed by means of array calibration with a focus on communication performance. However, residual impairments may exist that affect sensing performance. This paper proposes a data-driven framework for mitigating such impairments. A monostatic orthogonal frequency-division multiplexing (OFDM) sensing and multiple-input single-output (MISO) communication scenario is considered, incorporating hardware imperfections at the ISAC transceiver antenna array. Since conventional ISAC signal processing algorithms rely on mathematical models of the wireless channel, a mismatch occurs between the assumed mathematical models and the underlying reality in the presence of hardware impairments. We first study the detrimental effects of such impairments at the transmitter and receiver side of the proposed scenario, showcasing different levels of degradation on communication and sensing performances. As the core contribution of this work, we propose a novel differentiable version of the orthogonal matching pursuit (OMP) algorithm that is suitable for multi-target sensing and allows for efficient end-to-end learning of the hardware impairments. Based on the differentiable OMP, we devise two model-based parameterization strategies of the ISAC beamformer and sensing receiver to account for hardware impairments: (i) learning a dictionary of steering vectors for different angles and (ii) learning the parameterized hardware impairments. We carry out a comprehensive performance analysis of the proposed model-based learning approaches and a strong baseline consisting of least-squares beamforming, conventional OMP, and maximum-likelihood symbol detection for communication. Results show that by parameterizing the hardware impairments, learning approaches offer gains in terms of higher detection probability, position estimation accuracy, and lower symbol error rate (SER) compared to the baseline. We demonstrate that learning the parameterized hardware impairments outperforms learning a dictionary of steering vectors, also exhibiting the lowest complexity.'
publication: '*IEEE Transactions on Wireless Communications*'
doi: 10.1109/TWC.2024.3522667
---
