---
title: 'ASRank: Zero-Shot Re-Ranking with Answer Scent for Document Retrieval'

# Authors
authors:
  - Abdelrahman Abdallah
  - Jamshid Mozafari
  - admin
  - Adam Jatowt

date: '2025-04-12T00:00:00Z'
doi: '10.18653/v1/2025.findings-naacl.161'

# Schedule page publish date (NOT publication's date)
#publishDate: '2025-04-12T00:00:00Z'

# Publication type
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name
publication: "Findings of the Association for Computational Linguistics: NAACL 2025"
publication_short: "NAACL 2025"

abstract: "Retrieval-Augmented Generation (RAG) models have drawn considerable attention in modern open-domain question answering. The effectiveness of RAG depends on the quality of the top retrieved documents. However, conventional retrieval methods sometimes fail to rank the most relevant documents at the top. In this paper, we introduce ASRANK, a new re-ranking method based on scoring retrieved documents using zero-shot answer scent which relies on a pre-trained large language model to compute the likelihood of the document-derived answers aligning with the answer scent. Our approach demonstrates marked improvements across several datasets, including NQ, TriviaQA, WebQA, ArchivalQA, HotpotQA, and Entity Questions. Notably, ASRANK increases Top-1 retrieval accuracy on NQ from 19.2% to 46.5% for MSS and 22.1% to 47.3% for BM25. It also shows strong retrieval performance on several datasets compared to state-of-the-art methods (47.3 Top-1 by ASRANK vs 35.4 by UPR by BM25)."

tags:
  - RAG
  - QA
  - Reranking
  - Score A

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
    url: 'https://aclanthology.org/2025.findings-naacl.161/'
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

