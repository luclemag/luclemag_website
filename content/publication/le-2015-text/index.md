---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Text-informed audio source separation. example-based approach using non-negative
  matrix partial co-factorization
subtitle: ''
summary: ''
authors:
- Luc Le Magoarou
- Alexey Ozerov
- Ngoc QK Duong
tags: []
categories: []
date: '2015-01-01'
lastmod: 2023-08-17T15:03:19+02:00
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
publishDate: '2023-08-17T13:03:19.098653Z'
publication_types:
- '2'
abstract: The so-called informed audio source separation, where the separation process
  is guided by some auxiliary information, has recently attracted a lot of research
  interest since classical blind or non-informed approaches often do not lead to satisfactory
  performances in many practical applications. In this paper we present a novel text-informed
  framework in which a target speech source can be separated from the background in
  the mixture using the corresponding textual information. First, given the text,
  we propose to produce a speech example via either a speech synthesizer or a human.
  We then use this example to guide source separation and, for that purpose, we introduce
  a new variant of the non-negative matrix partial co-factorization (NMPCF) model
  based on a so-called excitation-filter-channel speech model. Such a modeling allows
  sharing the linguistic information between the speech example and the speech in
  the mixture. The corresponding multiplicative update (MU) rules are eventually derived
  for the parameters estimation and several extensions of the model are proposed and
  investigated. We perform extensive experiments to assess the effectiveness of the
  proposed approach in terms of source separation and alignment performance.
publication: '*Journal of Signal Processing Systems*'
---
