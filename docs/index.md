---
# Front matter for Jekyll layout/theme
layout: default
---

<style>
.pinned-summary {
  position: sticky; top: 0;
  background: white; padding: 1rem;
  border-bottom: 2px solid #0969da; cursor: pointer;
  z-index: 1000;
}
.content { padding: 2rem; min-height: 200vh; }
.details-content { display: none; }
.details-content.open { display: block; }
</style>

<div class="pinned-summary" onclick="toggleContent()">
  📋 Click to expand (stays pinned)
</div>

<div class="content">
  <div id="detailsContent" class="details-content">
    ## Unlimited scrollable Markdown content
    - Works perfectly on GitHub Pages
    - No SVG height limits
    - Native browser scrolling
  </div>
</div>

<script>
function toggleContent() {
  document.getElementById('detailsContent').classList.toggle('open');
}
</script>
