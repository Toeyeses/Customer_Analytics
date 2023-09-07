# Customer Lifetime Value (CLV) Analysis

## Introduction

This repository presents a Customer Lifetime Value (CLV) analysis for Dusit International's loyalty program. Dusit International is a prominent hospitality company in Southeast Asia, operating across various business units, including Hotels & Resorts, Hospitality Education, Foods, Property Development, and Hospitality-Related Services. The aim of this analysis is to enhance the existing loyalty program by introducing a new CLV scoring feature.

## Current Loyalty Program

![Current Loyalty Program](/images/current_loyalty_program.png)

### Pain Points

The current loyalty program faces the following challenges:

1. **Loss of Opportunity**: High-tier hotels may not benefit from the current calculation of customer loyalty programs, resulting in missed revenue opportunities.

2. **Overlooking Long-Lifespan Customers**: Customers with longer lifespans might not receive the recognition they deserve within the program.

## CLV Scoring Feature

To address these pain points, a new CLV scoring feature has been introduced. The CLV score is calculated based on the following factors:

- Number of Stays
- Number of Nights
- Total Spending
- Customer Lifespan (in Years)

This enhanced scoring system allows for a more comprehensive assessment of customer value and engagement.

## New Scorecard Metrics and Hotel Tiers

![New Scorecard Metrics](/images/new_scorecard_metrics.png)

### Hotel Tiers

Hotel tiers are now determined based on the star rating of each hotel. This ensures that loyal customers receive appropriate recognition and rewards at each level of the program.

## Example Customer Profile Score

![Example Customer Profile Score](/images/example_customer_profile.png)

This example demonstrates how the CLV scoring feature can be applied to a customer profile. It provides a clear indication of the customer's value to the loyalty program.

## Summary

The Customer Lifetime Value (CLV) is calculated using the following equation:

```
CLV = Avg. Transaction Amount Per Year * Avg. Transactions Per Year * Lifespan (Years)
```

This analysis aims to enhance the Dusit International loyalty program by better recognizing and rewarding customers based on their long-term value, ultimately leading to increased revenue and customer satisfaction.

---

Feel free to explore the code and documentation in this repository for a more detailed understanding of the CLV analysis and its potential impact on Dusit International's loyalty program. If you have any questions or feedback, please don't hesitate to reach out.