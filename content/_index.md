---
title: 'Home'
date: 2023-10-24
type: landing

design:
  spacing: '4rem'

sections:
  - block: biography
    content:
      username: admin
    design:
      banner:
        filename: kalen-emsley-Bkci_8qcdvQ-unsplash.jpg
      biography:
        style: 'text-align: left; font-size: 1em; line-height: 1.7; max-width: 760px;'
      avatar:
        size: large
        shape: rounded

  - block: markdown
    content:
      title: Research Interests
      text: |
        - Natural Language Processing
        - Temporal Question Answering
        - Information Retrieval
        - Historical Document Retrieval
        - Retrieval-Augmented Generation

  - block: collection
    id: publications
    content:
      title: Selected Publications
      filters:
        folders:
          - publication
        featured_only: false
    design:
      view: citation
      columns: '1'

  - block: experience
    content:
      username: admin
    design:
      date_format: 'January 2006'
      is_education_first: true

  - block: awards
    content:
      title: Awards
      username: admin
---
