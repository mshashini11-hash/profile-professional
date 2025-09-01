---
title: "About Me"
type: aboutme
intro: "I am a fifth-year Ph.D. candidate in Mathematics at Michigan State University. My research focuses on quantum topology and knot theory, and I am deeply engaged in teaching and educational development."

blocks:
  # Education and Thesis Block
  - block: markdown
    content:
      title: "Education"
      text: |
        <p>Ph.D. in Mathematics, Michigan State University (2021–2026)</p>
        <p>Thesis: <a href="https://example.com" target="_blank">Quantum Topology</a>, supervised by Prof. Efstratia Kalfagianni.</p>
        <p>BSc in Artificial Intelligence, MIT (2016–2020), GPA 3.9/4.0</p>
    design:
      image:
        src: "/uploads/grad-school.jpg"
        position: right
        size: 50%
      spacing:
        padding: [3, 3, 3, 3]

  # Alternate image on left
  - block: markdown
    content:
      title: "Research Interests"
      text: |
        <p>My research combines quantum topology, knot theory, and computational methods to explore low-dimensional manifolds. I also integrate coding and technology in my teaching approaches.</p>
    design:
      image:
        src: "/uploads/research.jpg"
        position: left
        size: 50%
      spacing:
        padding: [3, 3, 3, 3]

  # Hobbies Section (horizontal blocks)
  - block: collection
    content:
      title: "My Hobbies"
      text: "Click on each image to explore more."
      page_type: aboutme_hobby
    design:
      view: cards
      columns: 2
      spacing:
        padding: [3, 3, 3, 3]
      card:
        hover_shadow: true
        border_radius: xl
