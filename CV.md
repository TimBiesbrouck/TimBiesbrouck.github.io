---
layout: page
title: "CV"
---
<div class="pdf-container">
  <iframe
    src="{{ '/Tim_Biesbrouck_CV.pdf' | relative_url }}"
    title="Curriculum vitae"
    loading="lazy">
  </iframe>
</div>

<p>
  <a href="{{ '/Tim_Biesbrouck_CV.pdf' | relative_url }}">Open CV as a PDF</a>
</p>

<style>
  .pdf-container {
    width: 100%;
    height: min(85vh, 1000px);
    min-height: 640px;
    border: 1px solid #ddd;
    overflow: hidden;
  }

  .pdf-container iframe {
    display: block;
    width: 100%;
    height: 100%;
    border: 0;
  }

  @media (max-width: 700px) {
    .pdf-container {
      height: 75vh;
      min-height: 520px;
    }
  }
</style>

