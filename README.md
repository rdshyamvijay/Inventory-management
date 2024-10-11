# Inventory Optimization Using Predictive Analytics

This project demonstrates how to build a predictive model to optimize inventory management using **Random Forest**. The model predicts future inventory levels based on features such as **weekly sales**, **temperature**, **past promotions**, and **demand forecasts**.

## Project Overview

The goal of this project is to reduce overstocking and stockouts by forecasting inventory levels more accurately, thus improving procurement efficiency.

### Dataset

The dataset used includes the following columns:
- **Store**: The store ID.
- **Date**: Date of the record.
- **Product**: Product ID.
- **Weekly_Sales**: Number of sales for the product in that week.
- **Inventory level**: The current inventory level for the product.
- **Temperature**: The temperature of the store location during that week.
- **Past promotion of product in lac**: Whether a promotion occurred.
- **Demand forecast**: Forecasted demand for the product.

### Project Steps

1. **Data Preprocessing**: 
   - Handle missing values.
   - Convert the `Date` column to datetime format.
   - Feature engineering: created lagged features for `Weekly Sales`.

2. **Modeling**:
   - A **Random Forest Regressor** was trained to predict the `Inventory level`.
   - Model performance was evaluated using **Mean Squared Error**.

3. **Results**:
   - The model predicts future inventory levels and helps optimize stock levels, reducing inefficiencies by ensuring optimal inventory.

