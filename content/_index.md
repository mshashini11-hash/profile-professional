---
title: ""
date: 2025-09-01
type: landing

sections:
  # Resume/Bio block (top)
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

  # Skills & Languages under Interests/Education
  - block: markdown
    content:
      title: "Skills & Languages"
      text: |
        <div class="mb-12 p-6 bg-white rounded-xl shadow-md max-w-7xl mx-auto">
          <h3 class="text-2xl font-bold text-[#18453B] mb-4">Technical Skills</h3>
          <ul class="list-disc list-inside text-gray-800 mb-6">
            <li>Python – 90%</li>
            <li>LaTeX – 100%</li>
            <li>SQL – 40%</li>
          </ul>

          <h3 class="text-2xl font-bold text-[#18453B] mb-4">Languages</h3>
          <ul class="list-disc list-inside text-gray-800">
            <li>English – 100%</li>
            <li>Sinhala – 75%</li>
          </ul>
        </div>
    design:
      columns: 1

  # Hobbies section (alternating layout + gallery)
  - block: markdown
    content:
      title: "Hobbies"
      text: |
        <div class="max-w-7xl mx-auto">
          <!-- Hobby 1 -->
          <div class="grid grid-cols-1 md:grid-cols-2 gap-8 items-center mb-12">
            <div class="text-center md:order-2">
              <img src="/uploads/artwork1.jpg" alt="Art" class="rounded-lg shadow-lg w-full max-w-sm">
            </div>
            <div class="md:order-1">
              <p class="text-gray-800 text-lg">
                I enjoy painting and digital art. Exploring colors and abstract forms allows me to connect creativity with logical problem solving.
              </p>
            </div>
          </div>

          <!-- Hobby 2 -->
          <div class="grid grid-cols-1 md:grid-cols-2 gap-8 items-center mb-12">
            <div>
              <p class="text-gray-800 text-lg">
                Photography lets me capture mathematical patterns in nature and architecture. Each photo is a story of symmetry and structure.
              </p>
            </div>
            <div class="text-center">
              <img src="/uploads/photography1.jpg" alt="Photography" class="rounded-lg shadow-lg w-full max-w-sm">
            </div>
          </div>

          <!-- Mini galleries -->
          <h3 class="text-2xl font-bold text-[#18453B] mb-4">Explore More</h3>
          <div class="grid grid-cols-2 md:grid-cols-4 gap-4 mb-12">
            <a href="/hobbies/art">
              <img src="/uploads/artwork2.jpg" alt="Artwork 2" class="rounded-lg shadow-md w-full">
            </a>
            <a href="/hobbies/art">
              <img src="/uploads/artwork3.jpg" alt="Artwork 3" class="rounded-lg shadow-md w-full">
            </a>
            <a href="/hobbies/photography">
              <img src="/uploads/photo2.jpg" alt="Photo 2" class="rounded-lg shadow-md w-full">
            </a>
            <a href="/hobbies/photography">
              <img src="/uploads/photo3.jpg" alt="Photo 3" class="rounded-lg shadow-md w-full">
            </a>
          </div>
        </div>
    design:
      columns: 1
---










