---
layout: page
title: Topological Deep Learning
description: A new way to work with higher-order, complex data in the context of deep learning. 
img: assets/img/TDL.jpg
importance: 1
category: work
related_publications: true
---

Topological deep learning is a rapidly growing field that pertains to the development of deep learning models for data supported on topological domains such as simplicial complexes, cell complexes, and hypergraphs, which generalize many domains encountered in scientific computations. 

Traditional machine learning often assumes that the observed data of interest are supported on a linear vector space and can be described by a set of feature vectors. However, there is growing awareness that, in many cases, this view- point is insufficient to describe several data within the real world. For example, molecules may be described more appropriately by graphs than feature vectors. Other examples include three-dimensional objects represented by meshes, as encountered in computer graphics and geometry processing, or data supported on top of a complex social network of interrelated actors. Hence, there has been an increased interest in importing concepts from geometry and topology into the usual machine learning pipelines to gain further insights into such types of data in a systematic way.

TDL is concerned with algebraic-topology integrated into deep learning frameworks. Topology is concerned with the study of properties that remain invariant under continuous deformations, and affords a powerful lens through which the global structure of data can be discerned. By characterizing topological features (including connected components, loops, and voids across multiple scales), topological tools such as persistent homology (Carlsson, 2009; Edelsbrunner & Harer, 2010) have become powerful methods to capture essential structures and patterns that elude conventional methods.

Going beyond the existing paradigm of persistent-homology, four practical advantages of TDL are as follows. First, the topology of the underlying data space determines the choice of possible neural network architectures. Second, topological domains enable the modeling of data containing multi-way interactions (also known as higher-order relations). Third, TDL captures regularities inherent to manifolds, such as ‘remeshing symmetry’. Fourth, TDL captures topological equivariances in the data. In summary, TDL takes into ac- count topological characteristics that appear in relational data, and therefore is a natural choice for various machine learning problems.

<!--
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

You can also put regular text between your rows of images, even citations {% cite einstein1950meaning %}.
Say you wanted to write a bit about your project before you posted the rest of the images.
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
-->
