---
title: ""
date: 2022-10-24
type: landing

sections:
  # Resume/Bio block
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
        size: medium
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

  # Skills block
  - block: skills
    content:
      title: My Skills
      subtitle: Technical Skills & Languages
      skills:
        - name: Python
          percent: 90
          icon: code-bracket
        - name: LaTeX
          percent: 100
          icon: file-text
        - name: SQL
          percent: 40
          icon: circle-stack
      languages:
        - name: English
          percent: 100
        - name: Sinhala
          percent: 75
    design:
      columns: 2

  # About Me block
  - block: markdown
    content:
      title: "About Me"
      text: |
        I am a fifth-year Ph.D. candidate in Mathematics at Michigan State University, currently on the academic job market. My research focuses on quantum topology and knot theory, with an interest in integrating computational approaches into mathematical exploration. Alongside my research, I am deeply engaged in teaching and the development of innovative teaching and learning techniques that connect abstract mathematical ideas with technology and coding.
    design:
      columns: 1

  # Hobbies / Portfolio block
  - block: gallery
    content:
      title: "My Hobbies"
      subtitle: "Click on an image to explore more"
      items:
        - title: "Art"
          image:
            filename: artwork1.jpg
            alt: "My Art"
          description: "Some of my personal art projects."
          url: "/hobbies/art"
        - title: "Photography"
          image:
            filename: photography1.jpg
            alt: "Photography"
          description: "Capturing moments and landscapes."
          url: "/hobbies/photography"
    design:
      columns: 2

  # Recent News
  - block: collection
    id: news
    content:
      title: Recent News
      subtitle: ""
      text: ""
      page_type: post
      count: 5
      filters:
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      offset: 0
      order: desc
    design:
      view: date-title-summary
      spacing:
        padding: [0, 0, 0, 0]

---








