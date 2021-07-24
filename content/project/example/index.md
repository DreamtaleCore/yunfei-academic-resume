---
slides: example
url_pdf: ""
summary: An example of using the in-built project page.
authors:
  - Yunfei Liu
  - Xingju Ma
  - James Bailey
  - Feng Lu
url_video: ""
date: 2020-05-02T00:00:00.000Z
external_link: eccv2020_Refool/project_index.html
url_slides: ""
title: "Reflection Backdoor: A Natural Backdoor Attack on Deep Neural Networks"
tags:
  - Backdoor Attack
  - Natural Reflection
  - Deep Neural Networks
links:
  - icon: ""
    icon_pack: fab
    name: pdf
    url: https://arxiv.org/abs/2007.02343
  - url: https://github.com/DreamtaleCore/Refool
    name: Code
    icon_pack: null
    icon: ""
  - url: project_index.html
    name: Project
image:
  caption: Teaser Image
  focal_point: Smart
  filename: featured.png
url_code: ""
---
<!--StartFragment-->

Recent studies have shown that DNNs can be compromised by backdoor attacks crafted at training time. A backdoor attack installs a backdoor into the victim model by injecting a backdoor pattern into a small proportion of the training data. At test time, the victim model behaves normally on clean test data, yet consistently predicts a specific (likely incorrect) target class whenever the backdoor pattern is present in a test example. While existing backdoor attacks are effective, they are not stealthy. The modifications made on training data or labels are often suspicious and can be easily detected by simple data filtering or human inspection. In this paper, we present a new type of backdoor attack inspired by an important natural phenomenon -- reflection. Using mathematical modeling of physical reflection models, we propose reflection backdoor (Refool) to plant reflections as backdoor into a victim model. We demonstrate on 3 computer vision tasks and 5 datasets that, Refool can attack state-of-the-art DNNs with high success rate, and is resistant to state-of-the-art backdoor defenses.

<!--EndFragment-->