# CryptoClustering

Bootcamp Module 11

In this challenge, we will use unsupervised learning to analyze cryptocurrency data by examining the effects of 24-hour and 7-day price changes. Begin by loading the crypto_market_data.csv file into a DataFrame, then review summary statistics and visualize the data. Normalize the data using StandardScaler() and set the "coin_id" as the index for the scaled DataFrame. Determine the optimal number of clusters (k) for K-means clustering using the elbow method with k values from 1 to 11. Cluster the cryptocurrencies with the best k value, then visualize the results with scatter plots using hvPlot. Next, apply Principal Component Analysis (PCA) to reduce the features to three principal components, assess the explained variance, and repeat the elbow method on the PCA data to find the best k value. Finally, compare clustering results between the original and PCA-reduced data to understand the impact of feature reduction.
