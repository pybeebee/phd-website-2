---
title: "MetaFaith: Faithful Natural Language Uncertainty Expression in LLMs"
authors:
- admin
- Gal Yona
- Avi Caciularu
- Idan Szpektor
- Tim G. J. Rudner
- Arman Cohan
date: "2025-05-30T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-11-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "*Submission to ARR May 2025*"
publication_short: "*Submission to ARR May 2025*"

abstract: "A critical component in the trustworthiness of LLMs is reliable uncertainty communication, yet LLMs often use assertive language when conveying false claims, leading to over-reliance and eroded trust. We present the first systematic study of *faithful confidence calibration* of LLMs, benchmarking models' ability to use linguistic expressions of uncertainty that *faithfully reflect* their intrinsic uncertainty, across a comprehensive array of models, datasets, and prompting strategies. Our results demonstrate that LLMs largely fail at this task, and that existing interventions are insufficient: standard prompt approaches provide only marginal gains, and existing, factuality-based calibration techniques can even harm faithful calibration. To address this critical gap, we introduce MetaFaith, a novel prompt-based calibration approach inspired by human metacognition. We show that MetaFaith robustly improves faithful calibration across diverse models and task domains, enabling up to 61% improvement in faithfulness and achieving an 83% win rate over original generations as judged by humans. Our code is available at https://github.com/yale-nlp/MetaFaith."

# Summary. An optional shortened abstract.
summary: 'For LLMs to be deployed reliably and responsibly, it is essential that their linguistically expressed
confidence faithfully reflect their internal uncertainty. This paper presents the first study to systematically and
comprehensively benchmark faithful calibration of LLMs and proposes MetaFaith, the first method to improve faithful calibration of any instructionfollowing LLM in a task-agnostic manner.'

#tags:
#- LLMs
#- NLP
#- Metacognition
featured: false

# Optional external URL for project (replaces project detail page).
external_link: 'https://arxiv.org/abs/2505.24858'

links:
- name<!-- : HF Repo
  ur -->l: https://huggingface.co/collections/yale-nlp/mdcure-6724914875e87f41e5445395
url_pdf: 'https://arxiv.org/pdf/2505.24858'
url_code: 'https://github.com/yale-nlp/MetaFaith'
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