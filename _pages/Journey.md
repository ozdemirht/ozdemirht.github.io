---
layout: archive
title: "Journey"
permalink: /journey/
author_profile: true 
excerpt: "Tim Ozdemir"
header:
  overlay_image: Data-Science-BG.jpg  # teaser: photo-nyc-1.jpg
  caption: "Data Engineering and Science"
---

{% include base_path %}

List of completed courses ..

{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}
