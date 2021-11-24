---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: Researcher
    company: L.A.C.E. Lab @ HMC.
    company_url: ''
    company_logo: hmc
    location: California
    date_start: '2019-05-15'
    date_end: ''
    description: |2-       
        - Selective Planning. Using uncertainty in prediction models for a more effective TD learning (developed on the previous work https://arxiv.org/abs/2007.02418.)
        - Atari Game for test platform. Implemented with PyTorch C++ frontend for the NN version, with Eigen for the tree version.
        - Developing object-based prediction models for reinforcement learning agents in uncertain environments.
        
  - title: Researcher
    company: Institute of Automation Chinese Academy of Sciences (CASIA)
    company_url: ''
    company_logo: casia
    location: Beijing
    date_start: '2020-08-01'
    date_end: '2021-03-01'
    description: |2-       
        - POIS: Policy-Oriented Instance Segmentation for Ambidextrous Robot Picking. ICRA 2021. First author (co-listed).
        - Overcoming the motion planning problem when a pair of parallel robot arms share a working space using a policy-oriented segmentation strategy.

design:
  columns: '2'
---
