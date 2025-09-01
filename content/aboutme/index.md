---
title: "About Me"
type: aboutme
intro: "When I’m not unraveling the mysteries of knots and quantum topology, you can usually find me with a paintbrush in hand..."
---

<p>Born and raised in the lush hills of Kandy, Sri Lanka...</p>

<figure class="story-img">
  <img src="/uploads/kandy.png" alt="Hills of Kandy">
  <figcaption>The misty hills of Kandy</figcaption>
</figure>

<p>As a child, I spent hours sketching patterns...</p>

<figure class="story-img">
  <img src="/uploads/art1.jpeg" alt="Art sketching">
  <figcaption>Painting to explore new perspectives</figcaption>
</figure>

<p>My passion for numbers led me to pursue higher education abroad...</p>

<figure class="story-img">
  <img src="/uploads/hike1.jpeg" alt="Nature trail">
  <figcaption>Exploring nature trails for inspiration</figcaption>
</figure>

<div class="clear-both"></div>

<div class="video-container my-6">
  <iframe src="https://www.youtube.com/embed/YOUR_VIDEO_ID" frameborder="0" allowfullscreen></iframe>
</div>
<p class="video-caption text-center text-gray-600 mb-6">A talk on knot theory</p>

<section class="gallery-section mb-6">
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

<section class="gallery-section mb-6">
  <h2>My Paintings</h2>
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

<div id="lightbox" class="lightbox hidden">
  <button id="lb-close" class="lb-close" aria-label="Close">×</button>
  <img id="lb-img" src="" alt="">
  <p id="lb-caption" class="lb-caption"></p>
</div>

<script>
(function(){
  const links = document.querySelectorAll('.gallery-link');
  const lb = document.getElementById('lightbox');
  const lbImg = document.getElementById('lb-img');
  const lbCaption = document.getElementById('lb-caption');
  const lbClose = document.getElementById('lb-close');

  function openLB(href, caption){
    lbImg.src = href;
    lbCaption.textContent = caption;
    lb.classList.remove('hidden');
    document.body.style.overflow = 'hidden';
  }
  function closeLB(){
    lb.classList.add('hidden');
    lbImg.src = '';
    lbCaption.textContent = '';
    document.body.style.overflow = '';
  }

  links.forEach(a => a.addEventListener('click', e => {
    e.preventDefault();
    openLB(a.href, a.dataset.caption);
  }));
  lbClose.addEventListener('click', closeLB);
  lb.addEventListener('click', e => { if(e.target===lb) closeLB(); });
  document.addEventListener('keydown', e => { if(e.key==='Escape') closeLB(); });
})();
</script>












