---
title: "Data Science Projects"
excerpt: "<img src='/images/data-science-2.jpg' width='500' height='300'>"
collection: portfolio
---

|-----------------+------------|
|:----------------|:-----------|
| Dimension Reduction | Clustering |
| <a href="https://github.com/ozdemirht/Data-Science/blob/master/learn/pca/ex1/example.ipynb"><img src="/images/pca-1.png" alt="https://ozdemirht.github.io/" width="200" height="250"> </a> <br> <span style="font-weight:bold;font-family:verdana;color:blue;font-size:14px">Classification methods (Logistic Regression, Decision Tree, Random Forest) after applying PCA</span> <br> <br> wine quality classification <br> Data Set: <a href="https://archive.ics.uci.edu/ml/datasets/wine+quality">Wine Quality Dataset</a> <br> Applied <a href="https://en.wikipedia.org/wiki/Principal_component_analysis">PCA</a> for dimension reduction on input vectors <br> Algorithms: Logistic Regression, Decision Tree, Random Forest (using <a href="https://scikit-learn.org/">Scikit-learn</a> )<br> Compared performance of algorithms |<a href="https://github.com/ozdemirht/Data-Science/blob/master/learn/clustering/ex1/example.ipynb"><img src="/images/kmeans-1.png" alt="https://ozdemirht.github.io/" width="200" height="250"></a><br> <span style="font-weight:bold;font-family:verdana;color:blue;font-size:14px">K-Means (using <a href="https://scikit-learn.org/">Scikit-learn</a> )</span> <br> Discover classes in a given data set<br> Data Set: <a href="https://archive.ics.uci.edu/ml/datasets/wine+quality">Wine Quality Dataset</a><br> Algorithm: K-Means clustering (using <a href="https://scikit-learn.org/">Scikit-learn</a>) |
| Regression | Classification |
| <a href="https://github.com/ozdemirht/Data-Science/blob/master/learn/regression/ex1/example.ipynb"><img src="/images/regression-1.png" alt="https://ozdemirht.github.io/" width="200" height="250"> </a> <br> <span style="font-weight:bold;font-family:verdana;color:blue;font-size:14px">Regression methods (Linear, Ridge, Lasso, ElasticNet, Huber)</span> <br><br> Predict price of a house<br> Data Set: <a href="https://www.kaggle.com/harlfoxem/housesalesprediction">House Sales in King County, USA</a><br> Algorithms: Linear, Ridge, Lasso, ElasticNet, Huber (using <a href="https://scikit-learn.org/">Scikit-learn</a>)|<a href="https://github.com/ozdemirht/Data-Science/blob/master/learn/classification/ex1/example.ipynb"><img src="/images/classification-1.png" alt="https://ozdemirht.github.io/" width="200" height="250"></a><br><span style="font-weight:bold;font-family:verdana;color:blue;font-size:14px">DNNClassifier, LinearClassifier (using <a href="https://www.tensorflow.org/">TensorFlow</a>)</span> <br><br>Classifiy wine quality based on given measurements<br>Data set: <a href="https://archive.ics.uci.edu/ml/datasets/wine+quality">Wine Quality Dataset</a><br>Classification Algorithm: DNNClassifier (multi-layer neural network)<br>Compare performans of classification algorithms|
| Visualization (Exploratory Data Analysis) | |
| Matplotlib | Seaborn |
| <a href="https://github.com/ozdemirht/Data-Science/tree/master/matplotlib/ex1/example.ipynb"><img src="/images/matplotlib-1.png" alt="https://ozdemirht.github.io/" width="200" height="250"></a><br> <span style="font-weight:bold;font-family:verdana;color:blue;font-size:14px"><a href="https://matplotlib.org/contents.html">Matplotlib</a> Example </span> | <a href="https://github.com/ozdemirht/Data-Science/blob/master/seaborn/ex1/example.ipynb"><img src="/images/seaborn.png" alt="https://ozdemirht.github.io/" width="200" height="250"></a><br> <span style="font-weight:bold;font-family:verdana;color:blue;font-size:14px"><a href="https://seaborn.pydata.org/">Seaborn</a> Example</span> |



﻿# Data Science and Machine Learning Notebooks 

* Visualization
 for Exploratory Data Analysis  
  * [Matplotlib notebook](https://github.com/ozdemirht/Data-Science/tree/master/matplotlib/ex1/example.ipynb)
 (scatter plot, histogram/kde, box plot)   
  * [Seaborn notebook](https://github.com/ozdemirht/Data-Science/tree/master/seaborn/ex1/example.ipynb)   
 
  * Lightning - http://lightning-viz.org/
  * Bokeh - https://bokeh.pydata.org/
* Data cleaning
  * Notebook
* Dimension reduction
  * [Notebook](./learn/pca/ex1/example.ipynb) for PCA, LogisticRegression, DecisionTree, RandomForest (from [Scikit-learn](https://scikit-learn.org/) )
    * <i>Data Set</i>: [Wine Quality](https://archive.ics.uci.edu/ml/datasets/wine+quality)
    * <i>Problem</i>: Predict quality of wine. 
    * <i>Approach</i>: Used classification methods (Logistic Regression, Decision Tree, Random Forest) after applying PCA.
  * [Notebook](./learn/pca/ex2/example.ipynb) for PCA, LDA, Autoencoder (from [Scikit-learn](https://scikit-learn.org/) )
    * <i>Data Set</i>: [Human Activity Recognition](https://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones)
    * <i>Problem</i>: Predict activity from observations. 
    * <i>Approach</i>: 
* Clustering

  * [Notebook](./learn/clustering/ex1/example.ipynb) for K-Means (from [Scikit-learn](https://scikit-learn.org/) )
    * <i>Data Set</i>: [Wine Quality](https://archive.ics.uci.edu/ml/datasets/wine+quality)
    * <i>Problem</i>: Cluster data for two quality categories. 
    * <i>Approach</i>: Used K means algorithm to cluster.  
* Regression
 
  * [Notebook](./learn/regression/ex1/example.ipynb) for LinearRegression, Ridge, Lasso, ElasticNet, ElasticNet CrossValidation, HuberRegressor (from [Scikit-learn](https://scikit-learn.org/) )
    * <i>Data Set</i>: [House Sales in King County, USA](https://www.kaggle.com/harlfoxem/housesalesprediction)
    * <i>Problem</i>: Predict price of a house. 
    * <i>Approach</i>: Used regression methods (Linear, Ridge, Lasso, ElasticNet, Huber). 
  * TensorFlow.LinearRegressor
  * TensorFlow.DNNRegressor
* Classification
 
  * [Notebook](./learn/classification/ex1/example.ipynb) for DNNClassifier, LinearClassifier (from [TensorFlow](https://www.tensorflow.org/))
    * <i>Data Set</i>: [Wine Quality](https://archive.ics.uci.edu/ml/datasets/wine+quality)
    * <i>Problem</i>: Predict quality of wine. 
    * <i>Approach</i>: Used classification methods (DNNClassifier, LinearClassifier).
  * SVM
* Text Analysis and NLP
  * Word2Vec
* Reinforcement Learning



<div markdown="0"> 
  <table style="border: none;margin: 0px auto;vertical-align:bottom;background-color:#f3f2f7">
<tr>  
 <th>Dimension Reduction</th> <th>Clustering</th>
</tr>
<tr>
 <td style="white-space:wrap;text-align:center;vertical-align:bottom">
  <a href="https://github.com/ozdemirht/Data-Science/blob/master/learn/pca/ex1/example.ipynb">
   <img src="/images/pca-1.png" alt="https://ozdemirht.github.io/" width="200" height="250">
  </a>
  <br> <span style="font-weight:bold;font-family:verdana;color:blue;font-size:14px">Classification methods (Logistic Regression, Decision Tree, Random Forest) after applying PCA</span> <br>
   <ul>
     <li> wine quality classification</li>
     <li> Data Set: <a href="https://archive.ics.uci.edu/ml/datasets/wine+quality">Wine Quality Dataset</a> </li>
     <li> Applied <a href="https://en.wikipedia.org/wiki/Principal_component_analysis">PCA</a> for dimension reduction on input vectors </li>
     <li> Algorithms: Logistic Regression, Decision Tree, Random Forest (using <a href="https://scikit-learn.org/">Scikit-learn</a> )</li>
     <li> Compared performance of algorithms </li>
   </ul>
 </td>
 <td style="white-space:wrap;text-align:center;vertical-align:bottom">
  <a href="https://github.com/ozdemirht/Data-Science/blob/master/learn/clustering/ex1/example.ipynb">
   <img src="/images/kmeans-1.png" alt="https://ozdemirht.github.io/" width="200" height="250">
  </a>
  <br> <span style="font-weight:bold;font-family:verdana;color:blue;font-size:14px">K-Means (using <a href="https://scikit-learn.org/">Scikit-learn</a> )</span>
   <ul>
     <li> Discover classes in a given data set</li>
     <li> Data Set: <a href="https://archive.ics.uci.edu/ml/datasets/wine+quality">Wine Quality Dataset</a> </li>
     <li> Algorithm: K-Means clustering (using <a href="https://scikit-learn.org/">Scikit-learn</a>)</li>
   </ul>
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
  <br> <span style="font-weight:bold;font-family:verdana;color:blue;font-size:14px">Regression methods (Linear, Ridge, Lasso, ElasticNet, Huber)</span> <br>
   <ul>
     <li> Predict price of a house
     <li> Data Set: <a href="https://www.kaggle.com/harlfoxem/housesalesprediction">House Sales in King County, USA</a> </li>
     <li> Algorithms: Linear, Ridge, Lasso, ElasticNet, Huber (using <a href="https://scikit-learn.org/">Scikit-learn</a>) </li>
   </ul>
 </td>
 <td style="white-space:wrap;text-align:center;vertical-align:bottom">
  <a href="https://github.com/ozdemirht/Data-Science/blob/master/learn/classification/ex1/example.ipynb">
   <img src="/images/classification-1.png" alt="https://ozdemirht.github.io/" width="200" height="250">
  </a>
  <br><span style="font-weight:bold;font-family:verdana;color:blue;font-size:14px">DNNClassifier, LinearClassifier (using <a href="https://www.tensorflow.org/">TensorFlow</a>)</span> <br>
   <ul>
     <li>Classifiy wine quality based on given measurements </li>
     <li>Data set: <a href="https://archive.ics.uci.edu/ml/datasets/wine+quality">Wine Quality Dataset</a>  </li>
     <li>Classification Algorithm: DNNClassifier (multi-layer neural network)</li>
     <li>Compare performans of classification algorithms</li>
   </ul>  
 </td>
</tr>
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
<td style="white-space:wrap;text-align:center;vertical-align:bottom"> Convolutional-NN
</td>
<td style="white-space:wrap;text-align:center;vertical-align:bottom">Recurrent-NN
</td>
</tr>
<tr>
<td style="white-space:wrap;text-align:center;vertical-align:bottom"> Autoencoders
</td>
<td style="white-space:wrap;text-align:center;vertical-align:bottom"> Transformers
</td>
</tr>
<tr>
<td style="white-space:wrap;text-align:center;vertical-align:bottom"> Reinforcement learning
</td>  
<td style="white-space:wrap;text-align:center;vertical-align:bottom">
</td>
</tr>
</table>
</div>
