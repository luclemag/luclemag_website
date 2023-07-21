---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Analyzing the approximation error of the fast graph Fourier transform
subtitle: ''
summary: ''
authors:
- Luc Le Magoarou
- Nicolas Tremblay
- Rémi Gribonval
tags:
- Jacobian matrices;Signal processing algorithms;Approximation error;Fourier transforms;Approximation
  algorithms;Laplace equations;Sparse matrices
categories: []
date: '2017-10-01'
lastmod: 2023-07-21T09:41:55+02:00
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
publishDate: '2023-07-21T07:41:54.216599Z'
publication_types:
- '1'
abstract: The graph Fourier transform (GFT) is in general dense and requires O(n2)
  time to compute and O(n2) memory space to store. In this paper, we pursue our previous
  work on the approximate fast graph Fourier transform (FGFT). The FGFT is computed
  via a truncated Jacobi algorithm, and is defined as the product of J Givens rotations
  (very sparse orthogonal matrices). The truncation parameter, J, represents a trade-off
  between precision of the transform and time of computation (and storage space).
  We explore further this trade-off and study, on different types of graphs, how is
  the approximation error distributed along the spectrum.
publication: '*2017 51st Asilomar Conference on Signals, Systems, and Computers*'
doi: 10.1109/ACSSC.2017.8335133
---
