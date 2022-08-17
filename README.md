# Customer-Segmentation-using-Kmeans-clustering

Dataset Source: https://www.kaggle.com/datasets/arjunbhasin2013/ccdata

**K-Means Algorithm**
K-Means algorithm falls under the unsupervised learning category of machine learning. In K-means, there are clusters formed based of the close proximity of the centroids. 

This means that, when there are n number of clusters defined, there are same n number of centroids in the dataset, and the points closest to those centroids forms the n clusters. Clustering is simply grouping close distance points together and identifying the features that made them fall into that particular cluster. The different distance metrics available are Euclidean, Manhattan, Chi-Squared, chebyshev, however, the most common method used is Euclidean distance.

**Principal Component Analysis**
Eliminating the unwanted features can be of great help when buiding a model and visualizing them. The model with less features can be predicted or grouped together easily. In our model, we took 95% variance of the features and fit it in only 5 components, drastically reducing from the total of 18 columns we had before.
