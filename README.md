# CryptoClustering

This repository contains the code needed to run the CryptoClustering challenge. All code can be found in Crypto_Clustering.ipynb. Data needed to run the code can be found in the 'Resources' folder. 
In this challenge Python and unsupervised learning are used to predict if cryptocurrencies are affected by 24-hour or 7-day price changes. 
Briefly, after data were loaded, it was explored using summary statistics and an hvplot.line. The data were then prepared using StandardScaler() and a data frame was generated. The Cryptocurrencies were clustered with K-means by using the scaled dataframe. The clusters were then optimized with Principal Component Analysis (PCA) and the best value for k was found using the PCA dataframe. The Cryptocurrencies were then clustered using K-means using the PCA dataframe. The plots generated with the original and the scaled PCA dataframes were visualized in parallel.
