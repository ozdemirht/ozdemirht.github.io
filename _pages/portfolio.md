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

Data Science
------

<table>
<tr>
 <th> Visualization</th> <th> </th>
</tr>

<tr>
<td>
<a href="https://github.com/ozdemirht/Data-Science/tree/master/matplotlib/ex1/example.ipynb">
<img src="/images/matplotlib-1.png" alt="https://ozdemirht.github.io/" width="200" height="250">
</a>
<br> Matplotlib Example 
</td>

<td>
<a href="https://github.com/ozdemirht/Data-Science/blob/master/seaborn/ex1/example.ipynb">
<img src="/images/seaborn.png" alt="https://ozdemirht.github.io/" width="200" height="250">
</a>
<br> Seaborn Example 
</td>
</tr>
</table>


{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}
