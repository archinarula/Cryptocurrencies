# Written Analysis of the UnSupervised Machine Learning and Cryptocurrency challenge Module 18

## Overview of Analysis
This project purpose is to use unsupervised machine learning to analyze the data of Crypto currencies and create a report on traded cyrptocurrencies classified by groups based on their features. To following approach was used:

- Preprocessing the database
- Reducing data dimensionality using PCA (Principal Conmponent Analysis)
- Clustering using K-Means
- and finally, visualizing the classifications with 2D and 3D scatter plots


Data Source: 
![crypto_data.csv] (https://github.com/archinarula/Cryptocurrencies/blob/main/crypto_data.csv)

## Deliverable: 
This challenge consists of four technical analysis deliverables and a written report to present results. 


- Deliverable 1: Preprocessing the Data for PCA
- Deliverable 2: Reducing Data Dimensions Using PCA
- Deliverable 3: Clustering Cryptocurrencies Using K-means
- Deliverable 4: Visualizing Cryptocurrencies Results
- A Written Report on the Cryptocurrencies Analysis (README.md)


## Results

The results are displayed on Jupiter notebooks links 

![crypto_clustering.ipynb](https://github.com/archinarula/Cryptocurrencies/blob/main/crypto_clustering.ipynb) 

Key findings and highlights of this analysis is:

1. We started with 1252 cryptocurrencies in the original dataset and after preprocessing and cleaning the data we landed to 532 tradable cryptocurrencies

2. We used Elbow curve method to identify clusters using the K-Means method iterating on k values from 1 to 10. The best k value appears to be 4 so we conclude that 4 clusters will be good to categorize the cryptocurrencies data

3. 3D scatter plot was obtained using the PCA algorithm to reduce the crytocurrencies dimensions to three principal components and 2D scatter plot was obtained to reduce dimensions to two principal components. Both 2D and 3D plots showed distribution and 4 clusters of cryptocurrencies. Few unique outliers were also clear.

4. Most of the cryptocurrencies are part of class #0 and #1.
BitTorrent is the only cryptocurrency in class #2. 


## Summary
Classified 532 cryptocurrencies based on similarities of their features.This report will be useful to investments bankers to discuss and propose the new cryptocurrency investment portfolio to customers.

 







 



