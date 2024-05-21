# PRODIGY_ML_02
#### Project Overview
The Mall Customer Clustering project aims to analyze and segment mall customers based on their spending behaviors and income levels using unsupervised machine learning techniques. By clustering customers, we can gain valuable insights into different customer segments, which can help in tailoring marketing strategies and improving customer satisfaction.

### Key Features
Data Analysis: Understanding the distribution and characteristics of the data.
Customer Segmentation: Clustering customers into distinct groups based on income and spending score.
Insights Generation: Deriving actionable insights such as low income high spending, low income low spending, high income low spending, and high income high spending customers.
### Data
The dataset used for this project contains the following features:

- CustomerID: Unique identifier for each customer.
- Gender: Gender of the customer.
- Age: Age of the customer.
- Annual Income (k$): Annual income of the customer in thousands of dollars.
- Spending Score (1-100): Score assigned by the mall based on customer behavior and spending nature.
### Data Exploration:

- Load the dataset.
- Perform exploratory data analysis (EDA) to understand data distribution and relationships.
- Visualize the data using plots like histograms, box plots, and scatter plots.
- Data Preprocessing:

- Handle missing values if any.
- Standardize the features for better clustering performance.
### Clustering:

- Use K-Means clustering algorithm to segment customers.
- Determine the optimal number of clusters using the elbow method.
- Fit the K-Means model and predict the clusters.
### Insights and Visualization:
Visualize the clusters using scatter plots.
- Interpret the clusters to derive insights:
- Cluster 1: Low Income, High Spending Score
- Cluster 2: Low Income, Low Spending Score
- Cluster 3: High Income, Low Spending Score
- Cluster 4: High Income, High Spending Score
Provide actionable recommendations based on the insights.
### Results
##### The clustering results provide a clear segmentation of customers based on their income and spending score. The identified clusters are as follows:

- Cluster 1 (Low Income, High Spending Score): Customers who might benefit from loyalty programs to sustain their spending.
- Cluster 2 (Low Income, Low Spending Score): Customers who may need targeted promotions to increase their spending.
- Cluster 3 (High Income, Low Spending Score): Customers who could be encouraged to spend more through exclusive offers.
- Cluster 4 (High Income, High Spending Score): Premium customers who should receive personalized services to enhance their shopping experience.
#### Conclusion
This project demonstrates how unsupervised learning techniques like K-Means clustering can be used to gain deep insights into customer behavior. These insights can help businesses tailor their marketing strategies and improve customer engagement.
