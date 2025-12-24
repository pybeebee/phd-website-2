---
title: "Incorporating Q&A Nuggets into Retrieval-Augmented Generation"
authors:
- Laura Dietz
- Bryan Li
- admin
- Jia-Huei Ju
- Eugene Yang
- Dawn Lawrie
- William Gantt Walden
- James Mayfield
date: "2026-03-29T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-11-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*ECIR*"
publication_short: "*ECIR*"

abstract: "We present NagSys, a Nugget-Augmented Generation System that preserves explicit citation provenance by constructing a bank of Q&A nuggets from retrieved documents and uses them to guide extraction, selection, and report generation. Reasoning on nuggets avoids repeated information through clear and interpretable Q&A semantics—rather than opaque cluster abstractions—while maintaining citation provenance throughout the entire generation process. Evaluated on the TREC NeuCLIR 2024 collection, our NagSys system substantially outperforms Ginger, a recent nugget-based RAG system, in nugget recall, density, and citation grounding."

# Summary. An optional shortened abstract.
summary: 'Nugget-based evaluation methods have emerged as the standard for measuring relevance of long-form RAG responses. We argue that nuggets are valuable also for guiding retrieval and generation, and we present a nugget-centric RAG system that automatically constructs its own nugget bank and uses it as a control signal throughout the pipeline.'

#tags:
#- LLMs
#- NLP
#- RAG
featured: false

# Optional external URL for project (replaces project detail page).
external_link: ''

links:
#- name: HF Repo
#  url: https://huggingface.co/collections/yale-nlp/mdcure-6724914875e87f41e5445395
url_pdf: ''
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