# CryptoClustering

CryptoClustering
CryptoClustering is a Python project that explores the clustering of cryptocurrencies based on their price change percentages. This project uses unsupervised learning techniques, specifically K-means clustering, to group cryptocurrencies into distinct clusters.

Overview
The goal of CryptoClustering is to analyze the price change behaviors of cryptocurrencies over a given time period (e.g., 24 hours and 7 days) and identify patterns or similarities among them. By clustering cryptocurrencies based on their price change percentages, we aim to uncover underlying structures within the cryptocurrency market.

Features
Load cryptocurrency market data from a CSV file.
Preprocess and normalize the data using StandardScaler.
Perform clustering using K-means algorithm.
Visualize clustering results using scatter plots.
Utilize Principal Component Analysis (PCA) for dimensionality reduction.
Setup
Clone the repository to your local machine.
Install the required dependencies by running pip install -r requirements.txt.
Run the Jupyter notebook Crypto_Clustering.ipynb to execute the analysis.
Usage
Load the cryptocurrency market data into the notebook.
Preprocess the data by normalizing it using StandardScaler.
Determine the optimal number of clusters using the Elbow method.
Perform K-means clustering on the original data.
Visualize clustering results using scatter plots.
Apply PCA to reduce dimensionality of the data.
Determine the optimal number of clusters using the Elbow method on PCA-transformed data.
Perform K-means clustering on the PCA-transformed data.
Visualize clustering results for PCA-transformed data.
Analyze and interpret the clustering results.
Contributing
