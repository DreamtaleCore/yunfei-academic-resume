---
title: "Separate In Latent Space: Unsupervised Single Image Layer Separation"
publication_types:
  - "1"
authors:
  - Yunfei Liu
  - Feng Lu
publication: The Thirty-Fourth AAAI Conference on Artificial Intelligence
publication_short: AAAI
abstract: Many real world vision tasks, such as reflection removal from a
  transparent surface and intrinsic image decomposition, can be modeled as
  single image layer separation. However, this problem is highly ill-posed,
  requiring accurately aligned and hard to collect triplet data to train the CNN
  models. To address this problem, this paper proposes an unsupervised method
  that requires no ground truth data triplet in training. At the core of the
  method are two assumptions about data distributions in the latent spaces of
  different layers, based on which a novel unsupervised layer separation
  pipeline can be derived. Then the method can be constructed based on the GANs
  framework with self-supervision and cycle consistency constraints, etc.
  Experimental results demonstrate its successfulness in outperforming existing
  unsupervised methods in both synthetic and real world tasks. The method also
  shows its ability to solve a more challenging multi-layer separation task.
draft: false
featured: false
tags:
  - Layer Decomposition
  - Unsupervised Learning
image:
  filename: aaai20.png
  focal_point: Smart
  preview_only: false
  caption: Teaser Image
date: 2019-11-01T14:07:22.714Z
---
