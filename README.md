# Instacart Reorder Prediction

Machine learning analysis of customer reorder behavior using feature engineering and classification model comparison.

## Overview
This project analyzes customer reorder behavior using the Instacart Market Basket Analysis dataset. The goal was to predict whether a customer would reorder a product based on historical shopping patterns, product-level characteristics, and temporal behavior.

## Business Problem
Accurately predicting reorders can help support:
- personalized recommendations
- demand forecasting
- inventory planning
- targeted marketing strategies

## Dataset
The analysis used the Instacart Market Basket Analysis dataset, including 3.4 million grocery orders, more than 200,000 users, and nearly 50,000 products.

## Methods
The project compared three classification models:
- Logistic Regression
- Random Forest
- XGBoost

Feature engineering focused on:
- customer reorder behavior
- product reorder patterns
- basket-level behavior
- temporal shopping variables

## Key Results
- Random Forest achieved the best test AUC: **0.772**
- XGBoost followed closely with test AUC: **0.771**
- Logistic Regression provided a baseline test AUC: **0.733**
- The most important predictors included:
  - user reorder ratio
  - product reorder rate
  - average basket size
  - days since prior order

## Skills Demonstrated
- machine learning classification
- feature engineering
- model evaluation
- business interpretation of predictive modeling
- e-commerce / retail analytics
- data storytelling

## Project Files
- [Final Report](reports/final-instacart-report.pdf)
- [Presentation Deck](presentations/instacart-capstone-presentation.pptx)

## Notes
This repository presents an academic capstone project in portfolio format, highlighting the methodology, results, and business relevance of the analysis.
