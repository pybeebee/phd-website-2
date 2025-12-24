---
title: "Evaluating Retrieval-Augmented Generation Systems on Unanswerable, Uncheatable, Realistic, Multi-hop Queries"
authors:
- admin
- Bryan Li
- Arman Cohan
- William Gantt Walden
- Eugene Yang
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

abstract: "Real-world use cases often present RAG systems with complex queries for which relevant information is missing from the corpus or is incomplete. In these settings, RAG systems must be able to reject unanswerable, out-of-scope queries and identify failures of retrieval and multi-hop reasoning. Despite this, existing RAG benchmarks rarely reflect realistic task complexity for multi-hop or out-of-scope questions, which often can be cheated via disconnected reasoning (i.e., solved without genuine multi-hop inference) or require only simple factual recall. This limits the ability for such benchmarks to uncover limitations of existing RAG systems. To address this gap, we present the first pipeline for automatic, difficulty-controlled creation of un*c*heatable, *r*ealistic, *u*nanswerable, and *m*ulti-hop *q*uerie*s* (CRUMQs), adaptable to any corpus and domain. We use our pipeline to create CRUMQs over two popular RAG datasets and demonstrate its effectiveness via benchmark experiments on leading retrieval-augmented LLMs. Results show that compared to prior RAG benchmarks, CRUMQs are highly challenging for RAG systems and achieve up to 81.0% reduction in cheatability scores. More broadly, our pipeline offers a simple way to enhance benchmark difficulty and realism and drive development of more capable RAG systems."

# Summary. An optional shortened abstract.
summary: 'We present the first pipeline for automatic, difficulty-controlled creation of uncheatable, realistic, unanswerable, and multi-hop queries (CRUMQs), adaptable to any corpus and domain. This offers a simple way to enhance benchmark difficulty and realism and drive development of more capable RAG systems.'

#tags:
#- LLMs
#- NLP
#- RAG
featured: false

# Optional external URL for project (replaces project detail page).
external_link: 'https://www.arxiv.org/abs/2510.11956'

links:
#- name: HF Repo
#  url: https://huggingface.co/collections/yale-nlp/mdcure-6724914875e87f41e5445395
url_pdf: 'https://www.arxiv.org/pdf/2510.11956'
url_code: 'https://github.com/pybeebee/CRUMQs'
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