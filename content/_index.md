---
title: 'Home'
date: 2023-10-24
type: landing

design:
  spacing: '2rem'

sections:
  - block: biography
    content:
      username: admin
    design:
      biography:
        style: 'text-align: left; font-size: 1.05em; line-height: 1.75; max-width: 760px;'
      avatar:
        size: large
        shape: rounded

  - block: markdown
    content:
      title: Research Interests
      text: |
        <div style="columns: 2; column-gap: 3rem; font-size: 1.05em; line-height: 1.9;">
        <ul>
        <li>Natural Language Processing</li>
        <li>Temporal Question Answering</li>
        <li>Temporal Information Retrieval</li>
        <li>Information Retrieval</li>
        <li>Historical Document Retrieval</li>
        <li>Retrieval-Augmented Generation</li>
        <li>Large Language Models</li>
        </ul>
        </div>

  - block: collection
    id: publications
    content:
      title: Selected Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title: Academic Positions
      text: |
        <div style="border-top: 1px solid #e5e7eb; padding-top: 1rem;">

        <p><strong style="color:#0b3d91;">2022 – Present</strong><br>
        <strong>PhD Researcher</strong><br>
        Data Science Group, Digital Science Center, University of Innsbruck, Austria</p>

        <p><strong style="color:#0b3d91;">2016</strong><br>
        <strong>Software Engineer Intern</strong><br>
        LIS Nepal, Nepal</p>

        </div>

  - block: markdown
    content:
      title: Awards
      text: |
        <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(220px, 1fr)); gap: 1rem;">
          <div style="padding: 1rem; border: 1px solid #e5e7eb; border-radius: 10px;">
            University of Innsbruck PhD Scholarship Award
          </div>
          <div style="padding: 1rem; border: 1px solid #e5e7eb; border-radius: 10px;">
            Dean's List Award, Pokhara University
          </div>
          <div style="padding: 1rem; border: 1px solid #e5e7eb; border-radius: 10px;">
            Master's Semester Scholarship, Pokhara University
          </div>
        </div>
---
