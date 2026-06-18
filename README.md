# synent-task8-customer-segmentation-akshara_dave
# Customer Segmentation using K-Means Clustering

## Problem Statement

Businesses often serve customers with different purchasing behaviors and financial capacities. Treating all customers the same can reduce the effectiveness of marketing strategies and customer engagement efforts.

The objective of this project is to segment customers into meaningful groups based on their annual income and spending behavior using the K-Means Clustering algorithm. These customer segments can help businesses develop targeted marketing campaigns, improve customer retention, and optimize resource allocation.

## Dataset Details

### Dataset Name
Mall Customers Dataset

### Dataset Description

The dataset contains demographic and spending information for customers visiting a shopping mall.

### Features

| Column Name | Description |
|------------|-------------|
| CustomerID | Unique customer identifier |
| Gender | Gender of the customer |
| Age | Age of the customer |
| Annual Income (k$) | Customer's annual income in thousand dollars |
| Spending Score (1-100) | Score assigned based on spending behavior |

### Dataset Size

- Records: 200
- Features: 5

## Project Objectives

- Understand customer demographics and spending patterns.
- Identify distinct customer segments.
- Apply machine learning for customer grouping.
- Analyze segment characteristics.
- Generate business recommendations based on customer behavior.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Google Colab
- GitHub

## Approach

### 1. Data Understanding

- Loaded and explored the dataset.
- Reviewed data structure and feature information.
- Examined statistical summaries.

### 2. Data Cleaning

- Checked for missing values.
- Verified duplicate records.
- Confirmed data consistency.

### 3. Exploratory Data Analysis (EDA)

Performed the following analyses:

- Gender Distribution
- Age Distribution
- Annual Income Distribution
- Spending Score Distribution
- Income vs Spending Score Analysis

### 4. Feature Selection

Selected the following features for clustering:

- Annual Income (k$)
- Spending Score (1-100)

These features directly represent customer purchasing power and spending behavior.

### 5. Feature Scaling

Applied StandardScaler to standardize the selected features before clustering.

### 6. Elbow Method

Used the Elbow Method to determine the optimal number of clusters.

### 7. K-Means Clustering

Applied K-Means Clustering with 5 clusters to segment customers into distinct groups.

### 8. Cluster Analysis

Analyzed customer segments based on:

- Average Income
- Average Spending Score
- Segment Distribution

## Results

### Customer Segments Identified

#### Cluster 0 – Average Customers
- Moderate income
- Moderate spending behavior

#### Cluster 1 – Premium Customers
- High income
- High spending behavior

#### Cluster 2 – Carefree Spenders
- Lower income
- High spending behavior

#### Cluster 3 – Wealthy but Conservative Customers
- High income
- Low spending behavior

#### Cluster 4 – Budget Customers
- Low income
- Low spending behavior

## Key Findings

1. Five distinct customer groups were successfully identified.
2. Premium Customers represent the most valuable customer segment.
3. Wealthy but Conservative Customers present opportunities for targeted marketing.
4. Customer spending behavior varies significantly across income groups.
5. Customer segmentation enables personalized business strategies and improved customer engagement.

## Business Recommendations

- Offer loyalty programs and exclusive benefits to Premium Customers.
- Design targeted campaigns for Wealthy but Conservative Customers.
- Provide personalized promotions for high-spending customers.
- Develop cost-effective offers for Budget Customers.
- Continuously monitor customer behavior for improved segmentation.

## Conclusion

This project successfully applied K-Means Clustering to identify meaningful customer segments based on income and spending behavior.

The resulting customer groups provide actionable insights that can help businesses improve marketing effectiveness, increase customer satisfaction, and enhance profitability through data-driven decision-making.

## Future Scope

- Customer segmentation using additional demographic features.
- Advanced clustering techniques such as Hierarchical Clustering and DBSCAN.
- Customer Lifetime Value (CLV) prediction.
- Personalized recommendation systems.
- Interactive dashboards using Power BI or Tableau.
