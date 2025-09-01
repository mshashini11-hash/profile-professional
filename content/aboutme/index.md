---
title: "About Me"
type: aboutme
intro: "When I’m not unraveling the mysteries of knots and quantum topology, you can usually find me with a paintbrush in hand, exploring the colors of the world, or wandering through nature trails, camera in tow."
---

<!-- STORY: use HTML so floats wrap properly -->

<p>
  <strong>Born and raised in the lush hills of Kandy, Sri Lanka</strong>, I grew up curious about patterns—both in math and in life. My early education there laid the foundation for a lifelong fascination with learning, creativity, and adventure.
</p>

<figure class="float-right">
  <img src="/uploads/kandy.png" alt="Hills of Kandy">
  <figcaption>The misty hills of Kandy</figcaption>
</figure>

<p>
  Growing up, I spent hours sketching patterns and noticing mathematical symmetries in everyday things. These early hours with pencil and paper quietly nudged me toward both art and mathematics.
</p>

<figure class="float-left">
  <img src="/uploads/art1.jpeg" alt="Art and Math">
  <figcaption>Blending art with mathematical ideas</figcaption>
</figure>

<p>
  My passion for numbers led me to pursue higher education abroad. During my Ph.D., I focused on quantum topology and knot theory—presenting at conferences and publishing papers along the way.
</p>

<!-- responsive YouTube embed -->
<div class="video-container">
  <iframe src="https://www.youtube.com/embed/YOUR_VIDEO_ID" frameborder="0" allowfullscreen></iframe>
</div>
<p class="video-caption">A talk on knot theory.</p>

<p>
  When not immersed in equations, I explore the world through painting, photography, and hiking. These creative outlets often feed back into my math.
</p>

<figure class="float-right">
  <img src="/uploads/hike1.jpeg" alt="Hiking">
  <figcaption>Exploring trails for fresh ideas</figcaption>
</figure>

<div class="clear-both"></div>

<!-- GALLERIES: plain HTML so clickable and independent of shortcodes -->
<section class="gallery-section">
  <h2>Travel Photography</h2>
  <div class="gallery-grid">
    <a class="gallery-link" href="/uploads/hike1.jpeg" data-caption="Knuckles Range">
      <img src="/uploads/hike1.jpeg" alt="Travel 1">
      <div class="thumb-caption">Knuckles Range</div>
    </a>
    <a class="gallery-link" href="/uploads/kandy.png" data-caption="Kandy Hills">
      <img src="/uploads/kandy.png" alt="Travel 2">
      <div class="thumb-caption">Kandy Hills</div>
    </a>
  </div>
</section>

<section class="gallery-section">
  <h2>Paintings</h2>
  <div class="gallery-grid">
    <a class="gallery-link" href="/uploads/art1.jpeg" data-caption="Abstract Colors">
      <img src="/uploads/art1.jpeg" alt="Painting 1">
      <div class="thumb-caption">Abstract Colors</div>
    </a>
    <a class="gallery-link" href="/uploads/art1.jpeg" data-caption="Geometric Inspiration">
      <img src="/uploads/art1.jpeg" alt="Painting 2">
      <div class="thumb-caption">Geometric Inspiration</div>
    </a>
  </div>
</section>

<!-- LIGHTBOX + minimal JS (works without extra assets) -->
<div id="lightbox" class="lightbox hidden" aria-hidden="true">
  <button id="lb-close" class="lb-close" aria-label="close">×</button>
  <img id="lb-img" src="" alt="">
  <p id="lb-caption" class="lb-caption"></p>
</div>

<script>
  (function(){
    // gallery lightbox
    const links = document.querySelectorAll('.gallery-link');
    const lb = document.getElementById('lightbox');
    const lbImg = document.getElementById('lb-img');
    const lbCaption = document.getElementById('lb-caption');
    const lbClose = document.getElementById('lb-close');

    function openLB(href, caption) {
      lbImg.src = href;
      lbCaption.textContent = caption || '';
      lb.classList.remove('hidden');
      document.body.style.overflow = 'hidden';
    }
    function closeLB() {
      lb.classList.add('hidden');
      lbImg.src = '';
      lbCaption.textContent = '';
      document.body.style.overflow = '';
    }

    links.forEach(a => {
      a.addEventListener('click', function(e){
        e.preventDefault();
        openLB(this.href, this.dataset.caption);
      });
    });
    lbClose.addEventListener('click', closeLB);
    lb.addEventListener('click', function(e){
      if(e.target === lb) closeLB();
    });
    document.addEventListener('keydown', function(e){ if(e.key === 'Escape') closeLB(); });
  })();
</script>









