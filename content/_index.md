
---
title:
type: landing

sections:
  - block: hero
    id: home
    content:
      title: |
        NYCU KIR Lab
      text: |
        **Knowledge Inference, Reasoning and Discovery Laboratory**

        Advancing research in data mining, reinforcement learning,
        knowledge graphs, AI in healthcare, and time series analysis.

        Department of Computer Science,
        National Yang Ming Chiao Tung University, Taiwan.

  
  
  - block: features
    id: research
    content:
      title: Research
      text: "Our research interests include:"
      items:
        - name: Data Mining
          description: Discovering meaningful patterns and knowledge from complex datasets.
          icon: search
          icon_pack: fas

        - name: Reinforcement Learning
          description: Developing intelligent decision-making methods through interaction and feedback.
          icon: robot
          icon_pack: fas

        - name: Knowledge Graph Embedding and Reasoning
          description: Learning structured knowledge representations and exploring relationships for intelligent reasoning.
          icon: project-diagram
          icon_pack: fas

        - name: AI in Healthcare
          description: Applying AI techniques to healthcare data and clinical decision support.
          icon: heartbeat
          icon_pack: fas

        - name: Time Series Analysis
          description: Modeling temporal dependencies and extracting insights from sequential data.
          icon: chart-line
          icon_pack: fas


  
  - block: people
    id: people
    content:
      title: People
      user_groups:
        - Lab Supervisor
        - "2026"
        - PhD Students
        - Alumni
      sort_by: Params.last_name
      sort_ascending: true
    design:
      show_interests: false
      show_role: true
      show_social: true

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
    id: contact
    content:
      title: Contact
      text: |
        **NYCU KIR Lab**

        **Location:** Room EC120, Guangfu Campus

        **Address:** No. 1001, University Road,
        Hsinchu City 300093, Taiwan

        **Email:** [lpyting@cs.nycu.edu.tw](mailto:lpyting@cs.nycu.edu.tw)

        **Lab Supervisor:** [Lo Pang-Yun Ting](https://lpyting.github.io/)

---
