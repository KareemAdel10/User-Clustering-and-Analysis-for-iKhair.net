# User Clustering and Analysis for iKhair.net
## Project Overview
This project involves analyzing and segmenting users of the iKhair.net mobile app, which has over 10 million records of user profiles, transactions, and locations since its launch in 2011. The primary goal is to group users based on behavioral similarities and generate actionable insights through data analysis and visualization.

## Objectives
1. **Feature Engineering**
The table's initial features couldn't be directly used for clustering, so I generated new features to capture user behavior more effectively. These features include:
    - Total Transaction Amount per User: Sum of transaction amounts for each user.
    - Average Transaction Amount per User: Mean transaction amount per user.
    - Number of Transactions per User: Total count of transactions for each user.
    - Preferred Payment Method: Most commonly used payment method by each user.
    - Country of Most Frequent Transactions: Most common country for each user's transactions.
    - Variety in actid: Count of unique projects per user.
    - Time Since Account Creation: Average days since each user account was created.
    - Usage Count: Usage count recorded for each user.
    - Variety in orgid: Number of unique organizations interacted with by each user.
Using these engineered features, I applied the K-means clustering algorithm to segment users. I visualized the clusters by reducing dimensions from 9 to 2 using PCA and then plotted a scatter plot to show centroids and data points.

2. **Dashboard Creation**:
Built an interactive dashboard in Looker Studio to visualize findings, including:
    - Date and project name filters.
    - Percentage of purchases by organization.
    - Purchase activity trends (daily and monthly).
    - Top five user activities.
    
  [View the Interactive Dashboard](https://lookerstudio.google.com/u/0/reporting/66dba730-3464-4399-9d6c-20ab520076f5/page/RuaQE)


  ![image](https://github.com/user-attachments/assets/8fb4eef0-5f85-433f-bc6e-fe515b5d207d)
