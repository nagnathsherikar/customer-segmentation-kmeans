# Customer Segmentation using K-Means Clustering

![Python](https://img.shields.io/badge/Python-3.10%2B-blue) ![License](https://img.shields.io/badge/License-MIT-green) ![scikit-learn](https://img.shields.io/badge/scikit--learn-1.x-F7931E)

Unsupervised learning project that segments customers into meaningful groups using K-Means clustering on income and spending behavior.

## Overview
Customer segmentation divides customers into distinct groups based on shared characteristics, helping businesses identify high-value customers, improve marketing effectiveness, and boost retention.

## Objective
- Analyze customer purchasing behavior
- Segment customers into meaningful groups via clustering
- Identify high-value customers
- Support targeted marketing strategy design

## Method
1. Feature scaling with StandardScaler
2. Optimal cluster count via the Elbow Method
3. K-Means clustering on annual income and spending score
4. Visualization of resulting segments

## Business Insights
Customers are grouped into four segments:
- **High Income / High Spending** → Premium customers
- **High Income / Low Spending** → Potential customers
- **Low Income / High Spending** → Impulsive buyers
- **Low Income / Low Spending** → Low engagement group

## Tech Stack
- Python, Pandas, NumPy
- scikit-learn (KMeans, StandardScaler)
- Matplotlib, Seaborn

## Conclusion
K-Means clustering with feature scaling successfully segmented customers into four actionable groups, demonstrating practical use of unsupervised learning in business analytics.
