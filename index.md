---
layout: default
title: Home
body_class: home
---

<div class="hero-banner-wrap">
  <img
    class="hero-banner"
    src="{{ '/assets/img/main-header.png' | relative_url }}"
    alt="Weird Wild West"
  >
</div>

<div class="home-grid">
  <a class="home-tile" href="{{ '/story/' | relative_url }}">
    <img src="{{ '/assets/img/ssf.png' | relative_url }}" alt="The Story So Far">
  </a>

  <a class="home-tile" href="{{ '/glossary/' | relative_url }}">
    <img src="{{ '/assets/img/glossary-header.png' | relative_url }}" alt="The Glossary">
  </a>
</div>

<div class="home-grid">
  <div class="circle">
    <img class="circle-img" src="{{ '/assets/img/journal.png' | relative_url }}" alt="Quill and journal">
  </div>

  <div class="circle">
    <img class="circle-img" src="{{ '/assets/img/treasure.png' | relative_url }}" alt="Treasure sack and trunk">
  </div>
</div>

