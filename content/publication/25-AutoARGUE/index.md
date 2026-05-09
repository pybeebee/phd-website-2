---
title: "Auto-ARGUE: LLM-Based Report Generation Evaluation"
authors:
- William Gantt Walden
- Marc Mason
- Orion Weller
- Laura Dietz
- John Conroy
- Neil Molino
- Hannah Recknor
- Bryan Li
- admin
- Yu Hou
- Dawn Lawrie
- James Mayfield
- Eugene Yang
date: "2026-03-28T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-11-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*SIGIR*"
publication_short: "*SIGIR*"

abstract: "Generation of citation-backed reports is a primary use case for retrieval-augmented generation (RAG) systems. While open-source evaluation tools exist for various RAG tasks, tools designed for report generation are lacking. Accordingly, we introduce AutoARGUE, a robust LLM-based implementation of the recently proposed ARGUE framework for report generation evaluation. We present analysis of Auto-ARGUE on the report generation pilot task from the TREC 2024 NeuCLIR track and on two tasks from the TREC 2024 RAG track, showing good system-level correlations with human judgments. Additionally, we release ARGUE-viz, a web app for visualization and fine-grained analysis of Auto-ARGUE judgments and scores."

# Summary. An optional shortened abstract.
summary: 'Report generation (RG) is a RAG task that aims to produce a long-form, citation-attributed response to a complex user query. We present the first public, automated, LLM-based implementation of the ARGUE evaluation framework for RG.'

#tags:
#- LLMs
#- NLP
#- RAG
featured: false

# Optional external URL for project (replaces project detail page).
external_link: 'https://arxiv.org/abs/2509.26184'

links:
#- name: HF Repo
#  url: https://huggingface.co/collections/yale-nlp/mdcure-6724914875e87f41e5445395
url_pdf: 'https://arxiv.org/pdf/2509.26184'
url_code: 'https://github.com/hltcoe/auto-argue'
url_dataset: ''
url_poster: ''
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