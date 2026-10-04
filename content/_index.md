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
    design:
      css_class: dark
      avatar:
        size: large
        shape: square
      background:
        color: black
        image:
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false

  # Quick links to each main section
  - block: explore
    id: explore
    content:
      title: Explore

  # Embedded CV below the bio
  - block: cv-embed
    id: cv
    content:
      title: Curriculum Vitae
      pdf: uploads/resume.pdf


---

















