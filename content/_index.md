---
title: 'Home'
date: 2023-10-24
type: landing

design:
  spacing: '3rem'

sections:
  - block: biography
    content:
      username: admin
    design:
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
        - Temporal Information Retrieval
        - Information Retrieval
        - Historical Document Retrieval
        - Retrieval-Augmented Generation
        - Large Language Models

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

  - block: markdown
    content:
      title: Academic Positions
      text: |
        **2022 – Present**  
        **PhD Researcher**  
        Data Science Group, Digital Science Center, University of Innsbruck, Austria

        **2016**  
        **Software Engineer Intern**  
        LIS Nepal, Nepal

  - block: markdown
    content:
      title: Awards
      text: |
        - University of Innsbruck PhD Scholarship Award
        - Dean's List Award, Pokhara University
        - Master's Semester Scholarship, Pokhara University
---
