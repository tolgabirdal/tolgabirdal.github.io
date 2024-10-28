---
layout: page
permalink: /publications/
title: Publications
description: Publications by categories in reversed chronological order.
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->
{% if author.googlescholar %} You can also find my articles on <a href="https://scholar.google.com/citations?user=_Bxd5ggAAAAJ&hl=en">my Google Scholar profile</a>. {% endif %}

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

{% bibliography %}

</div>
