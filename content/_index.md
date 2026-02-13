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
      button:
        text: Download CV
        url: uploads/resume.pdf
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
        My research advances **human-centered robot learning** through three interconnected themes:

        **Foundations of Deep Reinforcement Learning** --- Understanding multi-step methods, memory architectures, and value estimation in partially observable environments (*Neural Networks* 2025, *IROS* 2021, *ICPR* 2020).

        **Preference Learning for Robotics** --- Enabling robots to learn from human preferences rather than hand-crafted rewards, with applications to interactive systems and assistive manipulation (*ACM THRI* 2021, ongoing work on patchable preference learning).

        **Real-World Deployment & Human-Robot Interaction** --- Translating learning algorithms to physical robots and large-scale public installations, including the Royal Ontario Museum deployment with 60,000+ visitors and partnerships with Boeing Research and Suburban Connect.
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

        CERC Postdoctoral Fellow, CSIRO Data61
        Adjunct Lecturer, Monash University

        **Email:** [lingheng.meng@data61.csiro.au](mailto:lingheng.meng@data61.csiro.au)

        [Google Scholar](https://scholar.google.ca/citations?user=ieZQPZEAAAAJ&hl=en) |
        [GitHub](https://github.com/LinghengMeng) |
        [ORCID](https://orcid.org/0000-0001-9419-5774)
---
