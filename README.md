# YASA-1 E-Commerce Data Analysis and Forecasting

## Introduction
This project is a comprehensive analytical solution developed for YASA-1 LLC, aimed at optimizing business operations and enhancing decision-making capabilities. Tasked by the Smart Business Analytics team, the project focuses on three key areas: demand forecasting, seller and product analysis, and product review sentiment analysis.

## Task 1: Demand Forecasting
### Objective
Implement a robust demand forecasting system for a short-term period (14 days) starting 7 days from the last date in the data for all product groups, including new products with minimal historical data.

### Approaches
1. **Machine Learning Forecasting**: Utilized regression models, such as Random Forest and Gradient Boosting, to predict future demand.
2. **Classical Time Series Forecasting**: Employed ARIMA models for time series forecasting.

## Task 2: Analysis of Sellers and Products
### Objective
Conduct an in-depth analysis of sellers and products on the marketplace, focusing on turnover, identifying sales leaders/outsiders in each area, and exploring the dependence of product weight on turnover and price. Additionally, provide segmentation of sellers and products with actionable business insights.

### Analysis Conducted
1. **Sellers**:
   - Identified sellers with the highest and lowest turnover.
   - Determined leaders and outsiders in sales within each area.
2. **Products**:
   - Conducted turnover analytics to identify top-performing products.
   - Analyzed the best-selling products in each category.
   - Investigated the relationship between product weight, turnover, and price.
   - Segmented sellers and products to derive meaningful business insights.

## Task 3: Analysis of Product Semantics
### Objective
Develop functionality to classify product review comments as positive, negative, or neutral, and analyze the correlation between text comments and numerical ratings (1-5). Identify products with the best/worst reviews, and highlight sellers who predominantly receive negative feedback. Additionally, extract and highlight price mentions in comments for competitor price analysis.

### Steps
1. **Sentiment Analysis**:
   - Implemented a classifier to categorize review comments into positive, negative, or neutral.
   - Analyzed the correlation between numerical ratings and text comments.
2. **Review Analytics**:
   - Identified products with the best and worst reviews.
   - Highlighted sellers who received mostly negative feedback.
3. **Price Extraction**:
   - Extracted price mentions from review comments.
   - Compared mentioned prices with actual product prices.

### Result

A visual representation of the analysis results provided in an `report1.pbix` file with accompanying code that generated the insights.

## Project Structure
- `data/`: Contains the datasets used for analysis.
- `notebooks/`: Jupyter notebooks with the analysis and visualizations.
- `scripts/`: Python scripts for forecasting and analysis.
- `README.md`: Project overview and detailed explanation.
