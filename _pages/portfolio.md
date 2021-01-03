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

<table style="border: none;margin: 0px auto;vertical-align:bottom;background-color:#f3f2f7">
<tr>
 <th> Visualization (Exploratory Data Analysis)</th> <th> </th>
</tr>

<tr>
<td style="white-space:wrap;text-align:center;vertical-align:bottom">
<a href="https://github.com/ozdemirht/Data-Science/tree/master/matplotlib/ex1/example.ipynb">
<img src="/images/matplotlib-1.png" alt="https://ozdemirht.github.io/" width="200" height="250">
</a>
<br> <span style="font-weight:bold;font-family:verdana;color:blue;font-size:14px"><a href="https://matplotlib.org/contents.html">Matplotlib</a> Example </span>
</td>

<td style="white-space:wrap;text-align:center;vertical-align:bottom">
<a href="https://github.com/ozdemirht/Data-Science/blob/master/seaborn/ex1/example.ipynb">
<img src="/images/seaborn.png" alt="https://ozdemirht.github.io/" width="200" height="250">
</a>
<br> <span style="font-weight:bold;font-family:verdana;color:blue;font-size:14px"><a href="https://seaborn.pydata.org/">Seaborn</a> Example</span> 
</td>
</tr>

<tr>  
 <th>Dimension Reduction</th> <th>Clustering</th>
</tr>

<tr>
 <td style="white-space:wrap;text-align:center;vertical-align:bottom">
  <a href="https://github.com/ozdemirht/Data-Science/blob/master/learn/pca/ex1/example.ipynb">
   <img src="/images/pca-1.png" alt="https://ozdemirht.github.io/" width="200" height="250">
  </a>
  <br> <span style="font-weight:bold;font-family:verdana;color:blue;font-size:14px">Classification methods (Logistic Regression, Decision Tree, Random Forest) after applying PCA</span> 
 </td>

 <td style="white-space:wrap;text-align:center;vertical-align:bottom">
  <a href="https://github.com/ozdemirht/Data-Science/blob/master/learn/clustering/ex1/example.ipynb">
   <img src="/images/kmeans-1.png" alt="https://ozdemirht.github.io/" width="200" height="250">
  </a>
  <br> <span style="font-weight:bold;font-family:verdana;color:blue;font-size:14px">K-Means (using <a href="https://scikit-learn.org/">Scikit-learn</a> )</span>
 </td>
</tr>

<tr>
 <th>Regression</th> <th>Classification</th>
</tr>

<tr>
 <td style="white-space:wrap;text-align:center;vertical-align:bottom">
  <a href="https://github.com/ozdemirht/Data-Science/blob/master/learn/regression/ex1/example.ipynb">
   <img src="/images/regression-1.png" alt="https://ozdemirht.github.io/" width="200" height="250">
  </a>
  <br> <span style="font-weight:bold;font-family:verdana;color:blue;font-size:14px">Regression methods (Linear, Ridge, Lasso, ElasticNet, Huber)</span> 
 </td>

 <td style="white-space:wrap;text-align:center;vertical-align:bottom">
  <a href="https://github.com/ozdemirht/Data-Science/blob/master/learn/classification/ex1/example.ipynb">
   <img src="/images/classification-1.png" alt="https://ozdemirht.github.io/" width="200" height="250">
  </a>
  <br><span style="font-weight:bold;font-family:verdana;color:blue;font-size:14px">DNNClassifier, LinearClassifier (using <a href="https://www.tensorflow.org/">TensorFlow</a>)</span>
 </td>
</tr>
</table>

Data Engineering
------
<table style="border: none;margin: 0px auto;vertical-align:bottom;background-color:#f3f2f7">

<tr>
<td style="white-space:wrap;text-align:center;vertical-align:bottom">
<a href="https://github.com/ozdemirht/Data-Enginering/blob/master/capstone/Capstone%20Project%20Report.ipynb">
<img src="/images/de-erd-1.png" alt="https://ozdemirht.github.io/" width="200" height="250">
</a>
<br> <span style="font-weight:bold;font-family:verdana;color:blue;font-size:14px">Project (Apache Spark, Matplotlib, pyspark)</span>  
</td>

<td style="white-space:wrap;text-align:center;vertical-align:bottom">
<a href="https://github.com/ozdemirht/Data-Enginering/tree/master/Project-4">
<img src="/images/de-erd-2.png" alt="https://ozdemirht.github.io/" width="200" height="250">
</a>
<br> <span style="font-weight:bold;font-family:verdana;color:blue;font-size:14px">Project (Star Schema, Apache Spark, AWS S3, and Python)</span> 
</td>
</tr>

<tr>
<td style="white-space:wrap;text-align:center;vertical-align:bottom">
<a href="https://github.com/ozdemirht/Data-Enginering/blob/master/project-2%20(Apache%20Cassandra)/Project_1B_%20Project.ipynb">
<img src="/images/de-cassandra.jpg" alt="https://ozdemirht.github.io/" width="200" height="250">
</a>
<br> <span style="font-weight:bold;font-family:verdana;color:blue;font-size:14px">NoSQL Apache Cassandra </span>  
</td>
 
<td style="white-space:wrap;text-align:center;vertical-align:bottom"> 
<a href="https://github.com/ozdemirht/Data-Enginering/tree/master/Project-4">
<img src="/images/data-science-1.png" alt="https://ozdemirht.github.io/" width="200" height="250"> 
</a>
<br> <span style="font-weight:bold;font-family:verdana;color:blue;font-size:14px">Project (Star Schema, AWS Redshift, AWS S3, and Python)</span> 
</td>
</tr> 

</table>


{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}

