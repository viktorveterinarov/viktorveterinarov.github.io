---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<div class="pdf-container">
  <!-- Embed PDF -->
  <embed src="/files/ViktorVeterinarovCV.pdf" type="application/pdf" width="80%" height="1000px" class="desktop-pdf">
  
  <!-- Fallback for mobile users -->
  <p class="mobile-fallback" style="text-align: left;">
    You can download my CV <a href="/files/ViktorVeterinarovCV.pdf" download>here</a>.
  </p>
</div>

<style>
  .pdf-container {
    width: 100%;
    max-width: 800px; /* Limit the width for better readability */
    margin: 0 auto; /* Center the content */
  }
  .desktop-pdf {
    display: block;
  }
  .mobile-fallback {
    display: none; /* Hide fallback text by default */
  }
  @media (max-width: 768px) {
    .desktop-pdf {
      display: none; /* Hide PDF embed for smaller screens */
    }
    .mobile-fallback {
      display: block; /* Show fallback text for mobile users */
    }
  }
</style>
