---
abstract: Recent studies have shown that DNNs can be compromised by backdoor
  attacks crafted at training time. A backdoor attack installs a backdoor into
  the victim model by injecting a backdoor pattern into a small proportion of
  the training data. At test time, the victim model behaves normally on clean
  test data, yet consistently predicts a specific (likely incorrect) target
  class whenever the backdoor pattern is present in a test example. While
  existing backdoor attacks are effective, they are not stealthy. The
  modifications made on training data or labels are often suspicious and can be
  easily detected by simple data filtering or human inspection. In this paper,
  we present a new type of backdoor attack inspired by an important natural
  phenomenon -- reflection. Using mathematical modeling of physical reflection
  models, we propose reflection backdoor (Refool) to plant reflections as
  backdoor into a victim model. We demonstrate on 3 computer vision tasks and 5
  datasets that, Refool can attack state-of-the-art DNNs with high success rate,
  and is resistant to state-of-the-art backdoor defenses.
slides: example
url_pdf: https://arxiv.org/abs/2007.02343
publication_types:
  - "1"
authors:
  - "**Yunfei Liu**"
  - Xingju Ma
  - James Bailey
  - Feng Lu
url_project: project_index.html
title: "Reflection Backdoor: A Natural Backdoor Attack on Deep Neural Networks"
doi: ""
publication: In *European Conference on Computer Vision*
publication_short: In *ECCV*
featured: true
tags:
  - Backdoor Attack
  - Natural Reflection
  - Deep Neural Networks
projects:
  - internal-project
image:
  focal_point: Smart
  preview_only: false
  filename: featured.png
date: 2020-05-02T00:00:00Z
publishDate: 2020-05-02T00:00:00Z
url_code: https://github.com/DreamtaleCore/Refool
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}} -->

