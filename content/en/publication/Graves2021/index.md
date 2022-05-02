---
title: "Data science competition for cross-site delineation and classification of individual trees from airborne remote sensing data"
authors:
- Graves et al.
date: "2021-01-07T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-01-19T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "bioRxiv"
publication_short: ""

abstract: "Delineating and classifying individual trees in remote sensing data is challenging. Many tree crown delineation methods have difficulty in closed-canopy forests and do not leverage multiple datasets. Methods to classify individual species are often accurate for common species, but perform poorly for less common species and when applied to new sites. We ran a data science competition to help identify effective methods for delineation of individual crowns and classification to determine species identity. This competition included data from multiple sites to assess the methods9 ability to generalize learning across multiple sites simultaneously, and transfer learning to novel sites where the methods were not trained. Six teams, representing 4 countries and 9 individual participants, submitted predictions. Methods from a previous competition were also applied and used as the baseline to understand whether the methods are changing and improving over time. The best delineation method was based on an instance segmentation pipeline, closely followed by a Faster R-CNN pipeline, both of which outperformed the baseline method. However, the baseline (based on a growing region algorithm) still performed well as did the Faster R-CNN. All delineation methods generalized well and transferred to novel forests effectively. The best species classification method was based on a two-stage fully connected neural network, which significantly outperformed the baseline (a random forest and Gradient boosting ensemble)."

# Summary. An optional shortened abstract.

tags:
- Forest Ecosystem Modeling
- Land Cover change

featured: false

links:
- name:
  url_pdf: 'https://www.biorxiv.org/content/10.1101/2021.08.06.453503.abstract'
url_code: ''
url_dataset: ''
url_poster: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:  
  caption:
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides:
---

#Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/).
