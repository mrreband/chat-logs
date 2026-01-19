---
layout: default
---

<style>
.pinned-summary {
  position: sticky; top: 0; background: white;
  padding: 1rem; border: 2px solid #0969da;
  cursor: pointer; z-index: 1000; font-weight: bold;
}
.content { padding: 2rem; min-height: 200vh; }
.details-content { display: none; }
.details-content.open { display: block; }
</style>

<div class="pinned-summary" onclick="toggleContent()">
  📋 Click to expand details (stays pinned on scroll)
</div>

<div class="content">
  <div id="detailsContent" class="details-content">

# Your Main Heading

This is **bold** and *italic* Markdown that renders properly.

## Subsections work too

- List item 1
- List item 2 with `inline code`
- [Links work](https://github.com)

```python
# Code blocks render with syntax highlighting
def hello():
    print("World!")
