# CryptoClustering

## Overview

The Crypto Clustering project aims to predict if cryptocurrencies are affected by 24-hour or 7-day price changes using unsupervised learning techniques, specifically K-means clustering. Additionally, the project explores the impact of dimensionality reduction using Principal Component Analysis (PCA) on clustering

## Steps

Load and preprocess the data.
Scale the data using StandardScaler.
Find the best value for k using the elbow method.
Cluster cryptocurrencies with K-means using the original scaled data.
Perform PCA to reduce the features to three principal components.
Find the best value for k using the PCA data.
Cluster cryptocurrencies with K-means using the PCA data.
Visualize and compare the results using hvPlot.

## Output

Elbow Curve for Original Data

![Elbow1](https://github.com/lintubaby5/CryptoClustering/blob/main/Images/elbow_orginal_data.png)

Elbow Curve for PCA Data

![Elbow2](https://github.com/lintubaby5/CryptoClustering/blob/main/Images/elbow_pca.png)

Scatter plot of Clusters based on original data

![Scatter1](https://github.com/lintubaby5/CryptoClustering/blob/main/Images/cluster_prediction_orginal_data.png)

Scatter plot of CLusters based on PCA Data

![Scatter2](https://github.com/lintubaby5/CryptoClustering/blob/main/Images/cluster_prediction_pca.png)

## Conclusion

Both the models (original and PCA) is best described using 4 clusters. Also in the elbow curve for PCA data the inertia is a little bit steeper than the one for original data.
These three principal components explained 90% of the variance of the cryptocurrencies' returns.

# Tools

Python
Pandas
Scikit-Learn
HvPlot
