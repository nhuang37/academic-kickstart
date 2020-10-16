---
title: Autonomous driving
summary: A CNN encoder-decoder model to navigate traffic environment using bird's eye view images.
tags:
- Deep Learning
date: "2020-05-15T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: My conversation with chatbot
  focal_point: Smart

links:
- icon: github
  icon_pack: fab
  name: Github
  url: https://github.com/cbs488/DLSP20-Project

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---
A self-driving vehicle needs perception, planning, and ex-ecution within constantly evolving environments,  whichi nvolves important tasks such as lane segmentation and ob-jects detection.  Approaches based on front-view images lack the ability to predict object distance and orientation accurately and require additional computation to estimateinformation such as geometry and depth maps. Therefore, it is more efficient to perform lane and vehicle detection in the vehicle coordinate system by projecting the front-view images to the bird’s eye view (BEV). In this work, we propose a Convolutional Neural Network(CNN)-based encoder-decoder model to simultaneously estimate road map and traffic environment using BEV images.