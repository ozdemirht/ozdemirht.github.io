---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
excerpt: "Tim Ozdemir"
header:
  overlay_image: research-and-development.jpg #Data-Science-BG.jpg  # teaser: photo-nyc-1.jpg
  caption: "Publications, Papers"

---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
