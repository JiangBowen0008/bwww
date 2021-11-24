---
title: "Selective Reinforcement Learning"
summary: Utilizing the uncertainty in object-based RL prediction models for selective, hence more efficient learning. 
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

# Overall Description

Using deictic tree for model-based reinforcement learning. The deictic tree uses uncertainty for selective learning in a mannar that is sensitive to marginal and nonlinear changes.

# My Works Involve

* Implemented Selective MVE based on the paper Selective Dyna-style Planning Under Limited Model Capacity
  - An algorithm that weights rollouts using their uncertainties
  - Finding: sensitive to hyperparameter (sensitivities to the scale of the uncertainties)
* Uncertainty Estimation: Particle
  - Borrowed from the engineering concept Particle Filter
  - Goal: Overcoming the vulnerability of the prediction models when the state transitions are nonlinear, which are ubiquitous among Atari games
  - Implementations (mostly listed in particle.h):
    1. Particle cloud: (rollout) variance calculation, average value calculations, resample, subsample
    2. Particle: Container for a state with utilities that keep track of the histories and facilitate arithmetic calculations
  - Added the prediction sample function to the prediction model
* Optimization with Eigen
  - Researched into several available linear algebra libraries
  - Self-taught Eigen: data conversion and QR decomposition for regression calculations
  - Designed a benchmark to compare the linear regression runtime






