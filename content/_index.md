---
title: ""
date: 2025-09-01
type: landing

sections:
  # Resume/Bio block (existing)
  - block: resume-biography-3
    content:
      username: admin
      text: ""
      button:
        text: Download CV
        url: uploads/resume.pdf
      # News card (shown next to Interests and Education)
      news:
        - date: "Nov 2026"
          text: "Named the MSU Graduate School's **Educator of the Month**."
          url: "https://grad.msu.edu/news-and-events/news/2026/11/november-eotm"
          link_text: "Read the feature"
    design:
      avatar:
        size: large
        shape: square

  # Quick links to each main section
  - block: explore
    id: explore
    content:
      title: Explore

  # Row of painting thumbnails (pulled from content/paintings)
  - block: paintings-strip
    id: paintings
    content:
      title: Paintings
      subtitle: "Oil portraits I paint outside of mathematics."
      count: 4

  # Embedded CV below the bio
  - block: cv-embed
    id: cv
    content:
      title: Curriculum Vitae
      pdf: uploads/resume.pdf


---

















