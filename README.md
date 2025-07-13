# ☕ Coffee Sales Analysis – Python Project

This project provides a comprehensive analysis of coffee shop sales data between **March 1, 2024 and July 31, 2024**.
Using Python, Pandas, and Seaborn, I explored trends in coffee purchases, revenue generation, sales by time, and product performance.

---

## 🎯 Project Objective

To explore and visualize coffee sales data in order to:
- Understand daily, weekly, and monthly sales trends  
- Identify top-selling coffee types by volume and revenue  
- Analyze performance by day of the week  
- Compare revenue generated via card vs cash payments  
- Generate insights to support operational and marketing decisions  

---

## 📊 Types of Analysis Performed

### 🧼 Data Cleaning & Preprocessing
- Standardized column names
- Converted all date formats to `%Y-%m-%d`
- Created new columns: `month`, `day_name`, and `week`
- Filled missing card codes as `'no code'` for cash payments

### 📈 Time-Based Trends
- **Daily Sales Trend**: Revenue peaks observed near weekends and month-ends.
- **Weekly Sales Trend**: Clear upward patterns in mid-weeks; helpful for scheduling.
- **Day-of-Week Sales**: **Friday** recorded the highest average sales.

### ☕ Coffee Type Analysis
- **Top Selling Coffee (by revenue)**: `Latte` was the best-selling item, followed by `Hot Chocolate` and `Americano`.
- **Average Revenue per Coffee**: `Latte` also had the highest average transaction value.
- Plots: Barplot, stripplot for detailed comparison.

### 💳 Payment Mode Breakdown
- Majority of revenue was from **card payments**
- Pie chart showed **~75% of transactions used card**
- Average spend was **slightly higher** for card users

### 📈 Revenue Distribution
- Most transactions ranged from **₹250 to ₹400**

---

## 📊 Key KPIs

| Metric               | Value               |
|----------------------|---------------------|
| Total Revenue        | ₹3,92,000+ approx.  |
| Average Transaction  | ₹320.47             |
| Total Transactions   | 1133                |
| Most Ordered Coffee  | `Latte`             |
| Best Sales Day       | `Friday`            
