---
layout: archive
title: "Reports, Thesis"
permalink: /reports/
author_profile: true
excerpt: "Tim Ozdemir"
header:
  overlay_image: research-report.jpg  # teaser: photo-nyc-1.jpg
  caption: "Research Reports, SU, HU"

---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.reports %}
  {% include archive-single.html %}
{% endfor %}
