# Projects

## Nitish Bahadur
*Data Science PhD Student*

### Non-linear dimenionality reduction techniques in Finance

<img src="images/euclidean_60.PNG" height="175" width="400" align="right"/>

Financial markets are high-dimensional, complex, and constantly changing.  Under stressed market conditions the
changes are amplified.  Financial market can be represented by an underlying manifold in low-dimension that captures
the inherent characteristics of the high-dimensional data.  Using Russell 3000 constituents and both geodesic and
informational geometric schemes, we determine the temporal dimensionality of US market.  Further, we use rate of
change in US market dimensionality over 30 years to detect early warning system. Additionally, using intra-day prices
we zoom into temporal dimensionality around large market movements to detect early perturbation in financial system.
We not only study the benefit of using non-linear techniques such as Isomap, over linear technique such as PCA or
Multidimensional Scaling but also compare and contrast the use of geodesic distance and informational geometric distances.

#### Publications
  * [Bahardur Paper 1](papers/bahadur_Paper1.pdf)


## Lauren Baker
*Industrial Mathematics MS Professional Project Student*

<img src="images/lauren.jpg" height="75" align="left"/>

### Compressive Sensing on Carbon Nanotube Sheet Quality Control Data

<img src="images/lauren_example.png" height="175" width="400"align="right"/>

The goal of this project is to apply compressive sensing techniques to measurements provided by Nanocomp Inc.,
a company producing carbon nanotube products. This project is concerned with the thickness and uniformity of
carbon nanotube sheets. Taking advantage of the sparsity of this data when transformed from the spatial to the
Fourier domain, research will determine if this property can be used to generate accurate higher-resolution data
on these sheets. This will ultimately allow Nanocomp to measure the effects of changes in their production process
on sheet quality.


## Melanie Jutras
*Data Science MS-Thesis Student*

<img src="images/jutras.jpg" height="75" align="left"/>

### Robust Principal Component Analysis <br>for Anomaly Detection in Cyber Network Data

<img src="images/jutrasMatrix.JPG" height="175" width="400"align="right"/>

The goal of this research is to utilize Robust Principal Component Analysis (RPCA) for the purpose of anomaly
detection in DNS network packet data. Computer network traffic meets all of the criteria for Big Data. When
dealing with high dimensional data, Principal Component Analysis (PCA) is a common technique used for dimensionality
reduction. Because traditional PCA is known to be sensitive to outliers, a robust version of PCA called RPCA is used.
Through the use of a tuning parameter, RPCA can be used to separate the original data into two parts: regular network
data and anomalous network data. This data science technique allows for tuning a model utilizing a very small amount
of training data.  The method described here is useful for cybersecurity because these types of problems are largely
unsupervised and often involve high dimensional network data with sparse anomalies.

#### Publications
  * [Paper 1](paper/jutras_Paper1Title.pdf)
  
  
## Kelum Gajamannage
*Mathematial Sciences Postdoctoral Scholar*

<img src="images\kdgajamannage.jpg" height="120" align="left"/>

### Manifold Learning and Dimensionality Reduction

<img src="images\smoothingGeodesic.png" height="200" align="right"/>

My research is mainly focused on developing robust Nonlinear Dimensionality Reduction (NDR) algorithms to embed
data accurately. Specifically, I am researching on extensions of the classic Isomap method by using smoothing
splines those are robust even when the data is sparse and contaminated with noise. Herein, we can fit geodesics
in Isomap by smoothing splines with a specific smoothing parameter and then the distances on the manifold are
approximated as the lengths of these splines. The smoothing spline scheme is capable of eliminating issues with
noise and scarcity and assures a faithful embedding. We can also utilize smoothing splines for NDR while preserving
the geometry of the higher dimensional data. For that, we first make higher dimensional slices of the data in *n*
orthogonal directions and then fit data in each slice by a cubic smoothing spline. All the cubic smoothing splines
represent a grid structure that we use as the <i>n</i> dimensional coordinate system to measure the distances on
the manifold. I am also interested of generalizing Isomap to the case where both geodesics and smoothing splines
are not good approximations of long manifold distances. In such a case, one can attempt to treat the long manifold
distances as unknown, and employ matrix completion techniques on distance matrices (<i>D</i>), where some entries
are not observed, to recover the distance matrix such that <i> D = S + L </i>, where <i>S</i> is a sparse matrix
and <i>L</i> is a low rank matrix.

#### Publications
  * [Paper 1](papers\gajamannage_papers.pdf)


## Wenjing Li
*Mathematical Department PhD Student*

<img src="images\Wenjing_Li.png" height="75" align="left"/>

### Large Scale Ensemble Learning

<img src="images\ensemble_learning.png" height="250" width="250"align="right"/>

Ensemble learning is a very important technic in machine learning, and it is also widely used in industrial field
because of the good performance on predictions and classifications. However, the reason why it works so good is
rarely understood. This project aims to figure out the mysterious parts of ensemble learning and even develop some
theorems that support ensemble learning. Generally speaking, ensemble learning is a process by which multiple models,
such as classifiers or experts, are strategically generated and combined to produce a better algorithm. It is
primarily used to improve the classification or prediction performance of a model, or to reduce the risk of selecting
a poor model. Therefore, there are two major focuses of ensemble learning: the first one is the process of model
generation and selection, and the other one is the model combining strategy.

#### Publications

* [Paper 1](papers\Wenjing_Paper1Title.pdf)

