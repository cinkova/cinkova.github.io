---
layout: custom
title: 'My Presentation'
---

<!DOCTYPE html>
<html>
  <head>
    <!-- Include Reveal.js styles (you might need to adjust the path) -->
    <link rel="stylesheet" href="lib/jsreveal/dist/reveal.css">
  </head>
  <body>
    <!-- Add the Reveal.js initialization script here -->
    <script src="lib/jsreveal/dist/reveal.js"></script>
    <script>
      Reveal.initialize({
        controls: true,
        progress: true,
        history: true,
        center: true,
        transition: 'slide'
      });
    </script>

    <div class="reveal">
      <div class="slides">
        <section>
          <h1>Slide 1</h1>
        </section>
        <section>
          <h1>Slide 2</h1>
        </section>
      </div>
    </div>
  </body>
</html>
