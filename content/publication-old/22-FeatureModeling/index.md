---
title: "Streaming Inference for Infinite Feature Models"
authors:
- Rylan Schaeffer
- Yilun Du
- admin
- Ila Rani Fiete
date: "2022-07-17T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*ICML*"
publication_short: "*ICML*"

abstract: "Unsupervised learning from a continuous stream of data is arguably one of the most common and most challenging problems facing intelligent agents. One class of unsupervised models, collectively termed feature models, attempts unsupervised discovery of latent features underlying the data and includes common models such as PCA, ICA, and NMF. However, if the data arrives in a continuous stream, determining the number of features is a significant challenge and the number may grow with time. In this work, we make feature models significantly more applicable to streaming data by imbuing them with the ability to create new features, online, in a probabilistic and principled manner. To achieve this, we derive a novel recursive form of the Indian Buffet Process, which we term the Recursive IBP (R-IBP). We demonstrate that R-IBP can be be used as a prior for feature models to efficiently infer a posterior over an unbounded number of latent features, with quasilinear average time complexity and logarithmic average space complexity. We compare R-IBP to existing offline sampling and variational baselines in two feature models (Linear Gaussian and Factor Analysis) and demonstrate on synthetic and real data that R-IBP achieves comparable or better performance in significantly less time."

# Summary. An optional shortened abstract.
summary: 'R-IBP is a novel recursive form of the Indian Buffet Process that makes feature models applicable to streaming data by imbuing them with the ability to create new features, online, in a probabilistic and principled manner. It can be be used as a prior for feature models to efficiently infer a posterior over an unbounded number of latent features, with quasilinear average time complexity and logarithmic average space complexity. '


#tags:
#- Bayesian nonparametrics
#- Streaming inference
featured: false

# Optional external URL for project (replaces project detail page).
external_link: 'https://proceedings.mlr.press/v162/schaeffer22a.html'

links:
- name: Abstract
  text: test
  # url: http://example.org
url_pdf: 'https://proceedings.mlr.press/v162/schaeffer22a/schaeffer22a.pdf'
url_code: ''
url_dataset: ''
url_poster: 'https://github.com/pybeebee/phd-website-2/tree/main/content/publication-old/22-FeatureModeling/poster.pdf'
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
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
slides: ""
---