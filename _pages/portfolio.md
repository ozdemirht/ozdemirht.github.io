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

<table style="border: none;margin: 0px auto;">
<tr>
 <th> Visualization (Exploratory Data Analysis)</th> <th> </th>
</tr>

<tr>
<td>
<a href="https://github.com/ozdemirht/Data-Science/tree/master/matplotlib/ex1/example.ipynb">
<img src="/images/matplotlib-1.png" alt="https://ozdemirht.github.io/" width="200" height="250">
</a>
<br> <a href="https://matplotlib.org/contents.html">Matplotlib</a> Example 
</td>

<td>
<a href="https://github.com/ozdemirht/Data-Science/blob/master/seaborn/ex1/example.ipynb">
<img src="/images/seaborn.png" alt="https://ozdemirht.github.io/" width="200" height="250">
</a>
<br> <a href="https://seaborn.pydata.org/">Seaborn</a> Example 
</td>
</tr>

<tr>  
 <th>Dimension Reduction</th> <th>Clustering</th>
</tr>

<tr>
 <td>
  <a href="https://github.com/ozdemirht/Data-Science/blob/master/learn/pca/ex1/example.ipynb">
   <img src="/images/pca-1.png" alt="https://ozdemirht.github.io/" width="200" height="250">
  </a>
  <br> Classification methods (Logistic Regression, Decision Tree, Random Forest) after applying PCA. 
 </td>

 <td>
  <a href="https://github.com/ozdemirht/Data-Science/blob/master/learn/clustering/ex1/example.ipynb">
   <img src="/images/kmeans-1.png" alt="https://ozdemirht.github.io/" width="200" height="250">
  </a>
  <br> K-Means (from <a href="https://scikit-learn.org/">Scikit-learn</a> )
 </td>
</tr>

<tr>
 <th>Regression</th> <th>Classification</th>
</tr>

<tr>
 <td>
  <a href="https://github.com/ozdemirht/Data-Science/blob/master/learn/regression/ex1/example.ipynb">
   <img src="/images/regression-1.png" alt="https://ozdemirht.github.io/" width="200" height="250">
  </a>
  <br> Regression methods (Linear, Ridge, Lasso, ElasticNet, Huber) 
 </td>

 <td>
  <a href="https://github.com/ozdemirht/Data-Science/blob/master/learn/classification/ex1/example.ipynb">
   <img src="/images/classification-1.png" alt="https://ozdemirht.github.io/" width="200" height="250">
  </a>
  <br>  DNNClassifier, LinearClassifier (from <a href="https://www.tensorflow.org/">TensorFlow</a>)
 </td>
</tr>
</table>

{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}

