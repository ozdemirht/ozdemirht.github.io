---
title: "Patents"
layout: archive
permalink: /patents/
collection: patents
author_profile: true
excerpt: "Tim Ozdemir"
header:
  overlay_image: patent.jpg #  # teaser: photo-nyc-1.jpg
  caption: "Patents, USPTO"
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.patents reversed %}
  {% include archive-single.html %}
{% endfor %}
