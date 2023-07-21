---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Text-informed audio source separation using nonnegative matrix partial co-factorization
subtitle: ''
summary: ''
authors:
- Luc Le Magoarou
- Alexey Ozerov
- Ngoc Q. K. Duong
tags:
- Speech;Source separation;Synchronization;Radio frequency;Dictionaries;Parameter
  estimation;Spectrogram;Informed audio source separation;text information;nonnegative
  matrix partial co-factorization;source-filter model
categories: []
date: '2013-09-01'
lastmod: 2023-07-21T09:42:05+02:00
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
publishDate: '2023-07-21T07:42:04.009299Z'
publication_types:
- '1'
abstract: We consider a single-channel source separation problem consisting in separating
  speech from nonstationary background such as music. We introduce a novel approach
  called text-informed separation, where the source separation process is guided by
  the corresponding textual information. First, given the text, we propose to produce
  a speech example via either a speech synthesizer or a human. We then use this example
  to guide source separation and, for that purpose, we introduce a new variant of
  the nonnegative matrix partial co-factorization (NMPCF) model based on a so called
  excitation-filter-channel speech model. The proposed NMPCF model allows sharing
  the linguistic information between the example speech and the speech in the mixture.
  We then derive the corresponding multiplicative update (MU) rules for the parameter
  estimation. Experimental results over different types of mixtures and speech examples
  show the effectiveness of the proposed approach.
publication: '*2013 IEEE International Workshop on Machine Learning for Signal Processing
  (MLSP)*'
doi: 10.1109/MLSP.2013.6661995
---
