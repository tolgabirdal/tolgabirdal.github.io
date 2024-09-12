---
layout: page
title: Data-driven 3D Local Features for Point Cloud Registration
description: 
img: assets/img/3dPPF.jpg
importance: 5
category: work
giscus_comments: false
related_publications: false
---

Developing robust and accurate methods for aligning 3D point clouds by learning discriminative feature descriptors is a long standing endeavor. Point clouds, which represent the shape and geometry of objects in 3D space, are critical for applications like 3D reconstruction, autonomous navigation, and augmented reality. Traditional methods rely on handcrafted features, but data-driven approaches leverage machine learning, particularly deep learning, to extract local features from point clouds. These learned features capture complex patterns and are invariant to transformations such as rotation and scale, enabling more precise and efficient point cloud registration in challenging environments.

Through a series of publications, we have explored the development of 3D local features suitable for use in autonomous driving as well as robotics applications like bin picking and navigation. Our methods can also be used for reconstructing scenes by aligning information from different views or scans.

## Related Publications
<div class="publications">
  {% bibliography -f papers -q @*[key=zhao20223dpointcaps]* %}
  {% bibliography -f papers -q @*[key=huang2022multiway]* %}
  {% bibliography -f papers -q @*[key=huang2021multibodysync]* %}
  {% bibliography -f papers -q @*[key=gojcic2020learning]* %}
  {% bibliography -f papers -q @*[key=zhao20193d]* %}
  {% bibliography -f papers -q @*[key=deng20193d]* %}
  {% bibliography -f papers -q @*[key=deng2018ppf]* %}
  {% bibliography -f papers -q @*[key=deng2018ppfnet]* %}
</div>