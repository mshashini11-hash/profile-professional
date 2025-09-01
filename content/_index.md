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

  # Hobbies section
  - block: markdown
    content:
      title: "Hobbies"
      text: |
        <div class="w-full max-w-[90%] mx-auto py-12">

          <!-- Hobby 1: Art -->
          <div class="grid grid-cols-1 md:grid-cols-2 gap-8 items-center mb-12">
            <div class="md:order-2 text-center">
              <a href="/hobbies/art">
                <img src="/uploads/artwork1.jpg" alt="Art" class="rounded-lg shadow-lg w-full max-w-md hover:scale-105 transition-transform duration-300">
              </a>
            </div>
            <div class="md:order-1">
              <p class="text-gray-800 text-lg">
                I enjoy painting and digital art. Exploring colors and abstract forms allows me to connect creativity with logical problem solving.
              </p>
            </div>
          </div>

          <!-- Hobby 2: Photography -->
          <div class="grid grid-cols-1 md:grid-cols-2 gap-8 items-center mb-12">
            <div class="text-center md:order-2">
              <a href="/hobbies/photography">
                <img src="/uploads/photography1.jpg" alt="Photography" class="rounded-lg shadow-lg w-full max-w-md hover:scale-105 transition-transform duration-300">
              </a>
            </div>
            <div class="md:order-1">
              <p class="text-gray-800 text-lg">
                Photography lets me capture mathematical patterns in nature and architecture. Each photo is a story of symmetry and structure.
              </p>
            </div>
          </div>

        </div>
    design:
      columns: 1
---










