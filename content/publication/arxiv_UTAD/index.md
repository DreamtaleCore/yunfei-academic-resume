---
title: "Unsupervised Two-Stage Anomaly Detection"
publication_types:
  - "2"
  - "3"
authors:
  - Yunfei Liu
  - Chaoqun Zhuang
  - Feng Lu
publication: arXiv:2103.11671
publication_short: arxiv
abstract: "Anomaly detection from a single image is challenging
since anomaly data is always rare and can be with highly
unpredictable types. With only anomaly-free data available,
most existing methods train an AutoEncoder to reconstruct
the input image and find the difference between the input
and output to identify the anomalous region. However, such
methods face a potential problem – a coarse reconstruction
generates extra image differences while a high-fidelity one
may draw in the anomaly (Fig.1). In this paper, we solve this
contradiction by proposing a two-stage approach, which gen-
erates high-fidelity yet anomaly-free reconstructions. Our
Unsupervised Two-stage Anomaly Detection (UTAD) relies
on two technical components, namely the Impression Extrac-
tor (IE-Net) and the Expert-Net. The IE-Net and Expert-Net
accomplish the two-stage anomaly-free image reconstruction
task while they also generate intuitive intermediate results,
making the whole UTAD interpretable. Extensive experi-
ments show that our method outperforms state-of-the-arts
on four anomaly detection datasets with different types of
real-world objects and textures"
draft: false
featured: false
tags:
  - Anomaly Detection
  - Two-stage
  - Unsupervised Learning
image:
  filename: featured.png
  focal_point: Smart
  preview_only: false
  caption: Teaser Image
date: 2021-03-01T14:07:22.714Z

links:
  - icon: ""
    icon_pack: fab
    name: PDF
    url: https://arxiv.org/pdf/2103.11671.pdf
  - url: https://github.com/DreamtaleCore/UTAD
    name: Code
    icon_pack: fab
    icon: "github"
---
