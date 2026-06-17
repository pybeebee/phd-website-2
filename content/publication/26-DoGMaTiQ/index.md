---
title: "DoGMaTiQ: Automated Generation of Question-and-Answer Nuggets for Report Evaluation"
authors:
- Bryan Li
- William Gantt Walden
- Yu Hou
- admin
- Chris Callison-Burch
- Dawn Lawrie
- James Mayfield
- Eugene Yang
- Laura Dietz
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
publication: "*SIGIR ICTIR*"
publication_short: "*SIGIR ICTIR*"

abstract: "Evaluation of long-form, citation-backed reports has lately received significant attention due to the wide-scale adoption of retrieval-augmented generation (RAG) systems. Core to many evaluation frameworks is the use of atomic facts, or nuggets, to assess a report’s coverage of query-relevant information attested in the underlying collection. While nuggets have traditionally been represented as short statements, recent work has used question-answer (QA) representations, enabling fine-grained evaluations that decouple the information need (i.e. the question) from the potentially diverse content that satisfies it (i.e. its answers). A persistent challenge for nugget-based evaluation is the need to manually curate sets of nuggets for each topic in a test collection—a laborious process that scales poorly to novel information needs. This challenge is acute in cross-lingual settings, where information is found in multilingual source documents. Accordingly, we introduce DoGMaTiQ, a pipeline for generating high-quality QA-based nugget sets in three stages: (1) document-grounded nugget generation, (2) paraphrase clustering, and (3) nugget subselection based on principled quality criteria. We integrate DoGMaTiQ nuggets with Auto-ARGUE—a recent nugget-based evaluation framework—to enable fully automatic evaluation of generated reports. We conduct extensive experiments on two cross-lingual TREC shared tasks, NeuCLIR and RAGTIME, showing strong rank correlations with both human-in-the-loop and fully manual judgments. Finally, detailed analysis of our pipeline reveals that a strong LLM nugget generator is key, and that the system rankings induced by DoGMaTiQ are robust to outlier systems. We facilitate future research in report evaluation by publicly releasing our code and artifacts."

# Summary. An optional shortened abstract.
summary: 'Evaluation of long-form, citation-backed reports typically depends on use of atomic, QA-based nuggets to assess coverage of query-relevant information. This largely depends on manual curation of sets of nuggets per test topic. To improve scalability, we introduce DoGMaTiQ, a pipeline to generate high-quality QA nugget sets, and integrate it with Auto-ARGUE, a recent nugget-based evaluation framework, to enable fully automatic evaluation of generated reports.'

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
url_pdf: 'https://arxiv.org/pdf/2605.04458'
url_code: 'https://github.com/manestay/dogmatiq'
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