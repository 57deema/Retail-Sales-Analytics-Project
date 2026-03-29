# Retail-Sales-Analytics-Project
End-to-end business analytics project including data analysis, machine learning, and Power BI dashboard.
# Retail Sales Analysis and Prediction Using E-Commerce Data

## Overview
This project analyzes e-commerce sales data and builds a machine learning model to predict order value.

## Objectives
- Analyze sales trends
- Understand customer behavior
- Identify top product categories
- Predict order value

## Dataset
Brazilian E-Commerce Public Dataset by Olist (~100k records)
Due to file size limitations, the full dataset is available here:
Full dataset: https://drive.google.com/file/d/14y-K1ifZKRAMOLyYlYXtrY_sorC5QAHL/view?usp=drive_link

## Data Processing
- Merged multiple datasets
- Handled missing values
- Cleaned data

## EDA
- Sales trends over time
- Top product categories
- Customer distribution

## Model
- Random Forest Regressor
- MAE ≈ 108
- R² ≈ 0.03

## Explainability
- SHAP values used
- Price and freight value are most important

## Bias Analysis
- Compared across states and payment types
- No major bias found

## Dashboard
Multi-page Power BI dashboard including:
- Sales Overview
- Customer Insights
- Product Analysis
- Model Performance (Scoring Board)

## Model Scoring
The model was used to generate predictions (scoring), and results were visualized in the dashboard using KPI metrics and a scoring table.

## Project Files
- Business_Analytics_Project.ipynb → Data analysis & model
- Business_Analytics_Dashboard.pbix → Power BI dashboard
- final_dataset.csv → Cleaned dataset
- presentation.pdf → Project presentation
