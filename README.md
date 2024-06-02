# 🌟 Predicting Customer Ratings for Amazon Beauty Products 🌟
Welcome to the "Predicting Customer Ratings for Amazon Beauty Products" project! This repository contains a Jupyter Notebook that walks through building a recommendation system to predict customer ratings for Amazon beauty products.

### 📂 Project Overview
This project involves several steps, including data preprocessing, exploratory data analysis, building a recommendation model, and generating recommendations. The dataset used is a matrix of user IDs, product IDs, and corresponding ratings.


### 📋 Table of Contents
* Dataset
* Project Steps
    * Step 1: Download the Dataset
    * Step 2: Import Required Libraries
    * Step 3: Load the Dataset
    * Step 4: Drop Irrelevant Columns
    * Step 5: Data Visualization
    * Step 6: Building the Utility Matrix
    * Step 7: Transposing the Matrix
    * Step 8: Decomposing the Matrix
    * Step 9: Generating the Correlation Matrix
    * Step 10: Recommending Top Correlated Products
* Results

### 📊 Dataset
The dataset contains over 2 million customer reviews and ratings of beauty products on Amazon. It includes the following attributes:

* _**UserId**_: Unique identifier for each user.
* **_ProductId:_** Unique identifier for each product.
* _**Rating:**_ Rating given by the user to the product.
* _**Timestamp:**_ Time of the rating.


### 🚀 Project Steps
_**Step 1:**_ Download the Dataset
Download the dataset from Kaggle and load it into your workspace.

_**Step 2:**_ Import Required Libraries
Import the necessary libraries for data manipulation, visualization, and model building.

_**Step 3:**_ Load the Dataset
Load the dataset into a pandas data frame.

_**Step 4:**_ Drop Irrelevant Columns
Drop columns that are not required for the analysis.

_**Step 5:**_ Data Visualization
Visualize the distribution of ratings and other relevant data points to understand the dataset better.

_**Step 6:**_ Building the Utility Matrix
Create a user-item matrix where rows represent users, columns represent products, and the values are the ratings.

_**Step 7:**_ Transposing the Matrix
Transpose the matrix to switch rows and columns for easier processing.

_**Step 8:**_ Decomposing the Matrix
Use Truncated Singular Value Decomposition (SVD) to decompose the matrix.

_**Step 9:**_ Generating the Correlation Matrix
Generate a correlation matrix to find the similarity between different products.

_**Step 10:**_ Recommending Top Correlated Products
Recommend the top correlated products for a given product based on the correlation matrix.

### 🎯 Results
The model provides a list of recommended products based on their correlation with a specified product. For instance, for product _**B00004TMFE**_, the top recommended products are:

* B000052WYD
* B00012NI7E
* B00013TQRE
* B0001TQ9WI
* B00027DMLK


Feel free to reach out if you have any questions or suggestions. Happy coding! 🎉
