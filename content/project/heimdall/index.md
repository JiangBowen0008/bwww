---
title: "Project Heimdall: Indoor Corner Case Detection"
summary: Mapping corner case objects (such as glass and mirrors) with sensor fusion on top of LIO-SAM as backbone. Harvey Mudd College Engineering clinic program.
tags:
- Robotics
- SLAM
- Machine Learning
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
url_slides: "https://drive.google.com/drive/folders/1_sC7vSGdzONLVBRYDuS7hOgkqMByvVro?usp=sharing"
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

*Information of our sponsor are confidential due to NDA.*

## Problem Statement

Indoor perception of obstacles and objects has been worked on for decades with recent major advances in both algorithms (e.g. Deep Learning / Machine Learning) as well as hardware (e.g. high-res cameras, LiDAR). Current systems work well for nominal cases such as detecting common, solid objects (e.g. furniture, walls or household items). However, there has been substantially less focus on rare, but important corner cases such as glass walls/doors, puddles and liquid spills, pot holes, or mirrors that can occur in applications such as industrial and manufacturing environments. This project aims at focusing on the detection of obstacles typical indoor perception systems fail at.

## Overall Goal

The team will create a comprehensive list of corner cases and select a set of indoor corner cases to solve based on the frequency at which they are encountered in the environment and their difficulty. The team will then develop a solution to the selected set of corner cases along with its performance metric, and build a handheld prototype to evaluate and demonstrate the performance of the solution.

## Work at Progress

- Develop a scalable SLAM algorithm based on LIO-SAM with VLP-16 and VectorNav-100T-CR.
- Develop a corner case detection module using RGBD camera and a TI radar (sensor fusion).
- Map the corner case objects to the global map.
- Port all the softwares to Jetson Nano.
- Make the entire setup portable.






