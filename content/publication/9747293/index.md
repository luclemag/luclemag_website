---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Deep Learning for Location Based Beamforming with Nlos Channels
subtitle: ''
summary: ''
authors:
- Luc Le Magoarou
- Taha Yassine
- Stéphane Paquelet
- Matthieu Crussière
tags:
- Training;Deep learning;Base stations;Array signal processing;Conferences;Neural
  networks;Symbols
categories: []
date: '2022-05-01'
lastmod: 2023-07-21T09:41:41+02:00
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
publishDate: '2023-07-21T07:41:40.196772Z'
publication_types:
- '1'
abstract: Massive MIMO systems are highly efficient but critically rely on accurate
  channel state information (CSI) at the base station in or-der to determine appropriate
  precoders. CSI acquisition requires sending pilot symbols which induce an important
  overhead. In this paper, a method whose objective is to determine an appropriate
  precoder from the knowledge of the user’s location only is proposed. Such a way
  to determine precoders is known as location based beamforming. It allows to reduce
  or even eliminate the need for pilot symbols, depending on how the location is obtained.
  the proposed method learns a direct mapping from location to pre-coder in a supervised
  way. It involves a neural network with a specific structure based on random Fourier
  features allowing to learn functions containing high spatial frequencies. It is
  assessed empirically and yields promising results on realistic synthetic channels.
  As opposed to previously proposed methods, it allows to handle both line-of-sight
  (LOS) and non-line-of-sight (NLOS) channels.
publication: '*2022 IEEE International Conference on Acoustics, Speech and Signal
  Processing (ICASSP)*'
doi: 10.1109/ICASSP43922.2022.9747293
---
