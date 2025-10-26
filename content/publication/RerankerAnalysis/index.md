---
title: 'How Good are LLM-based Rerankers? An Empirical Analysis of State-of-the-Art Reranking Models'

# Authors
authors:
  - Abdelrahman Abdallah
  - admin
  - Jamshid Mozafari
  - Mohammed Ali
  - Adam Jatowt

date: '2025-08-12T00:00:00Z'
doi: '10.18653/v1/2024.findings-emnlp.562'

# Schedule page publish date (NOT publication's date)
#publishDate: '2025-08-12T00:00:00Z'

# Publication type
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name
publication: "Findings of the Association for Computational Linguistics EMNLP 2025"
publication_short: "EMNLP 2025"

abstract: In this work, we present a systematic and comprehensive empirical evaluation of state-of-the-art reranking methods, encompassing large language model (LLM)-based, lightweight contextual, and zero-shot approaches, with respect to their performance in information retrieval tasks. We evaluate in total 22 methods, including 40 variants (depending on used LLM) across several established benchmarks, including TREC DL19, DL20, and BEIR, as well as a novel dataset designed to test queries unseen by pretrained models. Our primary goal is to determine, through controlled and fair comparisons, whether a performance disparity exists between LLM-based rerankers and their lightweight counterparts, particularly on novel queries, and to elucidate the underlying causes of any observed differences. To disentangle confounding factors, we analyze the effects of training data overlap, model architecture, and computational efficiency on reranking performance. Our findings indicate that while LLM-based rerankers demonstrate superior performance on familiar queries, their generalization ability to novel queries varies, with lightweight models offering comparable efficiency. We further identify that the novelty of queries significantly impacts reranking effectiveness, highlighting limitations in existing approaches

tags:
  - QA
  - Rerankers
  - Score A*

# Display this page in the Featured widget?
featured: true

share: false           # Removes social sharing buttons
show_related: false    # Removes related content
profile: false         # Removes author card
show_date: false       # Removes "Last updated" date
reading_time: false    # Removes reading time estimate

# Links - order matters for display
links:
  - name: Paper
    url: 'https://arxiv.org/abs/2508.16757'
    icon_pack: fas
    icon: file-pdf
  - name: Code
    url: 'https://github.com/DataScienceUIBK/llm-reranking-generalization-study'
    icon_pack: fab
    icon: github
  - name: Dataset
    url: 'https://huggingface.co/datasets/abdoelsayed/FutureQueryEval'
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

