---

title: "Reflection Backdoor: A Natural Backdoor Attack on Deep Neural Networks"
publication_types:
  - "1"
authors:
  - "**Yunfei Liu**"
  - Xingju Ma
  - James Bailey
  - Feng Lu
publication: The 16th European Conference on Computer Vision
publication_short: ECCV
summary: "The 16th European Conference on Computer Vision *(ECCV-2020)*"
abstract: "Recent studies have shown that DNNs can be compromised by backdoor 
attacks crafted at training time. A backdoor attack installs a backdoor into 
the victim model by injecting a backdoor pattern into a small proportion of the
training data. At test time, the victim model behaves normally on clean test 
data, yet consistently predicts a specific (likely incorrect) target class whe-
never the backdoor pattern is present in a test example. While existing backdoor 
attacks are effective, they are not stealthy, The modifications made on training 
data or labels are often suspicious and can be easily detected by simple data fi-
ltering or human inspection. In this paper, we present a new type of backdoor att-
ack inspired by an important natural phenomenon: reflection.  Using mathematical 
modeling of physical reflection models, we propose reflection backdoor (Refool) 
to plant reflections as backdoor into a victim model. We demonstrate on 3 computer
vision tasks and 5 datasets that, Refool can attack state-of-the-art DNNs with high 
success rate, and is resistant to state-of-the-art backdoor defenses."
tags:
  - Backdoor Attack
  - Natural Reflection
  - Deep Neural Networks
draft: false
featured: false

image:
  filename: featured.jpg
  focal_point: Smart
  preview_only: false
  caption: Teaser Image
date: 2020-02-04T13:56:00.000Z

links:
  - icon: ""
    icon_pack: fab
    name: PDF
    url: https://arxiv.org/abs/2007.02343
  - url: https://github.com/DreamtaleCore/Refool
    name: Code
    icon_pack: fab
    icon: "github"
  - url: external_pages/index.html
    name: Project

---