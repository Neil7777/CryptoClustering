# CryptoClustering

## Overview
This Python script performs analysis on cryptocurrency market data using K-Means clustering. It utilizes the scikit-learn library for K-Means clustering, PCA (Principal Component Analysis), and visualization using hvPlot. The analysis aims to cluster cryptocurrencies based on their price change percentages over different time intervals.

## File Structure
- crypto_market_data.csv: CSV file containing cryptocurrency market data.
- Crypto_Clustering.ipynb: Jupyter Notebook for data analysis and clustering.

## Instructions
1. Ensure Python 3.x and the required libraries are installed (pandas, hvplot, scikit-learn).
2. Place the crypto_market_data.csv file in the same directory as the script.
3. Run the crypto_market_data_analysis.py script.

## Description
- The script reads the market data from crypto_market_data.csv into a Pandas DataFrame.
- It preprocesses the data by scaling using StandardScaler, then performs K-Means clustering on both the original and PCA-transformed data.
- Elbow curves are plotted to determine the optimal number of clusters (k).
- Cryptocurrencies are clustered based on price change percentages over various time intervals.
- Results are visualized using scatter plots with clustered data points.

## Conclusion
- The script provides insights into cryptocurrency market trends by clustering based on price change percentages.
- It uses K-Means clustering and PCA to create more interpretable clusters.
- Results are visualized for easy interpretation of the clustering analysis.

## References
- Scikit-Learn Documentation
- hvPlot Documentation
- Pandas Documentation
