---
title: Photos
layout: default
---

# Photo Gallery

<div class="gallery">
  <img src="/assets/photos/photo1.jpg" alt="Photo 1" onclick="openLightbox(this)">
  <img src="/assets/photos/photo2.jpg" alt="Photo 2" onclick="openLightbox(this)">
  <img src="/assets/photos/photo3.jpg" alt="Photo 3" onclick="openLightbox(this)">
</div>

<!-- Lightbox -->
<div id="lightbox" class="lightbox" onclick="closeLightbox()">
  <img id="lightbox-img">
</div>
