---
title: 'Evaluating Robustness of LLMs in Question Answering on Multilingual Noisy OCR Data'

# Authors
authors:
  - admin
  - Jamshid Mozafari
  - Abdelrahman Abdallah
  - Antoine Doucet
  - Adam Jatowt

date: '2025-10-10T00:00:00Z'
doi: '10.1145/3746252.3761295'

# Schedule page publish date (NOT publication's date)
publishDate: '2025-02-10T00:00:00Z'

# Publication type
publication_types: ['1']

# Publication name and optional abbreviated publication name
publication: "CIKM '25: Proceedings of the 34th ACM International Conference on Information and Knowledge Management"
publication_short: "CIKM'25"

abstract: "Optical Character Recognition (OCR) plays a crucial role in digitizing historical and multilingual documents, yet OCR errors - imperfect extraction of text, including character insertion, deletion, and substitution can significantly impact downstream tasks like question-answering (QA). In this work, we conduct a comprehensive analysis of how OCR-induced noise affects the performance of Multilingual QA Systems. To support this analysis, we introduce a multilingual QA dataset MultiOCR-QA, comprising 50K question-answer pairs across three languages: English, French, and German. The dataset is curated from OCR-ed historical documents, which include different levels and types of OCR noise. We then evaluate how different state-of-the-art Large Language Models (LLMs) perform under different error conditions, focusing on three major OCR error types. Our findings show that QA systems are highly prone to OCR-induced errors and perform poorly on noisy OCR text. By comparing model performance on clean versus noisy texts, we provide insights into the limitations of current approaches and emphasize the need for more noise-resilient QA systems in historical digitization contexts."

summary: Evaluating how OCR noise affects LLM performance on multilingual question answering tasks.

tags:
  - Multilingual QA
  - Historical Documents
  - Large Language Models
  - OCR Text
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
    url: 'https://arxiv.org/abs/2502.16781'
    icon_pack: fas
    icon: file-pdf
  - name: Code
    url: 'https://github.com/DataScienceUIBK/MultiOCR-QA'
    icon_pack: fab
    icon: github
  - name: Dataset
    url: 'https://huggingface.co/datasets/Bhawna/MultiOCR-QA'
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

# Featured image
# Place an image named `featured.jpg/png` in this page's folder to display it
image:
  caption: 'MultiOCR-QA Dataset Overview'
  focal_point: ''
  preview_only: false
---

