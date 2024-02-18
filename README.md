# Connecticut Real Estate Market Data Analysis Project

# Link to dataset: 
catalog.data.gov/dataset/real-estate-sales-2001-2018

# Overview:
This project conducts a detailed analysis of the real estate market, leveraging machine learning to categorize properties and evaluate market trends.

# Project Objectives:
The primary objective of this analysis is to understand the trends, patterns, and anomalies within the Connecticut real estate market. By leveraging data analytics, we aim to provide actionable insights for stakeholders in the real estate sector.

# Tools and Technology:
Python: Primary programming language for analysis.
Pandas: Data manipulation and analysis.
Seaborn & Matplotlib: Data visualization for trend analysis.
Scikit-learn: Machine learning library used for predictive modeling.

# Results:
Market Valuation Trends: The assessed values of properties have remained relatively stable over the years, while sale amounts have seen a significant increase, particularly around 2020. This divergence may indicate a robust market with properties selling above their assessed valuations.

Sales Ratio Decline: The sales ratio has decreased over time, suggesting a widening gap between sale prices and assessed values. This trend may point to conservative assessment practices or market conditions favoring buyers.

Classification Model: The logistic regression model shows a high accuracy for 'Residential' properties but fails to classify 'Non-Residential' properties, highlighting a class imbalance issue.

Predictive Model Evaluation: The Linear Regression model has nearly identical RMSE values for in-sample and out-of-sample data, suggesting good generalization. However, the Decision Tree model's perfect in-sample performance contrasts with its poor out-of-sample predictions, indicating overfitting.

Statistical Significance: A chi-square test reveals a significant association between property type and town location (p-value: 0.0), underscoring the influence of geography on property classification.
