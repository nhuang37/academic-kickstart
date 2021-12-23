---
title: "A Simple Spectral Failure Mode for Graph Convolutional Networks"
authors:
- Carey E. Priebe
- Cencheng Shen
- admin
- Tianyi Chen
date: "2021-08-13T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-08-13T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Pattern Analysis and Machine Intelligence"
publication_short: "TPAMI"

abstract: Neural networks have achieved remarkable successes in machine learning tasks. This has recently been extended to graph learning using neural networks. However, there is limited theoretical work in understanding how and when they perform well, especially relative to established statistical learning techniques such as spectral embedding. In this short paper, we present a simple generative model where unsupervised graph convolutional network fails, while the adjacency spectral embedding succeeds. Specifically, unsupervised graph convolutional network is unable to look beyond the first eigenvector in approximately regular graphs, thus missing inference signals in non-leading eigenvectors. The phenomenon is demonstrated by visual illustrations and comprehensive simulations.

# Summary. An optional shortened abstract.
summary: A simple generative model in which spectral graph embedding for subsequent inference succeeds whereas unsupervised GCN fails. 

tags:
- Representation Learning
- Deep Learning
featured: false

#links:
# - name: ""
#   url: ""
url_pdf: https://ieeexplore.ieee.org/abstract/document/9513556
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  #caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---
