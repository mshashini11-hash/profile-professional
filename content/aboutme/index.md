---
title: "About Me"
type: aboutme

galleries:
  - title: "Travel"
    items:
      - image: "/uploads/hike1.jpeg"
        title: "Nepal"
        summary: "Hiking in the Himalayas."
      - image: "/uploads/art1.jpeg"
        title: "Italy"
        summary: "Exploring Venice."
  - title: "Paintings"
    items:
      - image: "/uploads/painting1.jpg"
        title: "Sunset"
        summary: "Acrylic on canvas."
      - image: "/uploads/painting2.jpg"
        title: "Forest"
        summary: "Watercolor piece."
---

<section class="prose lg:prose-lg mx-auto px-4 py-12">

  <h1 class="text-4xl font-bold text-center mb-12">About Me</h1>

  <!-- First image floated LEFT -->
  <figure class="float-left w-1/4 mr-6 mb-6">
    <img src="/uploads/kandy.png" alt="Hills of Kandy" class="rounded-xl shadow-md">
    <figcaption class="text-sm text-gray-600 mt-2 text-center">
      Hills of Kandy, where my journey began
    </figcaption>
  </figure>

  <p>
    Born and raised in the lush hills of Kandy, Sri Lanka, I grew up curious about
    patterns—both in math and in life. My early education there laid the foundation 
    for a lifelong fascination with learning, creativity, and adventure.
    I spent hours sketching patterns, watching the way sunlight danced through the trees, 
    and noticing mathematical structures in everyday life.
  </p>

  <!-- Second image floated RIGHT -->
  <figure class="float-right w-1/4 ml-6 mb-6">
    <img src="/uploads/art1.jpeg" alt="Exploring art and mathematics" class="rounded-xl shadow-md">
    <figcaption class="text-sm text-gray-600 mt-2 text-center">
      Art has always inspired my mathematical imagination
    </figcaption>
  </figure>

  <p>
    My passion for numbers and patterns led me to pursue higher education abroad. 
    During my Ph.D., I delved deep into quantum topology, knot theory, and the elegance 
    of abstract mathematics, presenting my work at conferences and publishing papers 
    along the way. These academic explorations not only deepened my expertise but also 
    taught me the importance of creativity in mathematics.
  </p>

  <!-- Third image floated LEFT -->
  <figure class="float-left w-1/4 mr-6 mb-6">
    <img src="/uploads/hike1.jpeg" alt="Hiking and creativity" class="rounded-xl shadow-md">
    <figcaption class="text-sm text-gray-600 mt-2 text-center">
      Hiking keeps me connected to nature and inspiration
    </figcaption>
  </figure>

  <p>
    When not immersed in equations, I explore the world through art and nature. 
    Painting, photography, and hiking allow me to slow down, notice details, 
    and stay inspired. These moments of creativity often feed back into my 
    mathematical thinking, reminding me that discovery and beauty go hand in hand.
  </p>

  <!-- Example YouTube embed with caption -->
  <figure class="float-right w-2/5 ml-6 mb-6">
    <iframe class="aspect-video rounded-lg shadow-md"
            src="https://www.youtube.com/embed/YOUR_VIDEO_ID"
            frameborder="0" allowfullscreen></iframe>
    <figcaption class="text-sm text-gray-600 mt-2 text-center">
      A talk I gave on knot theory
    </figcaption>
  </figure>

  <p>
    Sharing mathematics through talks and videos allows me to connect with 
    a wider audience and communicate the beauty of abstract ideas. 
    I enjoy blending storytelling with visuals to make abstract concepts 
    accessible and engaging.
  </p>

  <!-- Clear floats so galleries start clean -->
  <div class="clear-both"></div>

  <!-- Gallery 1 -->
  <h2 class="text-2xl font-bold mt-12 mb-6">Travel Photography</h2>
  <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
    <div class="rounded-xl shadow-md overflow-hidden">
      <img src="/uploads/hike1.jpeg" alt="Travel photo">
      <div class="p-4 text-center text-gray-700 text-sm">Capturing landscapes and cityscapes</div>
    </div>
    <div class="rounded-xl shadow-md overflow-hidden">
      <img src="/uploads/art1.jpeg" alt="Travel photo">
      <div class="p-4 text-center text-gray-700 text-sm">Exploring the world through my lens</div>
    </div>
  </div>

  <!-- Gallery 2 -->
  <h2 class="text-2xl font-bold mt-12 mb-6">My Paintings</h2>
  <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
    <div class="rounded-xl shadow-md overflow-hidden">
      <img src="/uploads/kandy.png" alt="Painting">
      <div class="p-4 text-center text-gray-700 text-sm">Inspired by Sri Lankan landscapes</div>
    </div>
    <div class="rounded-xl shadow-md overflow-hidden">
      <img src="/uploads/art1.jpeg" alt="Painting">
      <div class="p-4 text-center text-gray-700 text-sm">Abstract explorations in color</div>
    </div>
  </div>

</section>





