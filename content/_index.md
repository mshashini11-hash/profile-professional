---
title: ""
date: 2025-09-01
type: landing

sections:
  # Resume / Bio / Skills / Languages pulled from authors/admin/_index.md
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

  # About Me - Paragraph 1 with right image
  - block: image-text
    content:
      title: "About Me"
      text: "I am a fifth-year Ph.D. candidate in Mathematics at Michigan State University, currently on the academic job market. My research focuses on quantum topology and knot theory, with an interest in integrating computational approaches into mathematical exploration."
      image: "/uploads/portrait1.jpg"
      image_position: "right"
    design:
      columns: 1
      background:
        color: white

  # About Me - Paragraph 2 with left image
  - block: image-text
    content:
      title: ""
      text: "Alongside my research, I am deeply engaged in teaching and the development of innovative teaching and learning techniques that connect abstract mathematical ideas with technology and coding."
      image: "/uploads/portrait2.jpg"
      image_position: "left"
    design:
      columns: 1
      background:
        color: white

  # Hobbies Gallery
  - block: row
    content:
      title: "Hobbies"
      items:
        - title: "Art"
          image: "/uploads/artwork1.jpg"
          url: "/hobbies/art"
          description: "Exploring colors and abstract forms through painting and digital art."
        - title: "Photography"
          image: "/uploads/photography1.jpg"
          url: "/hobbies/photography"
          description: "Capturing patterns in nature and architecture through photography."
    design:
      columns: 2
      spacing:
        padding: [4, 0, 12, 0]
      background:
        color: white
---










