
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

        NYCU KIR Lab focuses on advancing artificial intelligence through Knowledge Inference and Knowledge Reasoning.

        We investigate how intelligent systems can uncover hidden knowledge from complex data, understand relationships, and combine evidence to derive meaningful conclusions.

        Department of Computer Science,
        National Yang Ming Chiao Tung University, Taiwan.

  
  
  - block: research-map
    id: research
    content:
      title: Research Area
      items:
        - name: Reasoning & Explainable AI
          icon: "🧠"
          tone: mint
          description: Advancing interpretable and knowledge-grounded AI reasoning through large language models, graph-based representations, and explainability techniques.
          branches:
            - label: Knowledge Graph Embeddings & Reasoning
            - label: LLM Reasoning
            - label: GraphRAG
            - label: Concept Bottleneck Models
            - label: Model Explainability & Interpretability

        - name: World Models & Reinforcement Learning
          icon: "🌍"
          tone: lavender
          description: Developing adaptive AI systems that learn representations of dynamic environments, reason across modalities, and improve decision-making through reinforcement learning.
          branches:
            - label: Multi-domain & Multi-modal World Modeling
            - label: Applied Reinforcement Learning
            - label: RL-Enhanced LLMs

        - name: AI for Real-World Systems
          icon: "🏙️"
          tone: peach
          description: "Bridging AI research and practical applications through intelligent modeling, prediction, and control of complex real-world systems, including smart cities and healthcare."
          branches:
            - label: Smart Cities
              topics:
                - Time-Series Modeling
                - Intelligent Control
            - label: AI for Healthcare
              topics:
                - Clinical NLP
                - Graph-based EHR Analysis
                - Early Warning System
            - label: Real-Time AI
              topics:
                - Small Language Models
                - Dynamic Graph Modeling
                - Multi-Agent RL Control

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

        **Location:** Room EC120, Engineering Building 3, Guangfu Campus

        **Address:** No. 1001, University Road,
        Hsinchu City 300093, Taiwan

        **Email:** [lpyting@cs.nycu.edu.tw](mailto:lpyting@cs.nycu.edu.tw)

        **Lab Supervisor:** [Lo Pang-Yun Ting](https://lpyting.github.io/)

---
