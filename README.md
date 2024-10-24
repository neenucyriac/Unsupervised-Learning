# Unsupervised-Learning
2.Clustering Algorithm Implementation (8 marks)

#A) KMeans Clustering (4 marks)

#Provide a brief description of how KMeans clustering works.
'''KMeans clustering is an iterative algorithm that divides a dataset into K distinct, non-overlapping subsets (clusters). The algorithm works as follows:

Initialize K centroids randomly.
Assign each data point to the nearest centroid.
Recalculate the centroids as the mean of the assigned points.
Repeat steps 2 and 3 until convergence (when assignments no longer change).'''

#Explain why KMeans clustering might be suitable for the Iris dataset.
'''KMeans is suitable for the Iris dataset because:

The dataset has well-defined groups that can be separated in a multi-dimensional space.
It allows for efficient clustering of the continuous numerical features (sepal length, sepal width, petal length, petal width).'''


#B) Hierarchical Clustering (4 marks)

#Provide a brief description of how Hierarchical clustering works.
'''Hierarchical clustering builds a tree-like structure (dendrogram) to represent the relationships between data points. 
There are two main types:

Agglomerative: Starts with each point as its own cluster and merges them based on proximity.
Divisive: Starts with one cluster and recursively splits it into smaller clusters.'''

#Explain why Hierarchical clustering might be suitable for the Iris dataset.
'''Hierarchical clustering is suitable for the Iris dataset because:

It does not require specifying the number of clusters in advance.
The dendrogram can provide insights into the data structure and the relationships between clusters.'''

