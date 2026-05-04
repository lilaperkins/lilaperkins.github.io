---
layout: cv
permalink: /cv/
title: CV
nav: true
nav_order: 5
cv_pdf: /assets/pdf/LilaPerkins_CV_Apr26.pdf # you can also use external links here
cv_format: #rendercv # options: rendercv, jsonresume
description: This is a description of the page. You can modify it in '_pages/cv.md'. You can also change or remove the top pdf download button.
---

<div class="cv-pdf-container" style="width: 100%; height: 90vh; margin-top: 1rem;">
  <iframe
    src="{{ page.cv_pdf }}"
    width="100%"
    height="100%"
    frameborder="0"
    style="border: none; border-radius: 4px; box-shadow: 0 2px 8px rgba(0,0,0,0.15);">
    <p>
      Your browser doesn't support embedded PDFs.
      <a href="{{ page.cv_pdf }}">Download the PDF instead.</a>
    </p>
  </iframe>
</div>
