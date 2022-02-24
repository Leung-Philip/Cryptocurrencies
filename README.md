# Cryptocurrencies

## Overview
ETL was used on cryptocurrency data so that it can be used in an unsupervised machined learning model.

Data dimensions were reduced using principal component analysis (PCA). We use this method to speed up the unsupervised machine learning algorithm when there is a high number of features or dimensions.

An elbow curve was created using hvPLot to determine the best value for K clusters. Then, a K-means algorithm was used to predict the K clusters for the dataset. 

Using Plotly Express and hvplot, visualizations were created for the distinct groups corresponding to the principal components that were created. Additionally, a table with all the currently tradable cryptocurrencies was created. 
