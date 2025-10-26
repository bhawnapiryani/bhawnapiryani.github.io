---
title: 'Wrong Answers Can Also Be Useful: PlausibleQA - A Large-Scale QA Dataset with Answer Plausibility Scores'

# Authors
authors:
  - admin
  - Jamshid Mozafari
  - Abdelrahman Abdallah
  - Antoine Doucet
  - Adam Jatowt

date: '2025-07-25T00:00:00Z'
doi: '10.1145/3726302.3730299'

# Schedule page publish date (NOT publication's date)
publishDate: '2025-07-25T00:00:00Z'

# Publication type
publication_types: ['1']

# Publication name and optional abbreviated publication name
publication: "SIGIR '25: Proceedings of the 48th International ACM SIGIR Conference on Research and Development in Information Retrieval"
publication_short: "SIGIR'25"

abstract: "Large Language Models (LLMs) are revolutionizing information retrieval, with chatbots becoming an important source for answering user queries. As by their design, LLMs prioritize generating correct answers, the value of highly plausible yet incorrect answers (candidate answers) tends to be overlooked. However, such answers can still prove useful, for example, they can play a crucial role in tasks like Multiple-Choice Question Answering (MCQA) and QA Robustness Assessment (QARA). Existing QA datasets primarily focus on correct answers without explicit consideration of the plausibility of other candidate answers, limiting opportunity for more nuanced evaluations of models. To address this gap, we introduce PlausibleQA, a large-scale dataset comprising 10,000 questions and 100,000 candidate answers, each annotated with plausibility scores and justifications for their selection. Additionally, the dataset includes 900,000 justifications for pairwise comparisons between candidate answers, further refining plausibility assessments. We evaluate PlausibleQA through human assessments and empirical experiments, demonstrating its utility in MCQA and QARA analysis. Our findings show that plausibility-aware approaches are effective for MCQA distractor generation and QARA. We release PlausibleQA as a resource for advancing QA research and enhancing LLM performance in distinguishing plausible distractors from correct answers."

tags:
  - Question Answering
  - Multi-choice QA
  - Large Language Models
  - Score A

featured: true
share: false           # Removes social sharing buttons
show_related: false    # Removes related content
profile: false         # Removes author card
show_last_modified: false       # Removes "Last updated" date
reading_time: false    # Removes reading time estimate

# Custom links
links:
  - name: Paper
    url: 'https://dl.acm.org/doi/10.1145/3726302.3730299'
    icon_pack: fas
    icon: file-pdf
  - name: Code
    url: 'https://github.com/DataScienceUIBK/PlausibleQA/tree/main'
    icon_pack: fab
    icon: github
  - name: Dataset
    url: 'https://huggingface.co/datasets/JamshidJDMY/PlausibleQA'
    icon_pack: fas
    icon: database

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''


---

