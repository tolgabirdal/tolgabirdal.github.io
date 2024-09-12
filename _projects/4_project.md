---
layout: page
title: Synchronization in Computer Vision
description: Investigates the uncertainties and ambiguities in 3D vision problems such as pose estimation, reconstruction and etc.
img: assets/img/sync.jpg
importance: 4
category: work
giscus_comments: false
related_publications: false
---

Many of the computer vision problems involve processing multiple entities be it objects, shapes, views or scenes. In such cases, graphs a.k.a. networks, are the key data structures for storing and organizing information. Yet, relationships between individual entities that had to be encoded in the edges often remain pairwise, or rather local. One of the most well accepted methods of seeking a global agreement is enforcing cycle-consistency, where the local errors are distributed over the entire graph such that the composition of maps/transforms along the cycles is close to the identity map. This art of consistently recovering absolute quantities from a collection of ratios is known as synchronization. From training generative adverserial networks to geometric structure from motion algorithms, from temporal video understanding to image-to-image translation, this capability of imposing consistency benefits a wide variety of vision tasks. In this tutorial, we first introduce the fundamentals of cycle-consistency and review the broad range of studies that make use of it. Next, we cover different techniques for solving multiview synchronization problems in computer vision, or in other words for achieving cycle consistency. Several techniques including graph theory, combinatorial optimization, Riemannian geometry, spectral decomposition, (non-)convex optimization, and MAP inference will be addressed. We also touch upon recent techniques that jointly optimize neural networks across multiple domains. Besides optimization techniques, we will also discuss the uncertainty and ambiguities inherent either in the data or in the model and show how the existing tools can be augmented to yield this valuable piece of information. We will finally showcase the applications of synchronizing linear/non-linear maps (e.g. functional maps) in multi-view based geometry reconstruction (RGB images or RGBD images), joint analysis of image collections, 3D reconstruction and understanding across multiple domains. This projects targets developing tools and methods acting as common techniques across several sub-fields of computer vision such as multi-view structure-from-motion, 3D geometry reconstruction, unsupervised map/object discovery, joint learning of neural networks and end-to-end multiview processing.

## Related Publications
<div class="publications">
  {% bibliography -f papers -q @*[key=huang2022multiway]* %}gojcic2020learning
  {% bibliography -f papers -q @*[key=huang2021multibodysync]* %}
  {% bibliography -f papers -q @*[key=birdal2021quantum]* %}
  {% bibliography -f papers -q @*[key=gojcic2020learning]* %}
  {% bibliography -f papers -q @*[key=birdal2020synchronizing]* %}
  {% bibliography -f papers -q @*[key=birdal2019probabilistic]* %}
  {% bibliography -f papers -q @*[key=birdal2018bayesian]* %}
</div>