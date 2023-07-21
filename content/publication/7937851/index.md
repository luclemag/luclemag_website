---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Approximate Fast Graph Fourier Transforms via Multilayer Sparse Approximations
subtitle: ''
summary: ''
authors:
- Luc Le Magoarou
- Rémi Gribonval
- Nicolas Tremblay
tags:
- Sparse matrices;Laplace equations;Signal processing;Fourier transforms;Symmetric
  matrices;Complexity theory;Jacobian matrices;Fast Fourier transform;graph signal
  processing;greedy algorithms;Jacobi eigenvalues algorithm;sensor networks
categories: []
date: '2018-06-01'
lastmod: 2023-07-21T09:41:53+02:00
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
publishDate: '2023-07-21T07:41:52.728645Z'
publication_types:
- '2'
abstract: The fast Fourier transform is an algorithm of paramount importance in signal
  processing as it allows to apply the Fourier transform in $mathcal O(n łog n)$ instead
  of $mathcal O(n^2)$ arithmetic operations. Graph signal processing is a recent research
  domain that generalizes classical signal processing tools, such as the Fourier transform,
  to situations where the signal domain is given by any arbitrary graph instead of
  a regular grid. Today, there is no method to rapidly apply graph Fourier transforms.
  In this paper, we propose a method to obtain approximate graph Fourier transforms
  that can be applied rapidly and stored efficiently. It is based on a greedy approximate
  diagonalization of the graph Laplacian matrix, carried out using a modified version
  of the famous Jacobi eigenvalues algorithm. The method is described and analyzed
  in detail, and then applied to both synthetic and real graphs, showing its potential.
publication: '*IEEE Transactions on Signal and Information Processing over Networks*'
doi: 10.1109/TSIPN.2017.2710619

links:
- name: arXiv
  url: https://arxiv.org/abs/1612.04542

---
