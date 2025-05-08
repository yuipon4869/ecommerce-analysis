# ecommerce-analysis

## Overview
This project analyzes an e-commerce dataset to uncover insights about customer purchasing behavior and sales trends. It includes data preprocessing, visualization, and regression modeling.

## 📊 Objective
- Understand customer purchasing behavior
- Explore the relationship between product price and quantity sold
- Build a regression model to predict product prices

## 🧰 Tools & Technologies
- Python
- Jupyter Notebook
- pandas, matplotlib, seaborn, scikit-learn

## 📁 Dataset
- Source: [Kaggle - E-Commerce Sales Prediction Dataset](https://www.kaggle.com/datasets/nevildhinoja/e-commerce-sales-prediction-dataset)
- Key columns: `Date`, `Price`, `Quantity`, `Product_Category`, `Shipping_Cost`

## 📈 Analysis Highlights
- Sales peaked in [Month]
- Category X contributed to 40% of total revenue
- Linear Regression showed RMSE = 3.27, indicating [brief conclusion]

## 🔮 Future Work
- Build a dashboard using Streamlit
- Try more advanced models (e.g., Random Forest, XGBoost)
- Segment customers with clustering

## 📕 Workflow
1. Load and explore the dataset
2. Clean missing or incorrect values
3. Convert and extract features from date (year, month, weekday)
4. Visualize key patterns (e.g. price distribution, correlations)
5. Train a regression model using RandomForestRegressor
6. Evaluate model performance (e.g. RMSE)

## 🔑 Key Findings
- Most products fall in a low-price range
- Quantity and price show weak negative correlation
- Weekday and monthly trends reveal patterns in order frequency
- Regression model achieved reasonable accuracy for price prediction

## ❓ How to Run
1. Clone the repository
2. Install dependencies:
   ```bash
   git clone https://github.com/yuipon4869/ecommerce-analysis.git
   cd ecommerce-analysis
   jupyter notebook
