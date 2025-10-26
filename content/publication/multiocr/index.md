---
title: 'Evaluating Robustness of LLMs in Question Answering on Multilingual Noisy OCR Data'

# Authors
authors:
  - admin
  - Jamshid Mozafari
  - Adam Jatowt

date: '2025-10-10T00:00:00Z'
doi: '10.1145/3746252.3761295'

# Schedule page publish date (NOT publication's date)
#publishDate: '2025-10-10T00:00:00Z'

# Publication type
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name
publication: In *CIKM '25 Proceedings of the 34th ACM International Conference on Information and Knowledge Management*
publication_short: In *CIKM '25*

abstract: Optical Character Recognition (OCR) plays a crucial role in digitizing historical and multilingual documents, yet OCR errors - imperfect extraction of text, including character insertion, deletion, and substitution can significantly impact downstream tasks like question-answering (QA). In this work, we conduct a comprehensive analysis of how OCR-induced noise affects the performance of Multilingual QA Systems. To support this analysis, we introduce a multilingual QA dataset MultiOCR-QA, comprising 50K question-answer pairs across three languages, English, French, and German. The dataset is curated from OCR-ed historical documents, which include different levels and types of OCR noise. We then evaluate how different state-of-the-art Large Language Models (LLMs) perform under different error conditions, focusing on three major OCR error types. Our findings show that QA systems are highly prone to OCR-induced errors and perform poorly on noisy OCR text. By comparing model performance on clean versus noisy texts, we provide insights into the limitations of current approaches and emphasize the need for more noise-resilient QA systems in historical digitization contexts.
# Summary (optional - appears in listings)
summary: A large-scale question answering dataset based on historical American newspaper pages.

tags:
  - Multilingual QA
  - Historical Documents
  - Large Language Models
  - OCR Text
  - Score A


url_pdf: ''
url_code: 'https://github.com/DataScienceUIBK/MultiOCR-QA'
url_dataset: 'https://huggingface.co/datasets/Bhawna/MultiOCR-QA'
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://arxiv.org/abs/2502.16781'
url_video: ''

# Display this page in the Featured widget?
featured: true
---

