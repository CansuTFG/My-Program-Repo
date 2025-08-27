---
layout: home
title: Welcome
---

<div id="particles-js"></div>

<h1>New Site with pages</h1>
<p>This is a basic site created with GitHub Pages.</p>

Hello world! This is my Jekyll homepage.

<script src="https://cdn.jsdelivr.net/npm/particles.js@2.0.0/particles.min.js"></script>
<script>
  particlesJS.load('particles-js', '{{ "/assets/js/particles-config.json" | relative_url }}', function() {
    console.log('Particles.js loaded');
  });
</script>
