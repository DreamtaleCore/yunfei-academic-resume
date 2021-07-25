---
title: "Semantic Guided Single Image Reflection Removal"
publication_types:
  - "2"
  - "3"
authors:
  - Yunfei Liu
  - Yu Li
  - Shaodi You
  - Feng Lu
publication: arXiv:1907.11912
publication_short: arxiv
abstract: "Reflection is common in images capturing scenes behind
a glass window, which is not only a disturbance visually but
also influence the performance of other computer vision al-
gorithms. Single image reflection removal is an ill-posed
problem because the color at each pixel needs to be sepa-
rated into two values, i.e., the desired clear background and
the reflection. To solve it, existing methods propose priors
such as smoothness, color consistency. However, the low-
level priors are not reliable in complex scenes, for instance,
when capturing a real outdoor scene through a window,
both the foreground and background contain both smooth
and sharp area and a variety of color. In this paper, in-
spired by the fact that human can separate the two layers
easily by recognizing the objects, we use the object seman-
tic as guidance to force the same semantic object belong to
the same layer. Extensive experiments on different datasets
show that adding the semantic information offers a signifi-
cant improvement to reflection separation. We also demon-
strate the applications of the proposed method to other com-
puter vision tasks"
draft: false
featured: false
tags:
  - Love-level Vision
  - Semantic Segmentation
  - Multi-task Learning
image:
  filename: featured.png
  focal_point: Smart
  preview_only: false
  caption: Teaser Image
date: 2019-07-01T14:07:22.714Z

links:
  - icon: ""
    icon_pack: fab
    name: PDF
    url: https://arxiv.org/pdf/1907.11912.pdf
  - url: https://github.com/DreamtaleCore/SGRRN
    name: Code
    icon_pack: fab
    icon: "github"
---
