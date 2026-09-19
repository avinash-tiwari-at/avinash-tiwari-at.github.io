---
title: Photos
layout: default
---

# Photo Gallery

<div class="gallery">
  {% for file in site.static_files %}
    {% if file.path contains '/assets/photos/' %}
      {% assign ext = file.extname | downcase %}
      {% if ext == '.jpg' or ext == '.jpeg' or ext == '.png' or ext == '.webp' %}
        <img src="{{ file.path }}" alt="Gallery Photo" onclick="openLightbox(this)">
      {% endif %}
    {% endif %}
  {% endfor %}
</div>

<!-- Lightbox -->
<div id="lightbox" class="lightbox" onclick="closeLightbox()">
  <img id="lightbox-img">
</div>
