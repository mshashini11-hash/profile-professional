---
title: ""
date: 2025-09-01
type: landing

sections:

  # Resume / Bio / Skills / Languages
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

  # About Me paragraphs + images using markdown
  - block: markdown
    content:
      title: "About Me"
      text: |
        <div style="display:flex; align-items:center; margin-bottom:3rem;">
          <div style="flex:1; padding-right:2rem;">
            <p>I am a fifth-year Ph.D. candidate in Mathematics at Michigan State University, currently on the academic job market. My research focuses on quantum topology and knot theory, with an interest in integrating computational approaches into mathematical exploration.</p>
          </div>
          <div style="flex:1;">
            <img src="/uploads/portrait1.jpg" style="width:100%; border-radius:10px;" alt="Portrait 1">
          </div>
        </div>

        <div style="display:flex; align-items:center; margin-bottom:3rem;">
          <div style="flex:1;">
            <img src="/uploads/portrait2.jpg" style="width:100%; border-radius:10px;" alt="Portrait 2">
          </div>
          <div style="flex:1; padding-left:2rem;">
            <p>Alongside my research, I am deeply engaged in teaching and the development of innovative teaching and learning techniques that connect abstract mathematical ideas with technology and coding.</p>
          </div>
        </div>

  # Hobbies gallery
  - block: markdown
    content:
      title: "Hobbies"
      text: |
        <div style="display:flex; gap:2rem; flex-wrap:wrap;">
          <a href="/hobbies/art">
            <img src="/uploads/artwork1.jpg" alt="Art" style="width:300px; border-radius:10px;">
          </a>
          <a href="/hobbies/photography">
            <img src="/uploads/photography1.jpg" alt="Photography" style="width:300px; border-radius:10px;">
          </a>
        </div>
---











