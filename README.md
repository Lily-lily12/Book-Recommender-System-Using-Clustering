# Recommender-System-Using-Clustering
Clustering is a from of unsupervised machine learning. In a given raw dataset, clusters are formed by initializing centriods, refroming of clusters, re assigning of centroids by finding out the centre of mass of the initial clusters.This methods however falls prey to the random initialization trap which means that final outcome may vary based on the initially assigned clusters. To avoid this we use the kmeans++ method to initialize the centroids.The goal of k means++ method to spread out the initial centroid by assigning the first centroid randomly then selecting the rest of the centroids based on the maximum squared distance. The idea is to push the centroids as far as possible from one another.

There are two types of clustering algorithms: K means Clustering and Hierarchial clustering 

In this project, I will use both the algorithms and draw differences and similarities between them.
