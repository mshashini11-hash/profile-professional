---
title: 'Projects'           # Page title
date: 2024-05-19            # Page date
type: landing               # Page type (landing = uses sections)
design:
  spacing: '5rem'           # Section spacing

sections:
  - block: collection       # First block: project cards
    content:
      title: Selected Projects
      text: I enjoy making things. Here are a selection of projects that I have worked on over the years.
      filters:
        folders:
          - project
    design:
      view: article-grid
      fill_image: false
      columns: 3

  - block: text             # Second block: Topology papers
    content:
      title: "Topology"
      text: |
        - **Paper 1:** [Topology Paper Title](assets/papers/topology-paper.pdf) – 2023  
        - **Talk Slides:** [Topology Seminar Slides](assets/slides/topology-seminar.pdf)

  - block: text             # Third block: Education papers
    content:
      title: "Education"
      text: |
        - **Paper 2:** [Education Paper Title](assets/papers/education-paper.pdf) – 2024  
        - **Lecture Slides:** [Intro to Calculus Slides](assets/slides/calculus-intro.pdf)

  - block: text             # Fourth block: Talks
    content:
      title: "Talks"
      text: |
        - **Invited Talk 1:** [Talk Title](assets/papers/talk1.pdf) – 2025  
        - **Slides:** [Talk Slides PDF](assets/slides/talk1-slides.pdf)
---


