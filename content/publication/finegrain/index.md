---
title: "Fine-grained Expressivity of Graph Neural Networks"
authors:
- 'Jan Böker'
- Ron Levie
- admin
- Soledad Villar
- Christopher Morris

date: "2023-06-06"
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

abstract: 'Numerous recent works have analyzed the expressive power of message-passing graph neural networks (MPNNs), primarily utilizing combinatorial techniques such as the 1-dimensional Weisfeiler-Leman test (1-WL) for the graph isomorphism problem. However, the graph isomorphism objective is inherently binary, not giving insights into the degree of similarity between two given graphs. This work resolves this issue by considering continuous extensions of both 1-WL and MPNNs to graphons. Concretely, we show that the continuous variant of 1-WL delivers an accurate topological characterization of the expressive power of MPNNs on graphons, revealing which graphs these networks can distinguish and the level of difficulty in separating them. We identify the finest topology where MPNNs separate points and prove a universal approximation theorem. Consequently, we provide a theoretical framework for graph and graphon similarity combining various topological variants of classical characterizations of the 1-WL. In particular, we characterize the expressive power of MPNNs in terms of the tree distance, which is a graph distance based on the concepts of fractional isomorphisms, and substructure counts via tree homomorphisms, showing that these concepts have the same expressive power as the 1-WL and MPNNs on graphons. Empirically, we validate our theoretical findings by showing that randomly initialized MPNNs, without training, exhibit competitive performance compared to their trained counterparts. Moreover, we evaluate different MPNN architectures based on their ability to preserve graph distances, highlighting the significance of our continuous 1-WL test in understanding MPNN expressivity.'

# Summary. An optional shortened abstract.
summary: We quantify which distances MPNNs induce, leading to a fine-grained understanding of their expressivity.

tags:
- Representation Learning
- Graph Neural Networks
featured: false

#links:
#- name: Custom Link
#  url: http://example.org
url_pdf: https://arxiv.org/abs/2306.03698
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
