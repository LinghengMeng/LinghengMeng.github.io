---
title: ''
summary: ''
date: 2024-01-01
type: landing

design:
  spacing: '1.5rem'

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
        My research on **human-centered robot learning** is organised around three interconnected themes:

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
      title: Publications
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation

---
