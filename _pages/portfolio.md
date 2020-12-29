---
layout: archive
title: "Portfolio"
permalink: /portfolio/
author_profile: true
excerpt: "Tim Ozdemir"
header:
  overlay_image: Data-Science-BG.jpg  # teaser: photo-nyc-1.jpg
  caption: "Data Engineering and Science"
---

{% include base_path %}

<p>
<a href="https://github.com/ozdemirht/Data-Science/tree/master/matplotlib/ex1/example.ipynb">
<img src="/images/matplotlib-1.png" alt="https://ozdemirht.github.io/" width="200" height="250">
</a>
Data Science: Visualization: Matplotlib Example 
</p>


{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}

