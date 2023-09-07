# Customer Segmentation, Segment Movement and Product Recommendation Analysis

## Introduction

This repository contains the code and analysis for customer segmentation and product recommendation based on a dataset. The primary goals of this project were to:

1. Segment customers into four distinct groups: Freeloaders, Dormants, New Payers, and Loyalists.
2. Create a Sankey diagram to visualize the ratio of customers who have paid or not paid in the past compared to recently.
3. Implement the Apriori algorithm for product recommendation.
4. Evaluate the impact of product recommendations on turning Freeloaders into New Payers, potentially increasing revenue.

## Customer Segmentation

### 1. Freeloaders
   - Customers who have made transactions but never paid.

### 2. Dormants
   - Existing customers who have not returned.
   - Existing customers who have returned but not paid.

### 3. New Payers
   - New customers who have made payments.
   - Existing customers who have recently made payments.

### 4. Loyalists
   - Loyal and recurring customers.

## Sankey Diagram

A Sankey diagram has been created to visualize the ratio of customers who have paid or not paid in the past compared to those who have done so recently. This diagram provides insights into customer behavior trends.

![Sankey Diagram](/images/sankey.png)

## Product Recommendation

The Apriori algorithm has been applied to generate product recommendations for customers. This algorithm analyzes customer purchase patterns to suggest relevant products. The results of product recommendations can have a significant impact on customer behavior.

## Impact Analysis

By using product recommendations, the goal is to convert Freeloaders into New Payers, potentially increasing revenue by approximately $20,000 million. Detailed analysis and results can be found in the project's code and documentation.

