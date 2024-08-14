# Clustering Shopping Mall Customers

<img src="img/clustering pic.jpeg" alt="clustering" width="600"/>

<br>
  
## Project Overview
In this project, I aim to identify target customers for a shopping mall, and guide the marketing team in developing marketing strategies and promotions to target specific demographics more effectively. Customer Segmentation is one the most important applications of unsupervised learning. Using clustering techniques, companies can identify the several segments of customers allowing them to target the potential user base. In this machine learning project, I will make use of three main clustering algorithm, K-Means Clustering, DBSCAN, and Hierarchical Clustering, combined with visualizations of clusters.

<br>

## Project Structure
The main parts of this project include:
- Part 1: Comprehensive Exploratory Data Analysis and Visualizations
- Part 2: Deploying the K-Means Clustering Algorithm Using scikit-learn package
- Part 3: Investigating the DBSCAN Algorithm and Visualizing the Clusters
- Part 4: Exploring the Hierarchical Clustering, Creating Dendograms and Visualizing the Clusters

<br>

## Dataset 
The dataset is aquired from kaggle and the link is as follows:

https://www.kaggle.com/nelakurthisudheer/mall-customer-segmentation

- The dataset consists of following five features of 200 customers:

- CustomerID: Unique ID assigned to the customer

- Gender: Gender of the customer

- Age: Age of the customer
  
- Annual Income (k$): Annual Income of the customer

- Spending Score (1-100): Score assigned by the mall based on customer behavior and spending nature.

<br>

## Exploratory Data Analysis
A detailed exploratory data analysis was conducted to understand the dataset, identify patterns, and gain insights. This involved checking for missing and duplicated values, analyzing the distribution of `Annual income' and `Spending Scores` for men and women shoppers, and exploring the relationship between `Spending score and Annual Income`, and then the relationship between `Spending score and Age`:

<div style="display: flex; justify-content: space-between;">
    <img src="img/Correlation 1.png" alt="correlation 1" width="500" height="400"/>
    <img src="img/Correlation 2.png" alt="correlation 2" width="500" height="400"/>
</div>
<br>

<img src="img/Hist 1.png" alt="hist1" width="1000" height="450"/>
<br>
<img src="img/Hist 2.png" alt="hist2" width="1000" height="450"/>
<br>


## K-Means Clustering


<div style="display: flex; justify-content: space-between;">
    <img src="img/K-Means.png" alt="Kmeans" width="400" height="400"/>
    <img src="img/3D K-Means.png" alt="3DKmeans" width="600" height="400"/>
</div>

## DBSCAN


<img src="img/DBSCAN.png" alt="dbscan" width="600"/>
<br>


## Hierarchical Clustering

<br>

## Conclusion
Clustering a mall customers or more generally, any retail companies’ customers, based on their shopping behavior and characteristics can provide us with valuable insights for strategic decision-making.

By segmenting customers into distinct groups, the company can tailor marketing strategies and promotions to target specific demographics more effectively. This approach allows for per- sonalized customer experiences, enhances customer satisfaction, and drives sales by offering relevant products and services.

Additionally, understanding different customer segments helps optimize store layouts, inven- tory management, and promotional activities. Segmentation also enhances recommenda- tion systems by allowing for more accurate and personalized product suggestions based on the specific preferences and behaviors of each customer group. This targeted approach improves operational eﬀiciency and boosts profitability while providing a more engaging shopping experience.
<br>
<br>

