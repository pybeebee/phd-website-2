---
title: "MDCure: A Scalable Pipeline for Multi-Document Instruction-Following"
authors:
- admin
- Bowen Shi
- Avi Caciularu
- Idan Szpektor
- Arman Cohan
date: "2024-11-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-11-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "*Submitted to ARR December 2024*"
publication_short: "*Submitted to ARR December 2024*"

abstract: "Multi-document (MD) processing is crucial for LLMs to handle real-world tasks such as summarization and question-answering across large sets of documents. While LLMs have improved at processing long inputs, MD contexts still present challenges, such as managing inter-document dependencies, redundancy, and incoherent structures. We introduce MDCure, a scalable and effective fine-tuning pipeline to enhance the MD capabilities of LLMs without the computational cost of pre-training or reliance on human annotated data. MDCure is based on generation of high-quality synthetic MD instruction data from sets of related articles via targeted prompts. We further introduce MDCureRM, a multi-objective reward model which filters generated data based on their training utility for MD settings. With MDCure, we fine-tune a variety of LLMs, from the FlanT5, Qwen2, and LLAMA3.1 model families, up to 70B parameters in size. Extensive evaluations on a wide range of MD and long-context benchmarks spanning various tasks show MDCure consistently improves performance over pre-trained baselines and over corresponding base models by up to 75.5%. Our code, datasets, and models are available at https://github.com/yale-nlp/MDCure."

# Summary. An optional shortened abstract.
summary: 'Multi-document (MD) processing is crucial for LLMs to handle real-world tasks across large sets of documents. This paper introduces MDCure, an effective and scalable procedure for generating high-quality multi-document instruction tuning data to improve MD capabilities of any base LLM.'

#tags:
#- LLMs
#- NLP
featured: false

# Optional external URL for project (replaces project detail page).
external_link: 'https://arxiv.org/abs/2410.23463'

links:
- name: HF Repo
  url: https://huggingface.co/collections/yale-nlp/mdcure-6724914875e87f41e5445395
url_pdf: 'https://arxiv.org/pdf/2410.23463'
url_code: 'https://github.com/yale-nlp/MDCure'
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