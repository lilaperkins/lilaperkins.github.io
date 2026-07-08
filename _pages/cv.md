---
layout: default
permalink: /cv/
title: CV
nav: true
nav_order: 5
cv_pdf: /assets/pdf/LilaPerkins_CV_Jul26.pdf # you can also use external links here
cv_format: rendercv # options: rendercv, jsonresume
description: This is a description of the page. You can modify it in '_pages/cv.md'. You can also change or remove the top pdf download button.
---

<div style="width: 100%; height: 90vh; margin-top: 1rem;">
  <iframe
    src="https://docs.google.com/viewer?url={{ site.url }}{{ page.cv_pdf }}&embedded=true"
    width="100%"
    height="100%"
    style="border: none; border-radius: 4px; box-shadow: 0 2px 8px rgba(0,0,0,0.15);">
  </iframe>
</div>
