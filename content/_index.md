---
title: ''
summary: ''
date: 2024-01-01
type: landing

design:
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      username: me
      text: ''
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: md
      avatar:
        size: medium
        shape: circle
  - block: markdown
    content:
      title: 'Research'
      subtitle: ''
      text: |-
        My central question is how to make robots that learn from and act alongside people robust and trustworthy in real-world deployment, not merely on standard benchmarks. I pursue this through **human-centered robot learning**, organised around three interconnected themes:

        **Foundations of Deep Reinforcement Learning** --- Understanding multi-step methods, memory architectures, and value estimation in partially observable environments (*Neural Networks* 2026, *IROS* 2021, *ICPR* 2020).

        **Preference Learning for Robotics** --- Enabling robots to learn from human preferences rather than hand-crafted rewards, with applications to interactive systems and assistive manipulation (*ACM THRI* 2021, ongoing work on patchable preference learning).

        **Real-World Deployment & Human-Robot Interaction** --- Translating learning algorithms to physical robots and large-scale public installations, including the Royal Ontario Museum deployment with 60,000+ visitors and partnerships with Boeing Research and Suburban Connect.
    design:
      columns: '1'
  - block: markdown
    content:
      title: 'Teaching & Supervision'
      subtitle: ''
      text: |-
        **Teaching** --- Co-designed and co-taught the Reinforcement Learning and Human-Robot Interaction sessions of Monash University's ECE4078 Intelligent Robotics unit (Semester 2, 2026).

        **Final Year Projects** --- Supervised 15 undergraduate students across 5 projects (2025--2026) on preference learning, deep reinforcement learning, VR-teleoperated dexterous grasping, and humanoid locomotion safety.

        **PhD co-supervision (Monash University)** --- Jin Siang Ong (perception-aware shared autonomy for fragile-object manipulation, RO-MAN 2026) and Emmanuel Fashae (interpretable models of human organisational preferences, HRI 2026).
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2
  - block: collection
    content:
      title: All Publications
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation
  - block: markdown
    id: contact
    content:
      title: Contact
      text: |-
        **Dr. Lingheng Meng**

        CERC Postdoctoral Fellow, CSIRO Technology
        Adjunct Lecturer, Monash University

        **Email:** lingheng.meng [at] csiro.au

        [Google Scholar](https://scholar.google.ca/citations?user=ieZQPZEAAAAJ&hl=en) |
        [GitHub](https://github.com/LinghengMeng) |
        [ORCID](https://orcid.org/0000-0001-9419-5774)
---
