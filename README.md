# Clustering Shopping Mall Customers

<img src="img/clustering pic.jpeg" alt="clustering" width="600"/>

## Project Overview
In this project, I aim to identify target customers for a shopping mall, and guide the marketing team in developing marketing strategies and promotions to target specific demographics more effectively. Customer Segmentation is one the most important applications of unsupervised learning. Using clustering techniques, companies can identify the several segments of customers allowing them to target the potential user base. In this machine learning project, I will make use of three main clustering algorithm, K-Means Clustering, DBSCAN, and Hierarchical Clustering, combined with visualizations of clusters.


## Project Structure
The main parts of this project include:
- Part 1: Comprehensive Exploratory Data Analysis and Visualizations
- Part 2: Deploying the K-Means Clustering Algorithm Using scikit-learn package
- Part 3: Investigating the DBSCAN Algorithm and Visualizing the Clusters
- Part 4: Exploring the Hierarchical Clustering, Creating Dendograms and Visualizing the Clusters


## Dataset 
The dataset is aquired from kaggle and the link is as follows:

https://www.kaggle.com/nelakurthisudheer/mall-customer-segmentation

- The dataset consists of following five features of 200 customers:

- CustomerID: Unique ID assigned to the customer

- Gender: Gender of the customer

- Age: Age of the customer
  
- Annual Income (k$): Annual Income of the customer

- Spending Score (1-100): Score assigned by the mall based on customer behavior and spending nature.



## Exploratory Data Analysis
A detailed exploratory data analysis was conducted to understand the dataset, identify patterns, and gain insights. This involved checking for missing values, analyzing the distribution of features, and visualizing relationships between features and the target variable (Churn).

<img src="img/Correlations.png" alt="churn" width="850"/>
<br>
<img src="img/Scatterplot.png" alt="churn" width="850"/>
<br>

## Predictive Modeling
Tree-based and boosting models were implemented to predict customer churn. These models included:
- Decision Trees
- Random Forests
- Gradient Boosting Machines (GBM)
- Adabooster

<br>

## Results
The performance of the models was evaluated using metrics such as accuracy, recall, and F1-score. The results showed that the boosting methods predicted customer churn better when I performed oversampling of the minority class.

<img src="img/Metrics.png" alt="churn" width="600"/>
<br>

## Conclusion
This project demonstrates the effectiveness of tree-based models combined with boosting methods in classification tasks such as the prediction of customer churn. Telecommunications companies can implement strategies to retain customers and reduce churn rates by identifying key factors contributing to churn.
<br>
<br>

## Installation
To run this project, we need to have Python installed along with the following libraries:
- Numpy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
