# Iris Dataset Clustering

This project demonstrates the application of clustering techniques on the famous Iris dataset using two popular methods: KMeans and Hierarchical Clustering. The objective is to partition the dataset into clusters without using the species labels and to visualize the resulting clusters.

## Dataset

The dataset used is the Iris dataset, which is available from the sklearn library. It contains 150 samples of iris flowers, with 4 features each: sepal length, sepal width, petal length, and petal width.

## Clustering Methods
### 1. KMeans Clustering

KMeans is a partition-based clustering algorithm that aims to divide the dataset into K clusters. It initializes K cluster centroids, assigns each point to the nearest centroid, and iteratively refines the centroids based on the mean of the points in each cluster.

#### Why KMeans?
KMeans is suitable for the Iris dataset due to the well-defined clusters that correspond to different species of flowers.

### 2. Hierarchical Clustering

Hierarchical clustering builds a hierarchy of clusters using either a bottom-up (agglomerative) or top-down (divisive) approach. The agglomerative method starts with each point as a separate cluster and merges them based on their similarity.

#### Why Hierarchical Clustering?
Hierarchical clustering provides a dendrogram, which helps visualize the hierarchical structure and relationships between clusters in the Iris dataset.

## Implementation

### Prerequisites
To run this project, you need to have Python installed along with the following libraries:

*pandas*

*numpy*

*scikit-learn*

*matplotlib*

*scipy*

## Loading and Preprocessing

Load the Iris dataset from sklearn and drop the species column.

### KMeans Clustering

Apply KMeans clustering and visualize the clusters.

### Hierarchical Clustering

Apply Hierarchical clustering and visualize the clusters using a dendrogram.

### Visualizations

The project includes visualizations for the resulting clusters from both KMeans and Hierarchical Clustering.

*KMeans Clustering Visualization*

*Hierarchical Clustering Dendrogram*

*Hierarchical Clustering Visualization*

## Conclusion

This project showcases the application of KMeans and Hierarchical clustering on the Iris dataset. Both methods provide insights into the structure of the data and highlight the natural grouping of the samples.
