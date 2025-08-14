# Customer Segmentation Using RFM and  K-means Clustering
Pdf version: You can access the pdf [here](https://drive.google.com/file/d/1gm6oWandM5hqls7Kfwi8i7vxndAZLJtd/view?usp=sharing)  
Dataset source: You can access the dataset [here](https://archive.ics.uci.edu/dataset/352/online+retail)

## Data Overview
The dataset used is the Online Retail Dataset from the UCI Machine Learning Repository, which contains over a year’s worth of transactional data (from December 2010 to December 2011) from a UK-based non-store online retailer. The company primarily sells unique all-occasion giftware, with many transactions involving wholesale customers.  

The data includes detailed records for each transaction, such as: Invoice ID, Product Code, Product Description, Quantity Purchased, Unit Price, Invoice Date, Customer ID, and Country.

## Problem Statement
1. 67.1% of customers placed more than one order.
   However, 32.9% of customers are one-time buyers. This highlights the need to better understand and retain both repeat and non-repeat customers through segmentation.

2. Average customer spending per month remains stagnant, fluctuating between £600–£770. Monthly purchase frequency per customer is consistently low, ranging only between 1.4–1.6x. This indicates that from month to month, there has been no significant improvement in customer behavior, or at least that current campaigns and treatments have not delivered satisfying results.
3. Only 27.3% of customers generate 80% of total revenue, this indicating a strong dependency on a small group. The remaining 73% contribute relatively little and may be under-engaged or untapped. Given the flat trends in average spending and frequency, this imbalance may be a sign that current strategies aren't effectively growing or activating the broader customer base.  
Reinforces the need for value-based customer segmentation, so the business can target and grow each segment differently.

## Why Need RFM Scoring?
- Not all customers contribute equally
- Traditional metrics give averages, but don’t reveal individual customer value or behavior patterns.
- To maximize revenue and retention
- This enables customized treatment: better retention, smarter promos, and more efficient resource use.

## Customer Segmentation Results & Action Plans
Following RFM Scoring and K-Means Clustering, we identified a total of 7 customer segments — 4 clusters for non-outlier data and 3 clusters for outliers — each with tailored strategies and actionable plans.

### Non-Outlier Clusters
1. Cluster 0 – Dormant Shoppers  
Customers who have not purchased in a long time, shop infrequently, and spend low amounts overall. They are inactive and require re-engagement to prevent churn.  
Action Plan: Reactivation campaigns via reminder emails, limited-time offers, and exclusive discounts to encourage a return purchase.

2. Cluster 1 – Active Low-to-Mid Spenders  
Customers who shop relatively recently and regularly, though spending remains modest. They represent consistent, steady-value customers with growth potential.  
Action Plan: Encourage higher spending through personalized product recommendations, bundle deals, and loyalty point multipliers.

3. Cluster 2 – At-Risk Buyers  
Customers with declining engagement, low purchase frequency, and reduced spending. They may be on the verge of churning.  
Action Plan: Deploy targeted win-back initiatives, such as personalized offers, satisfaction surveys, and reminders highlighting new arrivals.

4. Cluster 3 – High-Value Loyal Customers  
Frequent, high-spending, and recently active buyers who are highly valuable to the business.  
Action Plan: Retain and nurture loyalty with reward programs, early product access, and personalized services.

### Outlier Clusters
1. Cluster -1 – Big-Spend One-Time Shoppers
Recently made a high-value purchase but with very low purchase frequency; likely impulse buyers.  
Action Plan: Run reactivation campaigns with targeted reminders, time-limited discounts, and curated product suggestions.

2. Cluster -2 – Emerging High-Potential Buyers
Recent high-value purchases with moderate frequency, showing strong buying power and high engagement potential.
Action Plan: Foster repeat purchases through tiered promotions, loyalty incentives, and product education.

3. Cluster -3 – Super VIPs
Elite customers with extremely high purchase frequency, exceptionally high spend, and recent transactions. They generate disproportionate revenue.  
Action Plan: Offer VIP treatment through exclusive programs, private events, and premium benefits.

## Conclusion
1. Customer Segmentation with RFM & Clustering  
Customers were segmented into 7 actionable groups, covering both typical purchase patterns and extreme outliers.

2. Deep Behavioral Insights  
Segmentation revealed clear distinctions in recency, frequency, and monetary value, identifying customers from loyal high spenders to low-value dormant users.

3. Data-Driven Strategy Foundation  
The results enable targeted marketing, personalized retention efforts, and effective reactivation campaigns.

4. Value Preservation for Outliers  
Outliers were not discarded but analyzed separately, maintaining model accuracy while capturing high-impact customer value.




