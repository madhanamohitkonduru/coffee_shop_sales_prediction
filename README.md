<h1>Coffee Shop Inventory Data Analysis</h1>
<h2>Introduction</h2>
This repository contains my project as a student analyzing inventory data for 132 stores of an international coffee shop chain with over 1000 stores worldwide and $400M in revenue. The primary goal is to enhance sales and reduce waste through effective sales prediction and inventory alignment. This project focuses on three specific stores (StoreID=18, 117, 332).

<h2>Data Description</h2>
The dataset includes the following fields:

StoreID: Identifier for the store.
BusinessDate: Date of the record.
PLU: Inventory ID.
Description: Name of the product.
ItemType: Type of product.
CategoryLvl1Desc, Lvl2Desc, Lvl3Desc: Category details of the product.
ReceivedQuantity: Amount received from the distributor.
SoldQuantity: Quantity sold on a specific day.
EndQuantity: Inventory at the end of the day.
LatestOrder: Number of items requested in the latest order.
StockedOut: Instances when a product was out of stock.
MissedSales: Uncertain data, significance unknown.
<h2>Project Objectives</h2>

<h2>Analytical Goals:</h2>
Inventory & Sales Insight: Analyze inventory patterns, stock outs, and potential missed sales opportunities.
Product Performance Evaluation: Identify best and worst-performing products based on sales and inventory management.
Temporal Impact Analysis: Investigate how day of the week, month, and weather conditions affect sales and inventory.
Stocking Optimization: Suggest recommendations for stocking patterns based on data from multiple stores.

<h2>Predictive Modeling:</h2>
Data Generation: Utilize Generative models (GANs) for better predictions with limited historical data.
Feature Optimization: Select and engineer features for predictive modeling, including external factors like weather.
Model Development & Comparison: Implement and assess models like Random Forest, XGBoost, CNN, and others.
Forecasting: Predict future sales based on model results and external factors.
