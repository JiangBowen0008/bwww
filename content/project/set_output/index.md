---
title: "Object-based Prediction Model with Uncertainty in Reinforcement Learning"
summary: Designed a set-to-set object-based prediction model that gives reliable predictions for both values and uncertainties. 
tags:
- Machine Learning
- Reinforcement Learning
date: "2021-05-30T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Point Cloud Map
  focal_point: Smart

# links:
# - icon: git
#   icon_pack: fab
#   name: Follow
#   url: https://twitter.com/georgecushen
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

## Background

One problem we encountered when working with the object encoded Atari games is that how do we have a network that takes input as a set and output a different set. There are mainly three difficulties:

1. **The cardinality of the input set and output set can be different.** The number of objects between frames is not consistent. There can be, for example, objects spawning or disappearing due to game mechanisms. This makes certain types of NN architectures not directly usable, such as PointNet.
2. **Unordered nature of the set structure.** Set is different from a sequence, where the order of elements matters. While applying sequential models such as RNN or LSTM handles the MIMO problem, it is not the ideal candidate for sets. Having to worry about the order of input objects is undesired.
3. **Set matching.** In order to train a network, we also need to know the ground truth labels. Therefore, matching the network predictions with the ground truth labels is also a topic we studied.

## My Works Involve

![New object predictions with uncertainties](/content/project/set_output/image.png)

* Identified the problems: permutation invariance, variable cardinality
* Set-based prediction literature research
  - Most of the mainstream networks are not designed for set to set tasks
  - Identified some key papers that were relevant to our tasks. Some most relevant ones:
    1. PointGrow: Autoregressively Learned Point Cloud Generation with Self-Attention (An autoregressive approach)
    2. Unsupervised Object-Level Deep Reinforcement Learning.
    3. Learning Representations and Generative Models for 3D Point Clouds (GAN-like approach)
    4. PointNet
    5. Deformable DETR (variation of DETR)
    6. Deep Set Prediction Network (DSPN)
    7. LSTM approach
  - Implementations 
    1. Overall project framework
    2. Designed Minatar Dataset
    3. Designed a PointNet based existing object prediction model that also predicts variance.
    4. Designed a DSPN-based new object prediction model.
    5. Designed a fused set prediction model that combines those two models mentioned above.
  - Tunings







