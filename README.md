# Table of Contents
 - [Executive Summary](#executive-summary)
 - [Key Findings](#key-findings)
 - [Introduction](#introduction)
 - [Dataset Overview](#dataset-overview)
 - [Methodology](#methodology)
 - [Results](#results)
   - [Tree Diagram](#tree-diagram)
 - [Insights and Recommendations](#insights-and-recommendations)
 - [Dashboard](#dashboard)
   - [Tableau Dashboard](#tableau-dashboard)

# Executive Summary

This project aimed to create a machine learning classification model to predict customer churn for a bank, conduct exploratory data analysis (EDA) to uncover churn-related insights, and develop an interactive dashboard for stakeholders to explore customer data. The final Random Forest model achieved an accuracy of 86.7% on the validation set, and the Tableau dashboard enables stakeholders to visualize customer demographics, activity levels, and churn behaviors.

<img width="468" alt="Screenshot 2024-08-17 at 00 05 54" src="https://github.com/user-attachments/assets/3247ab75-dcff-4eaf-b7fe-06d2bd39ff16">

# Key Findings
- **Churn Insights:**
   - High-risk customers tend to be older, less active, have fewer products, lower balances, and lower salaries.
- **Model Performance:**
   - The Random Forest model achieved the best results with 86.7% validation accuracy and an overall model score of 0.858.
- **Actionable Strategies:**
   - Engage inactive members with promotions or tailored offerings.
   - Upsell products to customers with fewer products.
   - Build trust and loyalty with older customers.

# Introduction

The goal of this project was to build a machine learning model to predict customer churn and provide stakeholders with tools to understand and address churn-related behaviors. This included feature importance analysis, exploratory data analysis (EDA), and the creation of an interactive Tableau dashboard.

# Dataset Overview
- Source: Customer Churn Dataset
- Size: 10,000 entries, 14 columns.
- Memory Usage: 1.1+ MB.
- Features: Include demographics, activity levels, product engagement, and balances.

# Methodology
**Data Preparation:**
- Cleaned dataset and performed feature engineering.
- Identified key features affecting churn through EDA and feature importance analysis.

**Model Selection:**
- **Evaluated several machine learning models:**
   - Logistic Regression
   - Nearest Neighbors
   - Support Vectors
   - Decision Tree
   - **Random Forest (Final Model)**
   - AdaBoost
   - Gradient Boosting
   - Naive Bayes
   - Quadratic DA
   - Neural Network
   - Selected Random Forest for its high performance.

**Visualization:**
   - Built a Tableau dashboard to present key insights and facilitate stakeholder exploration.

# Results

| Metric | Value |
| --- | --- |
| Best Score Achieved | 0.858 |
| Accuracy on Training Set | 0.868 |
| Accuracy on Validation Set | 0.867 |

| 1549 | 46 |
| --- | --- |
| 221 | 184 |

## [Tree Diagram](https://github.com/jasonldoyle/Bank-Churn-Model/blob/main/EDA/tree_visualization.pdf)

# Insights and Recommendations
- **High-Risk Segment Strategy:**
   - Engage older, inactive customers with tailored campaigns.
   - Offer incentives for customers with fewer products or lower balances.
   - General Insights:
   - Focus retention efforts on demographics and behaviors closely linked to churn risk.
- Use the Tableau dashboard to regularly monitor churn trends.
- Older customers and those with fewer products are more likely to churn.
- Customers with lower balances and salaries are at higher risk.
- Inactive customers represent a significant churn risk.

# Dashboard
## [Tableau Dashboard](https://public.tableau.com/app/profile/jliudoyle/viz/P2_Bank_Churn_Model/Demographics)

### [Seaborn Visualisations](https://github.com/jasonldoyle/Bank-Churn-Model/tree/main/EDA)

<img width="1366" alt="Tableau" src="https://github.com/user-attachments/assets/2d1950f1-9624-411d-83ef-414eb23901e4">
