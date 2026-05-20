# Lab 11 Summary

* Objective:** Segment credit card customers based on their usage behavior using K-Means Clustering to help the company design better marketing strategies.
* Dataset:** Used the `CC_GENERAL.csv` dataset containing customer behavioral variables such as balance, purchases, cash advance, and credit limit.
* Data Cleaning:** Dropped the irrelevant `CUST_ID` column and handled missing values using mean imputation.
* Feature Scaling:** Standardized the features using `StandardScaler` to ensure all variables contribute equally to the distance-based K-Means algorithm.
* Model Evaluation:** Applied the Elbow Method and Silhouette Score to determine the optimal number of clusters ($K=4$).
* Cluster Analysis & Visualization:** Analyzed the 4 customer segments (Standard, VIP, Cash Users, Inactive) and used PCA to reduce dimensions for 2D visualization.
