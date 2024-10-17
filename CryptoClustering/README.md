## Cryptocurrency Clustering Analysis

# Overview

This project applies unsupervised machine learning techniques to classify cryptocurrencies based on their price change percentages across various timeframes. We use Principal Component Analysis (PCA) for dimensionality reduction and K-means clustering to group similar cryptocurrencies.

# Data
The dataset includes price change percentages for cryptocurrencies over the following periods:

24 hours

7 days

14 days

30 days

60 days

200 days

1 year

# Methodology

Data Preprocessing: Standardization of features
Dimensionality Reduction: PCA to reduce features to 3 principal components
Clustering: K-means algorithm applied to PCA-transformed data
Visualization: Scatter plot of cryptocurrencies in PCA space

# Key Findings

Optimal number of clusters: 4
PCA Components Interpretation:

PC1: Long-term vs. short-term price changes
PC2: Medium-term price trends
PC3: Weekly price dynamics

# Tools Used

Python

Pandas

Scikit-learn

Matplotlib


