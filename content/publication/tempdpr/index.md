---
title: 'TempRetriever: Fusion-based Temporal Dense Passage Retrieval for Time-Sensitive Questions'

# Authors
authors:
  - Abdelrahman Abdallah
  - admin
  - Jonas Wallat
  - Avishek Anand
  - Adam Jatowt

date: '2025-10-25T00:00:00Z'

# Schedule page publish date (NOT publication's date)
publishDate: '2025-10-25T00:00:00Z'

# Publication type
publication_types: ['1']

# Publication name and optional abbreviated publication name
publication: "WSDM '26: Proceedings of the Nineteenth ACM International Conference on Web Search and Data Mining"
publication_short: "WSDM '26"

abstract: "Temporal awareness is crucial in many information retrieval tasks, particularly in scenarios where the relevance of documents depends on their alignment with the query's temporal context. Traditional retrieval methods such as BM25 and Dense Passage Retrieval (DPR) excel at capturing lexical and semantic relevance but fall short in addressing time-sensitive queries. To bridge this gap, we introduce the temporal retrieval model that integrates explicit temporal signals by incorporating query timestamps and document dates into the representation space. Our approach ensures that retrieved passages are not only topically relevant but also temporally aligned with user intent. We evaluate our approach on two large-scale benchmark datasets, ArchivalQA and ChroniclingAmericaQA, achieving substantial performance gains over standard retrieval baselines. In particular, our model improves Top-1 retrieval accuracy by 6.63% and NDCG@10 by 3.79% on ArchivalQA, while yielding a 9.56% boost in Top-1 retrieval accuracy and 4.68% in NDCG@10 on ChroniclingAmericaQA. Additionally, we introduce a time-sensitive negative sampling strategy, which refines the model's ability to distinguish between temporally relevant and irrelevant documents during training. Our findings highlight the importance of explicitly modeling time in retrieval systems and set a new standard for handling temporally grounded queries."

tags:
  - Temporal Question Answering
  - Temporal Retriever
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
    url: 'https://arxiv.org/abs/2502.21024v1'
    icon_pack: fas
    icon: file-pdf

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''


---

