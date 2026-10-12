
---
title:
type: landing

sections:
  - block: hero
    id: home
    content:
      title: |
        NYCU KIR Lab
      image:
        filename: welcome.jpg
      text: |
        Welcome to the official website of **NYCU KIR Lab**.

        We are a research laboratory in the
        Department of Computer Science at
        National Yang Ming Chiao Tung University (NYCU), Taiwan.

  
  - block: markdown
    id: research
    content:
      title: Research
      text: |
        Our research interests include:

        - **Data Mining:** Discovering meaningful patterns and knowledge from complex datasets.

        - **Reinforcement Learning:** Developing intelligent decision-making methods through interaction and feedback.

        - **Knowledge Graph Embedding and Reasoning:** Learning structured knowledge representations and exploring relationships for intelligent reasoning.

        - **AI in Healthcare:** Applying AI techniques to healthcare data and clinical decision support.

        - **Time Series Analysis:** Modeling temporal dependencies and extracting insights from sequential data.

  
  - block: people
    id: people
    content:
      title: People
      user_groups:
        - Principal Investigators
        - Grad Students
        - Alumni
      sort_by: Params.last_name
      sort_ascending: true
    design:
      show_interests: true
      show_role: true
      show_social: true

  - block: markdown
    content:
      text: |
        [View All Members](/people/)


  
  - block: collection
    id: publications
    content:
      title: Publications
      count: 5
      offset: 0
      order: desc
      filters:
        folders:
          - publication
    design:
      view: compact
      columns: '1'

  - block: markdown
    content:
      text: |
        [View All Publications →](/publication/)


  - block: collection
    id: news
    content:
      title: Latest News
      count: 3
      offset: 0
      order: desc
      page_type: post
    design:
      view: compact
      columns: '1'

  - block: markdown
    content:
      text: |
        [View All News →](/post/)


  - block: markdown
    id: contact
    content:
      title: Contact
      text: |
        NYCU KIR Lab

        Department of Computer Science

        National Yang Ming Chiao Tung University

        Taiwan

        Contact details will be added soon.
---
