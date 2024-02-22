# SOEN471-Project
We possess two Selenium automation scripts tasked with retrieving data from given websites by MECP in text files, where the data extracted will be stored in tabular format within .xlsx files. Our goal is to integrate these scripts into Crawlab, a web scraping tool, to streamline their execution and enable the storage of results in a MySQL database. 

While our future plans include designing a prediction model using this data, we currently lack a provided dataset to accurately determine the most suitable algorithm. As a result, we are analyzing the situation based on the available information, relying on our understanding of the task to guide our approach. 

## Describe dataset and main characteristics (number and type of features):
The dataset represents supplier items and their item characteristics. The color feature represents the color of the item and is of text type, the brand represents the company that manufactures the item and is of text type, the availability represents whether the item is in stock or not and is of boolean type, the packaging represents a unit of the item and is of type text, the capacity represents the number of items per unit of item and is of numerical type.

## The research questions to be addressed in the project:
How can we develop a model to predict the stock levels of an item? How can we develop a model to identify the season during which an item’s demand peaks?

## The class of models to be applied to the dataset:
The class of models that will be applied to the dataset are unsupervised learning models since we are predicting features that are not labeled.

## Algorithms:
Clustering algorithms will be used. 
1. K-means clustering will be used because the algorithm is unsupervised. K-means is efficient and easy to parallelize which fits our large dataset. However, k-means is sensitive to outliers and assumes normally distributed clusters. 
2. The DBSCAN algorithm will also be used because the algorithm is unsupervised. DBSCAN can detect outliers and the shape of the clusters and number of clusters does not need to be known prior to running the algorithm.
