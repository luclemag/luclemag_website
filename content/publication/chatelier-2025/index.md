---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Model-Based Learning for Multi-Antenna Multi-Frequency Location-to-Channel
  Mapping
subtitle: ''
summary: ''
authors:
- Baptiste Chatelier
- Vincent Corlay
- Matthieu Crussière
- Luc Le Magoarou
tags:
- Computer architecture;Neural networks;Machine learning;Signal processing;Channel
  estimation;Training;Channel models;Adaptation models;Complexity theory;Channel impulse
  response;Model-based machine learning;implicit neural representations;spectral bias;sparse
  representation;MIMO
categories: []
date: '2025-03-01'
lastmod: 2025-03-21T10:16:53+01:00
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
publishDate: '2025-03-21T09:16:25.836570Z'
publication_types:
- '2'
abstract: 'Years of study of the propagation channel showed a close relation between a location and the associated communication channel response. The use of a neural network to learn the location-to-channel mapping can therefore be envisioned. The Implicit Neural Representation (INR) literature showed that classical neural architecture are biased towards learning low-frequency content, making the location-to-channel mapping learning a non-trivial problem. Indeed, it is well known that this mapping is a function rapidly varying with the location, on the order of the wavelength. This paper leverages the model-based machine learning paradigm to derive a problem-specific neural architecture from a propagation channel model. The resulting architecture efficiently overcomes the spectral-bias issue. It only learns low-frequency sparse correction terms activating a dictionary of high-frequency components. The proposed architecture is evaluated against classical INR architectures on realistic synthetic data, showing much better accuracy. Its mapping learning performance is explained based on the approximated channel model, highlighting the explainability of the model-based machine learning paradigm.'
publication: '*IEEE Journal of Selected Topics in Signal Processing*'
doi: 10.1109/JSTSP.2025.3549952
---
