K-Means Clustering Implementation

This project demonstrates the implementation of the K-Means Clustering
algorithm using Python and Scikit-learn. The notebook explores how to
determine the optimal number of clusters using the Elbow Method and
Silhouette Score.

Project Overview

Clustering is an unsupervised machine learning technique used to
group similar data points together.

In this project: - A dataset is loaded and visualized - K-Means
clustering is applied - Within-Cluster Sum of Squares (WCSS) is
calculated - The Elbow Method is used to find the optimal number of
clusters - Silhouette Score is used to evaluate cluster quality -
The final clustering model is trained using the optimal value of k

Technologies Used

-   Python
-   NumPy
-   Pandas
-   Matplotlib
-   Scikit-learn

Dataset

The dataset `cluster2.csv` contains two numerical features:

-   X coordinate
-   Y coordinate

These values represent data points that will be grouped into clusters.

Steps Performed

1.  Import necessary libraries
2.  Load dataset using Pandas
3.  Visualize the dataset
4.  Apply K-Means clustering
5.  Calculate WCSS values for k = 1 to 10
6.  Plot the Elbow Method graph
7.  Calculate Silhouette Scores
8.  Determine the optimal number of clusters
9.  Train the final K-Means model
10. Identify the cluster centroids

Elbow Method

The Elbow Method helps determine the best value of k by
plotting:

WCSS vs Number of Clusters

The optimal number of clusters is identified where the curve forms an
elbow point.

Silhouette Score

The Silhouette Score measures how well each data point fits within
its cluster.

Score range:

-   +1 → well clustered
-   0 → overlapping clusters
-   -1 → incorrect clustering

Final Result

Based on the evaluation methods, the optimal number of clusters was
determined to be:

k = 3

The final model was trained using this value, and the cluster
centroids were calculated.

