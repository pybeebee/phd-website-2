---
title: "Reinforcement Learning with Metacognitive Feedback Elicits Faithful Uncertainty Expression in LLMs"
authors:
- admin
- Avi Caciularu
- Gal Yona
- Idan Szpektor
- Arman Cohan
date: "2026-03-29T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-11-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "*Submission to COLM 2026*"
publication_short: "*Submission to COLM 2026*"

abstract: "Metacognition is a critical component of intelligence which describes the ability to monitor and regulate one's own cognitive processes. Yet LLMs exhibit systemic deficiencies in key metacognitive faculties: they hallucinate with high confidence, fail to recognize knowledge boundaries, and misrepresent their internal uncertainty-undermining trustworthiness and reliability. Since monitoring task performance and adapting behavior accordingly are central to metacognition, we posit that models capable of accurately judging their own performance are better positioned to improve it. We operationalize this idea via two novel mechanisms: _reinforcement learning with metacognitive feedback_ (RLMF), a paradigm to refine completion rankings during preference optimization based on the quality of a model's self-judgments of performance, and _metacognitive data selection,_ which leverages similar self-judgments to identify high-value training examples, outperforming naive active learning. We apply these innovations to the problem of faithful calibration (FC), a task that is itself fundamentally metacognitive: the goal is to align expressed with intrinsic uncertainty, challenging even for frontier LLMs. We adopt a two-stage, decoupled approach, first using these methods to calibrate the faithfulness of models' self-reported confidence scores, then mapping to natural, context-adaptable linguistic uncertainty via targeted output editing. Extensive experiments show our framework achieves generalizable, state-of-the-art FC across a wide array of datasets, while preserving task accuracy. Importantly, RLMF surpasses standard RL to strengthen post-training outcomes by up to 63% while enhancing models' ability to recognize and communicate their own capability limits. This positions RLMF as a promising paradigm for encoding metacognitive awareness into LLMs toward improved abilities and alignment, and suggests metacognitive performance as an effective RL signal that can overcome limitations of prior intrinsic feedback methods."

# Summary. An optional shortened abstract.
summary: "Metacognition is a critical component of intelligence which describes the ability to monitor and regulate one's own cognitive processes. Yet LLMs exhibit systemic deficiencies in key metacognitive faculties. Since monitoring task performance and adapting behavior accordingly are central to metacognition, we posit that models capable of accurately judging their own performance are better positioned to improve it. We introduce reinforcement learning with metacognitive feedback (RLMF), a novel paradigm to refine completion rankings during preference optimization based on the quality of a model’s self-judgments of performance (i.e., metacognitive accuracy), and apply it to successfully tackle faithful calibration in LLMs."

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