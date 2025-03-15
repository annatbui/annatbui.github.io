---
layout: default
permalink: /cv/
title: CV
nav: true
nav_order: 3
cv_pdf: assets/pdf/cv-2024.pdf
description: |
  Below is my most recent CV. If the PDF does not load, you can 
  <a href="{{ site.baseurl }}/assets/pdf/cv-2024.pdf" target="_blank"></a>.
toc:
  sidebar: left
---


<!-- Show Download Button for Mobile -->
<div class="mobile-only" style="text-align: center; margin-bottom: 20px;">
  <a href="{{ site.baseurl }}/assets/pdf/cv-2024.pdf" class="btn btn-primary" target="_blank">
    📄 Download CV (PDF)
  </a>
</div>

<!-- Embed PDF for Desktop -->
<div class="desktop-only" style="position: relative; padding-bottom: 130%; height: 0; overflow: hidden; max-width: 100%; background: #f8f8f8;">
  <iframe 
      src="{{ site.baseurl }}/assets/pdf/cv-2024.pdf" 
      style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; border: none;"
      allowfullscreen>
  </iframe>
</div>

<!-- Make mobile/desktop display conditional -->
<style>
  @media (max-width: 768px) {
    .desktop-only { display: none; }
  }
  @media (min-width: 769px) {
    .mobile-only { display: none; }
  }
</style>
