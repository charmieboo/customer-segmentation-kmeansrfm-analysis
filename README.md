# Customer Segmentation using RFM Analysis and K-Means Clustering
This project focuses on segmenting customers based on their purchasing behavior using RFM (Recency, Frequency, Monetary Value) analysis and K-Means clustering. By understanding the behavioral patterns exhibited in customer purchase history, we aim to gain insights into market performance and personalize experiences for different customer segments.

The dataset comes from Kaggle and can be found [here](https://www.kaggle.com/kyanyoga/sample-sales-data).

## Introduction
Understanding customer behavior is crucial for businesses to tailor their marketing strategies effectively. Rather than relying solely on demographic data, analyzing purchasing patterns provides deeper insights into customer preferences and tendencies. This project delves into customer segmentation using RFM analysis and K-Means clustering, enabling us to categorize customers into distinct groups based on their buying habits.

## Data Analysis
We utilized a dataset containing information about customer orders, including order details such as quantity, price, sales, and date. The dataset was cleaned and preprocessed to remove unnecessary columns and ensure data integrity.

We visualized the data using various techniques, including density plots, count plots, and bar plots, to explore trends in sales, order status, and quarterly sales distribution over the years.

## RFM Analysis
RFM analysis involves evaluating three key metrics: Recency, Frequency, and Monetary Value. We calculated these metrics for each customer to quantify their purchasing behavior and assign RFM scores. By grouping customers based on their RFM scores, we gained insights into different customer segments.

## K-Means Clustering
K-Means clustering is an unsupervised machine learning algorithm used for data clustering. We employed K-Means clustering to segment customers into distinct groups based on their RFM scores. Using the elbow method, we determined the optimal number of clusters and visualized the results using 3D scatter plots.

## Interpretation of Results
Based on the resulting groups from K-Means clustering, we interpreted the customer segments and categorized them into four distinct groups:

- Group 0: Former best customers - departing
- Group 1: Best customers - active
- Group 2: Old and random customers - inactive
- Group 3: New and random customers - new

## Marketing Strategies
We proposed tailored marketing strategies for each customer segment based on the insights gained from the analysis. These strategies aim to optimize customer engagement, retention, and conversion rates, focusing on targeted promotional efforts and personalized experiences for different customer groups.

By leveraging RFM analysis and K-Means clustering, businesses can enhance their understanding of customer behavior and refine their marketing strategies to better meet customer needs and preferences.
