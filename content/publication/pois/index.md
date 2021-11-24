---
title: "POIS: Policy-Oriented Instance Segmentation for Ambidextrous Robot Picking"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Guangyun Xu
- Yi Tao
- admin
- Peng Wang
- Yongkang Luo
- Jun Zhong

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"

date: "2021-5-30T00:00:00Z"
doi: "10.1109/ICRA48506.2021.9562045"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-5-30T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE International Conference on Robotics and Automation 2021*
publication_short: In *ICRA 2021*

abstract: Robots with a parallel-jaw gripper and suction cup is an adaptive and efficient robotic picking system. This paper proposed Policy-Oriented Instance Segmentation (POIS) for ambidextrous robots. POIS can generate a pair of target masks that allows ambidextrous robots to pick in parallel. It takes a depth image and predicts initial mask, center offset, and policy confidence map through three paralleled branches. We incorporate the initial mask with center offset to obtain candidate instances, from which we select masks of target objects for policy execution (decided with policy confidence map). We also provide a dataset that contains 6k synthetic scenes and 100 real scenes for ambidextrous picking. Trained on synthetic scenes, POIS generalizes well in real scene and is capable of handling novel objects in cluttered scenes. Our dataset and video are available at https://bit.ly/3oJj8Tu.

# Summary. An optional shortened abstract.
summary: In this work, we propose policy-oriented Instance Segmentation for Ambidextrous Robot Picking. The robot has a Parallel- jaw gripper and a suction cup, and the two grippers complement each other.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/document/9562045'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: 'https://sites.google.com/view/policy-instance-segmentation/home'
url_slides: ''
url_source: ''
url_video: 'https://www.youtube.com/watch?v=GIXs6TAaPM8'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Published Paper**](https://ieeexplore.ieee.org/document/9562045)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- pois

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
