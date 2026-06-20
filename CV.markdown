---
layout: default
title: CV
hide_title: true
permalink: /cv/
---



<div style="max-width: 850px; margin: 0 auto;">

  <!-- Download button (always visible) -->
  <div style="text-align: center; margin-bottom: 1rem;">
    <a href="{{ '/assets/CV.pdf' | relative_url }}" download
       style="display: inline-block; padding: 0.5rem 1.25rem; background: #b31b1b; color: #fff; text-decoration: none; border-radius: 6px; font-weight: 600;">
      Download PDF
    </a>
  </div>

  <!-- Mobile fallback: direct link to open PDF (hidden on desktop) -->
  <div class="cv-mobile-fallback" style="display: none; text-align: center; padding: 2rem 1rem;">
    <p style="margin-bottom: 1rem; color: #555;">PDF preview is not supported on mobile browsers.</p>
    <a href="{{ '/assets/CV.pdf' | relative_url }}" target="_blank"
       style="display: inline-block; padding: 0.75rem 2rem; background: #b31b1b; color: #fff; text-decoration: none; border-radius: 6px; font-weight: 600; font-size: 1.1em;">
      Open CV
    </a>
  </div>

  <!-- PDF iframe (hidden on mobile) -->
  <iframe src="{{ '/assets/CV.pdf' | relative_url }}#toolbar=0"
          class="cv-iframe"
          width="100%" height="1100px" style="border: none;">
  </iframe>

</div>
