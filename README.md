# 🍔 Food Delivery Data Analysis

## 📌 Project Overview
This project focuses on analyzing a food delivery dataset to understand customer behavior, order patterns, revenue, and overall business insights.

The dataset includes details like customer age, city, order value, discounts, ratings, and order status.

---

## 📂 Dataset
- File: `food_delivery_dataset_realistic_80000.csv`
- Total Records: ~80,000  

### Columns Included:
- Customer Age  
- City  
- Order Value  
- Discount  
- Restaurant Rating  
- Order Status  

---

## 🧹 Data Cleaning
Some values were missing, so the following steps were taken:

- Filled missing **Customer Age** with median value  
- Filled missing **Restaurant Rating** with median  
- Filled missing **Discount** with median  

Also:
- Converted numeric columns (like Customer Age, Order Value) into proper integer format  

---

## 🔧 Feature Engineering

### 1. Age Category
Customers were grouped into:
- Young (18–30)  
- Middle Age (31–45)  
- Old (45+)
## 📊 Analysis Performed

### 1. Orders by City
- Count of orders from each city  
- Helps identify high-demand areas  

### 2. Customer Distribution by Age Group
- Shows which age group orders the most  

### 3. Revenue Analysis
- Revenue based on completed orders  
- Cancelled orders do not contribute  

---
## 📈 Key Insights
- Certain cities have much higher order volumes  
- Young customers contribute the most orders  
- Discounts reduce overall revenue  
- Cancelled orders impact profit negatively  

---

## 🛠 Tools Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  

---

## 🚀 Conclusion
This analysis helps in understanding:
- Customer behavior  
- Revenue trends  
- Business performance  

It can be used to improve:
- Marketing strategies  
- Customer targeting  
- Profit optimization  
