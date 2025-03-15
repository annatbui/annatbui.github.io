---
layout: default
permalink: /cv/
title: CV
nav: true
nav_order: 3
cv_pdf: assets/pdf/cv-2024.pdf
description: 
toc:
  sidebar: left
---


<!-- Show Download Button for Mobile -->
<div class="mobile-only" style="text-align: center; margin-bottom: 20px; padding: 15px; background-color: #f0f0f0; border-radius: 8px;">
  <a href="{{ site.baseurl }}/assets/pdf/cv-2024.pdf" class="btn btn-primary" target="_blank" style="color: white; background-color: #007bff; padding: 10px 20px; border-radius: 5px; text-decoration: none;">
    📎 Download CV (PDF)
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
