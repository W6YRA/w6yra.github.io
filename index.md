---
layout: page
title: "Home"
---

<h1 class="intro-heading">Welcome to the Bruin Amateur Radio Club!</h1>
<p class="intro-content">
  We' a're a community of Bruins dedicated to the art and science of amateur (HAM) radio—everything from collegiate contesting, HF experimentation, satellite communication, digital modes, and much more.
  <br>
  Whether you're a licensed operator, a complete beginner, or just curious about radio technology, you're in the right place.
</p>
<p class="intro-content">Meetings are Fridays weekly at 5pm, located at the radio shack (Boelter 8563-C). To get there, take the elevator located beside the SEASNet Cafe in Boelter Hall up to floor 8.</p>

<div class="socials">
  <a href="https://discord.gg/2aFBmqDwg9" class="icon-box"><i class="fa-brands fa-discord"></i></a>
</div>

<hr>

<div class="carousel">
  <button class="carousel-btn prev">&#10094;</button>
  <div class="carousel-pics">
    <img src="assets\images\IMG_0263.jpg">
    <img src="assets\images\20260311_175301.jpg">
    <img src="assets\images\20260515_172903.jpg">
    <img src="assets\images\DSC00865.jpg">
    <img src="assets\images\IMG_0203.jpg">
  </div>
  <button class="carousel-btn next">&#10095;</button>
</div>

<script>
  document.querySelectorAll('.carousel').forEach(function (c) {
    var track = c.querySelector('.carousel-pics');
    c.querySelector('.prev').onclick = function () {
      track.scrollBy({ left: -track.clientWidth * 0.6, behavior: 'smooth' });
    };
    c.querySelector('.next').onclick = function () {
      track.scrollBy({ left: track.clientWidth * 0.6, behavior: 'smooth' });
    };
  });
</script>

<hr>

<h1 class="intro-heading">2026-27 Officers</h1>
