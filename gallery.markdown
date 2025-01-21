---
layout: gallery
title: Gallery
permalink: /gallery/
---

<header class="header-background">
  {% include header.html %}
  <div>
      <article class="container mx-auto px-2 mt2 mb4">
  <header>
    <h1 class="h0 py-4 mt-3">Gallery</h1>
  </header>
  <div class="col-4 sm-width-full border-top-thin">
  </div>
  <div class="prose mb-4 py-4">
    <p>Hi! I do graphic design as a hobby.</p>
  </div>
</header>

<div class="container mx-auto px-2">
    <div class="prose mb-4 py-4">
        {% include image-gallery.html folder="/assets/images/gallery" %}
    </div>
</div>