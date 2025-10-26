---
title: 'DeAR: DeAR: Dual-Stage Document Reranking with Reasoning Agents via LLM Distillation'

# Authors
authors:
  - Abdelrahman Abdallah
  - Jamshid Mozafari
  - admin
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

abstract: "Large Language Models (LLMs) have transformed listwise document reranking by enabling global reasoning over candidate sets, yet single models often struggle to balance fine-grained relevance scoring with holistic cross-document analysis. We propose DeepAgentRank (DeAR), an open-source framework that decouples these tasks through a dual-stage approach, achieving superior accuracy and interpretability. In Stage 1, we distill token-level relevance signals from a frozen 13B LLaMA teacher into a compact {3, 8}B student model using a hybrid of cross-entropy, RankNet, and KL divergence losses, ensuring robust pointwise scoring. In Stage 2, we attach a second LoRA adapter and fine-tune on 20K GPT-4o-generated chain-of-thought permutations, enabling listwise reasoning with natural-language justifications. Evaluated on TREC-DL19/20, eight BEIR datasets, and NovelEval-2306, DeAR surpasses open-source baselines by +5.1 nDCG@5 on DL20 and achieves 90.97 nDCG@10 on NovelEval, outperforming GPT-4 by +3.09. Without fine-tuning on Wikipedia, DeAR also excels in open-domain QA, achieving 54.29 Top-1 accuracy on Natural Questions, surpassing baselines like MonoT5, UPR, and RankGPT. Ablations confirm that dual-loss distillation ensures stable calibration, making DeAR a highly effective and interpretable solution for modern reranking systems."
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
    url: 'https://arxiv.org/abs/2508.16998'
    icon_pack: fas
    icon: file-pdf
  - name: Code
    url: 'https://github.com/DataScienceUIBK/DeAR-Reranking'
    icon_pack: fab
    icon: github



url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

---

