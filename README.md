DU-VIRT-AI-PT-05-2024-U-LOLC-MWTH - Module 11 Challenge (Aug 4, 2024)

# Module 11 Challenge - Unsupervised Machine Learning (Clustering)

[notebooks/Crypto_Clustering.ipynb](https://github.com/JimGile/CryptoClustering/blob/main/notebooks/Crypto_Clustering.ipynb)

## Focus

Module 11 focuses on the unsupervised machine learning concept of clustering. Clustering is the grouping of data so that every member of that group is similar in some way. Unsupervised clustering algorithms use test data to build models that categorize the relationships among data points and arrange them in clusters. For example, when you purchase an item on a website, unsupervised clustering algorithms can identify related items that people frequently purchase together.

Unsupervised clustering algorithms and concepts explored in this challenge:

* **K-Means**: A simple and efficient clustering algorithm that partitions data into (k) clusters where each cluster is represented by its mean (centroid).

  * K: Refers to the number of clusters you want to divide your data into. This is a parameter you set before running the algorithm.

  * Means: Refers to the mean of the data points in each cluster. The algorithm iteratively adjusts the cluster centroids to minimize the distance between data points and their respective cluster centroids.

* **Elbow Curve**: A method to determine the optimal value of k, or the number of clusters in a dataset.  The Elbow Curve explores a range of k values to determine the number of clusters at which the data points become tightly clustered.

* **PCA**: Principal Component Analysis - Clustering algorithms, such as K-means, often suffer from the curse of dimensionality, or too many features than can be made sense of in a single model. PCA reduces the number of factors by transforming a large set of features into a smaller one that contains MOST of the information of the original larger dataset. It does the following:

  * Looks at all the dimensions (columns) in a dataset.

  * Analyzes the weight of their contribution to the variance in the dataset.

  * Reduces the dimensions to a smaller set that still contains as much of the 
information (the maximum variance) of the original dataset as possible.

## Challenge

The challenge is to create a machine learning model that groups cryptocurrencies. The purpose is to assemble investment portfolios that are based on the profitability of those cryptocurrencies.

## Solution #1

The standard solution is in the Jupyter Notebook file [notebooks/Crypto_Clustering.ipynb](https://github.com/JimGile/CryptoClustering/blob/main/notebooks/Crypto_Clustering.ipynb).

## Solution #2

An alternate solution using custom classes is in the Jupyter Notebook file [notebooks/Crypto_Clustering_With_Classes.ipynb](https://github.com/JimGile/CryptoClustering/blob/main/notebooks/Crypto_Clustering_With_Classes.ipynb).
