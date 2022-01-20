# Financial Consultancy

Unsupervised machine learning models to cluster cryptocurrency data.

## Description

This repository is designed to identify clusters in cryptocurrency data using unsupervised machine learning models. Information for each cryptocurrency in the dataset includes algorithm type, trading status, proof type, total coins mined, and total coins in supply. The data (crypto_data.csv) is located in the "Data" directory of this repository. 

Data preparation, dimensionality reduction, and modeling is done in **CryptoDataAnalysis.ipynb**. A standard scaler is used to standardize cleaned data before dimensionality reduction with PCA (90% of explained variance preserved) and t-SNE. Cluster analysis with k-Means suggests that the data can be clustered into three groups.  

## Getting Started

### Technologies Used 

* Python
* Pandas
* SciKit-learn
* Matplotlib

### Installing

* Clone this repository to your desktop.
* Navigate to the home directory and run **CryptoDataAnalysis.ipynb** in Jupyter Notebook.

### Data Sources

Crypto Coin Comparison Ltd. (2020) Coin market capitalization lists of crypto currencies and prices. Retrieved from [https://www.cryptocompare.com/coins/list/all/USD/1](https://www.cryptocompare.com/coins/list/all/USD/1)


## Author

Katlin Bowman, PhD

E: klbowman@ucsc.edu

[LinkedIn](https://www.linkedin.com/in/katlin-bowman/)
