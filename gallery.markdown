---
layout: gallery
title: Gallery
permalink: /gallery/
---

<header class="header-background">
  {% include header.html %}
  <div class="container mx-auto px-2 mb-2 clearfix header-text">
    <h1 class="h0 inline-block col-9 sm-width-full py-4 mt-3 header-title">Gallery</h1>
    
    <div class="clearfix mb-4 py-1">
      <div class="col-4 sm-width-full left border-top-thin">
        <p class="h4 lh-condensed font-smoothing mt-2 py-1">Hi! I do graphic design as a hobby.</p>
      </div>
    </div>
  </div>
</header>

<div class="container mx-auto px-2">
    <div class="prose mb-4 py-4">
        {% include image-gallery.html folder="/assets/images/gallery" %}
    </div>
</div>