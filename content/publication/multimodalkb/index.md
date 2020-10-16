---
title: "Learning Robust Multimodal Knowledge Graph Representations"
authors:
# - admin,
date: "2020-10-07T00:00:00Z"
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

abstract: We propose a new method to make natural language understanding models more parameter efficient by storing knowledge in an external knowledge graph (KG) and retrieving from this KG using a dense index. Given some task data, e.g., sentences in German, we retrieve entities from the KG and use their multimodal representations to improve downstream task performance. Using VisualSem as our KG, we compare a mix of tuple-based and graph-based algorithms to learn robust representations of entities that are grounded on their multimodal information. We then demonstrate the usefulness of our learned entity representations on two downstream tasks. Using our best learned representations, we improve performance on the multilingual named entity recognition (NER) task by 0.3%-0.7% (F1 score), while on the visual sense disambiguation task, we achieve up to 3% improvement in accuracy in the low-resource setting.

# Summary. An optional shortened abstract.
summary: We propose a new method to make NLP models more parameter efficient by storing and retrieving knowledge in an external knowledge graph.

tags:
- Representation Learning
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
