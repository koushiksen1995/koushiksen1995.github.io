---
layout: page
title: Wolf-Rayet binaries
description: In very massive binaries, mass transfer can occur from a more massive star to a less massive star at a nuclear timescale and Wolf-Rayet stars on the main sequence. 
img: assets/img/project_wolf_rayet.jpg
importance: 2
category: research
giscus_comments: false
---

Wolf-Rayet stars are the brightest and hottest stars observable in the sky. The spectra of these stars show broad emission lines of hydrogen, helium, nitrogen, oxygen and/or carbon. They give out strong radiation-driven winds, <span id="dots2">...</span><span id="more2">enriching the interstellar medium with various heavy elements. While most Wolf-Rayet stars are expected to be burning helium in their cores, a handful are also on the main sequence of the Hertzsprung-Russell diagram and are presumably burning hydrogen in their cores. These stars are thought to be the direct progenitors of black holes! So, understanding the formation and evolution of these systems directly refines our knowledge of gravitational wave astronomy, a rapidly growing field.

I have shown that the evolution of very massive binaries challenges the conventional knowledge of binary evolution, all related to the luminosity of these stars being close to their Eddington luminosity. I have identified observed counterparts, confirming a novel binary evolution channel in which a more massive star can transfer mass to a less massive star on the nuclear timescale (reverse Algols). Furthermore, the mass donors can be observed as Wolf-Rayet stars. I am studying the observable properties of this class of binaries to understand their impact on their surroundings, as they have much higher wind mass-loss rates than ordinary single stars. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, _bled_ for your project, and then... you reveal its glory in the next row of images.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>

The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}

```html
<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
```

{% endraw %}
