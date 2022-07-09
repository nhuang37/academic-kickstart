---
title: "From Local to Global: Spectral-Inspired Graph Neural Networks "
authors:
- admin
- 'Carey E. Priebe'
- Da Zheng
- Lin Yang
- Vladimir Braverman
- Soledad Villar
date: "2022-06-01"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: 'Graph Neural Networks (GNNs) are powerful deep learning methods for Non-Euclidean data. Most popular GNNs are message passing algorithms (MPNNs) that aggregate and combine signals in a local graph neighborhood. However, shallow MPNNs tend to miss global information or long-range signals, while deep MPNNs can suffer from issues like over-smoothing or over-squashing. To mitigate such issues, existing works typically borrow normalization techniques from training neural networks on Euclidean data, or modify the graph structures. But these approaches are usually not completely understood theoretically, and could increase the overall computational complexity. In this work, we draw inspirations from spectral graph embedding and propose two simple techniques: (1) a layer-wise normalization method PowerEmbed to inject global information in local MPNNs; (2) a graph decomposition procedure to exploit the advantages of global and local methods. We show PowerEmbed can provably express the top-k leading eigenvectors of the graph operator, which avoids over-smoothing and over-squashing, with provable guarantees for certain stochastic block models. We also provide sufficient conditions for the graph decomposition strategy to outperform pure global and local methods. We apply our techniques in a wide range of simulated and real graphs and demonstrate their superior performance, particularly for dense graphs.'

# Summary. An optional shortened abstract.
summary: We propose spectral-inspired GNNs that exploit the advantages from both global and local methods.

tags:
- Deep Learning
- Representation Learning
- Theory of deep learning
featured: false

#links:
#- name: Custom Link
#  url: http://example.org
#url_pdf: https://arxiv.org/abs/2205.14299
#url_code: '#'
#url_dataset: '#'
#url_poster: 'https://github.com/nhuang37/academic-kickstart/blob/master/static/poster_teresa_updated.pdf'
#url_project: ''
#url_slides: ''
#url_source: '#'
#url_video: '#'

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
