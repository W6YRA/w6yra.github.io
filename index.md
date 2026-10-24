---
layout: page
title: "Home"
---

<h1 class="intro-heading">Welcome to the UCLA Amateur Radio Club!</h1>
<p class="intro-content">
  We are a community of Bruins dedicated to the art and science of amateur (HAM) radio — everything from collegiate contesting, HF experimentation, satellite communication, digital modes, and much more.

  Whether you're a licensed operator, a complete beginner, or just curious about radio technology, you're in the right place.
</p>

<div class="carousel">
  <button class="carousel-btn prev" aria-label="Previous photo">&#10094;</button>
  <div class="carousel-pics">
    <img src="assets\images\IMG_0263.jpg">
    <img src="assets\images\20260311_175301.jpg">
    <img src="assets\images\20260515_172903.jpg">
    <img src="assets\images\DSC00865.jpg">
    <img src="assets\images\IMG_0203.jpg">
  </div>
  <button class="carousel-btn next" aria-label="Next photo">&#10095;</button>
</div>

<script>
  document.querySelectorAll('.carousel').forEach(function (c) {
    var track = c.querySelector('.carousel-pics');
    c.querySelector('.prev').onclick = function () {
      track.scrollBy({ left: -track.clientWidth * 0.7, behavior: 'smooth' });
    };
    c.querySelector('.next').onclick = function () {
      track.scrollBy({ left: track.clientWidth * 0.7, behavior: 'smooth' });
    };
  });
</script>