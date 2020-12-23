---
title: "Individual tree-crown detection in RGB imagery using semi-supervised deep learning neural networks"
authors:
- Weinstein et al.
date: "2019-01-07T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-01-19T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Remote Sensing"
publication_short: ""

abstract: 'Remote sensing can transform the speed, scale, and cost of biodiversity and forestry surveys. Data acquisition currently outpaces the ability to identify individual organisms in high resolution imagery. We outline an approach for identifying tree-crowns in RGB imagery while using a semi-supervised deep learning detection network. Individual crown delineation has been a long-standing challenge in remote sensing and available algorithms produce mixed results. We show that deep learning models can leverage existing Light Detection and Ranging (LIDAR)-based unsupervised delineation to generate trees that are used for training an initial RGB crown detection model. Despite limitations in the original unsupervised detection approach, this noisy training data may contain information from which the neural network can learn initial tree features. We then refine the initial model using a small number of higher-quality hand-annotated RGB images. We validate our proposed approach while using an open-canopy site in the National Ecological Observation Network. Our results show that a model using 434,551 self-generated trees with the addition of 2848 hand-annotated trees yields accurate predictions in natural landscapes. Using an intersection-over-union threshold of 0.5, the full model had an average tree crown recall of 0.69, with a precision of 0.61 for the visually-annotated data. The model had an average tree detection rate of 0.82 for the field collected stems. The addition of a small number of hand-annotated trees improved the performance over the initial self-supervised model.'

# Summary. An optional shortened abstract.
summary:

tags:
- LiDAR
- RGB
- Crown Segmentation
- Deep Learning

featured: false

links:
- name:
  url_pdf: 'https://www.mdpi.com/2072-4292/11/11/1309'
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
- IDTreeS

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides:
---
