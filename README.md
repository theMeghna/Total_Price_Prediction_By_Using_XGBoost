# 🛒 Retail Transaction Price Prediction using XGBoost

## 📌 Objective
Predict the `TotalPrice` of retail transactions using customer behavior, product popularity, and temporal features — without directly using leaky features like `Quantity × UnitPrice`.

## 📊 Dataset
- Historical online retail transactions
- Includes: `InvoiceDate`, `Country`, `StockCode`, `Description`, `Quantity`, `UnitPrice`

## 🧠 Features Used
- Hour, Day, Month, Weekday
- CountryCode, StockCodeEnc
- Quantity (when needed), ProductAvgPrice
- ProductPopularity (total quantity sold per product)

## 🛠️ Model
- **Algorithm:** XGBoost Regressor
- **Target Variable:** Log-transformed `TotalPrice`
 - RMSE: varies based on feature inclusion

## 📌 Conclusion
XGBoost can effectively learn complex relationships in retail data, and feature engineering plays a crucial role in balancing realism with predictive power.

