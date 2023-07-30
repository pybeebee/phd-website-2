---
title: "Streaming Inference for Infinite Non-Stationary Clustering"
authors:
- Rylan Schaeffer
- admin
- Yilun Du
- Scott Linderman
- Ila Rani Fiete
date: "2022-08-22T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*ICLR Workshop on Agent Learning in Open-Endedness & Conference on Lifelong Learning Agents*"
publication_short: "*ICLR Workshop on Agent Learning in Open-Endedness & Conference on Lifelong Learning Agents*"

abstract: "Learning from a continuous stream of non-stationary data in an unsupervised manner is arguably one of the most common and most challenging settings facing intelligent agents. Here, we attack learning under all three conditions (unsupervised, streaming, non-stationary) in the context of clustering, also known as mixture modeling. We introduce a novel clustering algorithm that endows mixture models with the ability to create new clusters online, as demanded by the data, in a probabilistic, time-varying, and principled manner. To achieve this, we first define a novel stochastic process called the Dynamical Chinese Restaurant Process (Dynamical CRP), which is a non-exchangeable distribution over partitions of a set; next, we show that the Dynamical CRP provides a non-stationary prior over cluster assignments and yields an efficient streaming variational inference algorithm. We conclude with experiments showing that the Dynamical CRP can be applied on diverse synthetic and real data with Gaussian and non-Gaussian likelihoods."

# Summary. An optional shortened abstract.
summary: 'We define the Dynamical Chinese Restaurant Process (Dynamical CRP), a novel stochastic process that provides a non-stationary prior over cluster assignments and yields an efficient streaming variational inference algorithm. Experiments show the Dynamical CRP can be applied on diverse synthetic and real data with Gaussian and non-Gaussian likelihoods.'


#tags:
#- Bayesian nonparametrics
#- Streaming inference
featured: false

# Optional external URL for project (replaces project detail page).
external_link: 'https://proceedings.mlr.press/v199/schaeffer22a.html'

links:
# - name: Abstract
  # text: test
  # url: http://example.org
url_pdf: 'https://proceedings.mlr.press/v199/schaeffer22a/schaeffer22a.pdf'
url_code: ''
url_dataset: ''
url_poster: 'https://drive.google.com/file/d/17OkQSgQDhM7FmT7H_fLQfzFX59OpogPe/view?usp=sharing'
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