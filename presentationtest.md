---
layout: custom
title: 'My Presentation'
---

<!DOCTYPE html>
<html>
  <head>
    <link rel="stylesheet" href="lib/jsreveal/dist/reveal.css">
  </head>
  <body>
    <div class="reveal">
      <div class="slides">
        <section>
          <h1>Slide 1</h1>
          ~~~ sdparse
Hlas jeden z daleka , hlas volá člověka
nsubj(volá, Hlas)
nummod(Hlas, jeden)
case(daleka, z)
nmod(Hlas, daleka)
appos(Hlas, hlas)
obj(volá, člověka)

~~~ 

          <div id="visualization-1"></div>
        </section>
        <section>
          <h1>Slide 2</h1>
          <!-- Add annodoc visualization code here -->
          <div id="visualization-2"></div>
        </section>
      </div>
    </div>
    <script src="lib/jsreveal/dist/reveal.js"></script>
    <script>
      Reveal.initialize();
    </script>

    <!-- Include the annodoc scripts here -->
    <script src="lib/local/annodoc.js"></script>
    <script>
      // Initialize annodoc here and add the visualization data
      Annodoc.initialize({
        container: 'visualization-1',
        data: yourVisualizationDataForSlide1
      });

      Annodoc.initialize({
        container: 'visualization-2',
        data: yourVisualizationDataForSlide2
      });
    </script>
  </body>
</html>
