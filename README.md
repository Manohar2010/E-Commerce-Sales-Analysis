
# E-Commerce Sales Analysis

## 📌 Project Overview
This project analyzes e-commerce transaction data to extract meaningful business insights related to revenue, customer behavior, and product performance.

---

## 📊 Dataset Description
The dataset includes:
- Order IDs and customer IDs  
- Product and category information  
- Price, quantity, and ratings  
- Order dates  

---

## 🧹 Data Cleaning
- Converted `order_date` to datetime format  
- Handled missing values:
  - Category → filled with "Unknown"  
  - Price → filled with mean  
  - Quantity → filled with median  
  - Rating → filled with median  

---

## ⚙️ Feature Engineering
- Created `total_price` (price × quantity)  
- Extracted date features:
  - Month  
  - Day  
  - Day name  
- Created `customer_type`:
  - High Value (≥ 1500)  
  - Medium Value (≥ 800)  
  - Low Value (< 800)  

---

## 📈 Key Insights

### Revenue Analysis
- Electronics category generated the highest revenue  
- Revenue varies across different months  

### Product Insights
- Identified the most sold product based on quantity  
- Identified the product generating the highest revenue  

### Customer Insights
- A small number of customers contributed the most revenue  
- High-value customers have significantly higher average spending  

### Ratings Insight
- Average ratings differ across categories, indicating potential quality variations  

---

## 🛠 Tools Used
- Python  
- Pandas  
- NumPy  

---

## 🚀 Future Improvements
- Add data visualizations (Matplotlib / Seaborn)  
- Build an interactive dashboard  
- Apply machine learning models for prediction  
