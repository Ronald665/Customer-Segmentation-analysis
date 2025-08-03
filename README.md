# Customer Personality Analysis – Clustering for Segmentation & Insight

## Overview

This project focuses on customer segmentation through unsupervised learning. Using a detailed marketing dataset, we apply clustering techniques to uncover customer behavior patterns. The resulting insights help businesses tailor products, promotions, and strategies to different customer types.

## Objective

Perform customer segmentation using clustering (K-Means) to identify distinct customer groups and gain insights into their preferences, spending behaviors, and engagement.

## Dataset Description

The dataset includes demographic, transactional, and behavioral attributes:

### People

ID: Unique customer ID

Year_Birth: Birth year

Education, Marital_Status

Income: Yearly income

Kidhome, Teenhome: Number of kids/teens

Dt_Customer: Enrollment date

Recency: Days since last purchase

Complain: Complaint history

### Products (Spending in Last 2 Years)

MntWines, MntFruits, MntMeatProducts, MntFishProducts, MntSweetProducts, MntGoldProds

### Promotions

NumDealsPurchases, AcceptedCmp1-5, Response

### Purchase Channels

NumWebPurchases, NumCatalogPurchases, NumStorePurchases, NumWebVisitsMonth

## Approach

Data Cleaning & Feature Engineering: Missing values, encoding, new features

Dimensionality Reduction: PCA for visualization and improved clustering

Clustering: K-Means with optimal k selected via Elbow and Silhouette Score


## Key Customer Segments

Cluster 0 – Luxury Spenders: Wealthy professionals, highest spenders

Cluster 1 – Budget Families: Low-income, large households, low spend

Cluster 2 – Loyal Shoppers: Mid-income, engaged, consistent buyers

Cluster 3 – Low-Spending Indivuals: Young, low income, minimal engagement
