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

  # About Me + Skills + Hobbies in one markdown block
  - block: markdown
    content:
      title: "About Me & Skills"
      text: |
        <p>I am a fifth-year Ph.D. candidate in Mathematics at Michigan State University, currently on the academic job market. My research focuses on quantum topology and knot theory, with an interest in integrating computational approaches into mathematical exploration. Alongside my research, I am deeply engaged in teaching and the development of innovative teaching and learning techniques that connect abstract mathematical ideas with technology and coding.</p>

        <h3>Technical Skills</h3>
        <ul>
          <li>Python – 90%</li>
          <li>LaTeX – 100%</li>
          <li>SQL – 40%</li>
        </ul>

        <h3>Languages</h3>
        <ul>
          <li>English – 100%</li>
          <li>Sinhala – 75%</li>
        </ul>

        <h3>Hobbies</h3>
        <p>Click on the images below to explore my hobbies:</p>
        <div style="display:flex; gap:1rem; flex-wrap:wrap;">
          <a href="/hobbies/art">
            <img src="/uploads/artwork1.jpg" alt="Art" style="width:200px; border-radius:10px;"/>
          </a>
          <a href="/hobbies/photography">
            <img src="/uploads/photography1.jpg" alt="Photography" style="width:200px; border-radius:10px;"/>
          </a>
        </div>
    design:
      columns: 1








