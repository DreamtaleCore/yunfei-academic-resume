---
slides: example
url_pdf: ""
summary: "**Winner** of Hyperspectral City Challenge 1.0, Rank: 1."
authors:
  - Yunfei Liu
url_video: ""
date: 2019-10-02T00:00:00.000Z
external_link: https://pbdl-ws.github.io/pbdl2019/challenge/index.html
url_slides: ""
title: "Physics Based Vision Meets Deep Learning - Hyperspectral City"
tags:
  - Low-level Vision
  - Rendering
  - Deep Neural Networks
links:
  - url: https://pbdl-ws.github.io/pbdl2019/challenge/index.html
    name: Challenge Page
image:
  caption: Teaser Image
  focal_point: Right
  filename: featured.png
url_code: ""
---
<!--StartFragment-->

When physics based vision meets deep learning, there will be mutual benefits. On one hand, classic physics based vision tasks can be implemented in a data-fashion way to handle complex scenes. This is because, a physically more accurate optical model can be too complex as an inverse problem for computer vision algorithms (usually too many unknown parameters in one model), however, it can be well approximated providing a sufficient collection of data. Later, the intrinsic physical properties are likely to be learned through a deep neural network model. Existing research has already exploited such benefit on luminance transfer, computational stereo, haze removal, etc.

We propose a semantic segmentation challenge for urban autonomous driving scene which utilizes newly developed hyperspectral camera. The motivation is to compensate the insufficient visual quality problem of existing dataset. Particularly, the CityScape dataset provides only extremely washed out RGB images. To solve this, we endeavour to propose the new dataset which adopts multi-channel visual input. Our new dataset, can provide the following benefits: 1. properly balanced and colourful visual input. 2. We can analyse and see visual properties which cannot be seen from RGB channels. 3. We can robustly handle night scenes, thanks to the near infrared band. 4. We can robustly handle water phenomenon including rain and fog, because of the absolution behaviour in the infrared band.

<!--EndFragment-->