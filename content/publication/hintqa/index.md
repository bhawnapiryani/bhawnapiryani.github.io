---
title: 'Exploring Hint Generation Approaches for Open-Domain Question Answering'

# Authors
authors:
  - Jamshid Mozafari
  - Abdelrahman Abdallah
  - admin
  - Adam Jatowt

date: '2024-11-12T00:00:00Z'
doi: '10.18653/v1/2024.findings-emnlp.546'

# Schedule page publish date (NOT publication's date)
publishDate: '2024-11-12T00:00:00Z'

# Publication type
publication_types: ['1']

# Publication name and optional abbreviated publication name
publication: "Findings of the Association for Computational Linguistics: EMNLP 2024"
publication_short: "EMNLP 2024"

abstract: "Automatic Question Answering (QA) systems rely on contextual information to provide accurate answers. Commonly, contexts are prepared through either retrieval-based or generation-based methods. The former involves retrieving relevant documents from a corpus like Wikipedia, whereas the latter uses generative models such as Large Language Models (LLMs) to generate the context. In this paper, we introduce a novel context preparation approach called HINTQA, which employs Automatic Hint Generation (HG) techniques. Unlike traditional methods, HINTQA prompts LLMs to produce hints about potential answers for the question rather than generating relevant context. We evaluate our approach across three QA datasets including TriviaQA, Natural Questions, and Web Questions, examining how the number and order of hints impact performance. Our findings show that the HINTQA surpasses both retrieval-based and generation-based approaches. We demonstrate that hints enhance the accuracy of answers more than retrieved and generated contexts."


tags:
  - Question Answering
  - Large Language Models
  - Hint
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
    url: 'https://aclanthology.org/2024.findings-emnlp.546/'
    icon_pack: fas
    icon: file-pdf
  - name: Code
    url: 'https://github.com/datascienceuibk/hintqa'
    icon_pack: fab
    icon: github
  - name: Dataset
    url: 'https://huggingface.co/datasets/JamshidJDMY/HintQA/tree/main'
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

