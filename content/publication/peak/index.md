---
title: "Dimensionality reduction, regularization, and generalization in overparameterized regressions"
authors:
# - admin,
date: "2020-10-14T00:00:00Z"
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

abstract: We study the peaking phenomenon of the double descent risk curve of linear models. We show that performing a PCA-based dimensionality reduction avoids the divergence when the number of the samples approaches to the number of the parameters. We connect these results to an analysis of adversarial attacks, which become more effective as they raise the condition number of the empirical covariance of the features. We show that ordinary least squares is arbitrarily susceptible to data-poisoning attacks in the overparameterized regime---unlike the underparameterized regime---and how regularization and dimensionality reduction improve its robustness. 

# Summary. An optional shortened abstract.
summary: We show how PCA avoids the peaking phenomenon of the double descent risk curve, and connect these results to adversarial attacks.

tags:
- Theory of deep learning
featured: false

#links:
#- name: Custom Link
#  url: http://example.org
#url_pdf: http://arxiv.org/pdf/1512.04133v1
#url_code: '#'
#url_dataset: '#'
#url_poster: '#'
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
