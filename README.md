# Cryptocurrencies

## Analysis Overview

The goal of this project is to utilise unsupervised machine learning to evaluate a cryptocurrency database and generate a report that categorises traded cryptocurrencies into groups based on their characteristics.
An investment bank might utilise this classification report to propose a new bitcoin investment portfolio to its clients.
For the analysis, we employ the following methods:

- Database preprocessing
- Using Principal Component Analysis to reduce the data dimension
- Using K-Means to cluster cryptocurrency
- Using 2D and 3D scatter plots to visualise classification findings

## Results

Following the preprocessing and cleaning phase we have a total of 532 tradable cryptocurrencies.

### Clustering Cryptocurrencies using K-Means - Elbow Curve

- We don't know what would be the output of the analysis so we are using unsupervised machine learning to identify clusters of the cryptocurrencies.
- We produced the elbow curve below using the K-Means method iterating on k values from 1 to 10.
- The best k value appears to be 4 so we would conclude on an output of 4 clusters to categorize the crytocurrencies.

![image](https://user-images.githubusercontent.com/82549869/131017963-64f81280-14e8-4c52-ac89-37b74c273634.png)

### Visualizing Cryptocurrencies Results

#### 3D-Scatter plot with clusters

![image](https://user-images.githubusercontent.com/82549869/131020542-b60e4838-e034-4ccd-a2e8-2cd0634972e1.png)

#### Tradable Cryptocurrencies Table

![image](https://user-images.githubusercontent.com/82549869/131020918-b1141d53-d62e-412a-8bce-31a653646905.png)

#### 2D-Scatter plot with TotalCoinMined vs TotalCoinSupply

![image](https://user-images.githubusercontent.com/82549869/131020997-cd7d5d09-48d6-4864-a5f1-1988e30874e8.png)

## Summary

We have identified the classification of 532 cryptocurrencies based on similarities of their features.
Particularities of each group need to be analyzed to determined their performance and potential interest for the investment bank's clients.
