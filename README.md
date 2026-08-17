# 🛒 Superstore Sales Performance Dashboard — Power BI

## 📌 Project Overview

An interactive, 2-page Power BI dashboard analyzing Superstore's
sales performance across 2019 and 2020. Built to uncover insights
on segment and payment behavior, year-over-year growth, regional
performance, category demand, and short-term sales forecasting.

---

## 📊 Dataset Summary

| Metric              | Value   |
| -------------------- | ------- |
| Total Sales           | 1.6M    |
| Total Profit           | 175K    |
| Total Quantity Sold    | 22K     |
| Avg Delivery Days     | 4       |
| Regions Covered        | 4 (Central, East, South, West) |

**States Covered:** California · New York · Texas · Washington · Pennsylvania ·
Ohio · Illinois · Florida · Michigan · North Carolina

---

## 🗂️ Dashboard Pages

### Page 1 — Sales Overview & Regional Performance

Analyzes sales and profit performance by customer segment,
payment method, category, and geography, with a year-over-year
comparison between 2019 and 2020.

**Key Visuals:**

- KPI cards (Total Sales, Total Profit, Total Quantity, Avg Delivery Days)
- Donut charts: Sales by Segment, Sales by Payment Method
- Area charts: Monthly Sales by YoY, Monthly Profit by YoY (2019 vs 2020)
- Map: Sales & Profit by State
- Bar charts: Sales by Category, Sales by Sub-Category, Sales by Ship Mode
- Region filter (Central, East, South, West)

**Key Insights:**

- Consumer segment drives 48% of total sales, ahead of Corporate (33%)
  and Home Office (19%)
- Cash on Delivery is still the leading payment method (43%), ahead
  of Online (35%) and Card payments (22%)
- 2020 sales and profit surged sharply from September to December
  compared to 2019, pointing to a strong holiday season
- Office Supplies leads all categories (644K), with Phones as the
  top sub-category (197K)
- Standard Class shipping dominates (912K), showing customers
  prioritize cost over delivery speed

---

### Page 2 — Sales Forecast & State-Level Breakdown

Projects short-term sales using a 15-day forecast model, alongside
a full state-by-state sales ranking.

**Key Visuals:**

- Forecast line chart: Sales Forecast — 15 Days (with confidence interval)
- Ranked bar chart: Sales by States

**Key Insights:**

- Daily sales are highly volatile through Q4 2020, with recurring
  spikes as high as 10.6K followed by sharp dips
- The forecast projects a noticeable slowdown heading into
  January 2021
- California leads all states at 335K — nearly double New York (187K)
- Texas (116K), Washington (93K), and Pennsylvania (82K) round out
  the top 5
- Sales are heavily concentrated in the top 3 states, while states
  like Michigan (49K) and North Carolina (40K) lag well behind

---

## 🔧 Tools & Techniques

| Area          | Details                                   |
| ------------- | ------------------------------------------ |
| Tool          | Microsoft Power BI Desktop                  |
| Data Source   | Superstore Sales dataset                    |
| Data Cleaning | Power Query — nulls, data types, outliers   |
| Data Modeling | Relationships across orders, products,      |
|               | customers, and date tables                  |
| DAX Measures  | Total sales, profit margin, YoY comparison, |
|               | delivery days, forecast bands               |
| Visuals Used  | Donut charts, area charts, filled map,      |
|               | KPI cards, ranked bar charts, forecast line |

---

## 💡 Business Questions Answered

1. Which customer segment and payment method drive the most sales?
2. How did sales and profit performance change year-over-year?
3. Which regions and states generate the highest revenue?
4. Which product categories and sub-categories perform best?
5. Which shipping mode do customers prefer, and why?
6. What does short-term sales demand look like going forward?

---

## 📈 Key Findings Summary

- **Segment Leader:** Consumer segment accounts for nearly half
  of all sales
- **Payment Behavior:** Cash on Delivery remains more popular
  than online payments
- **YoY Growth:** 2020 significantly outperformed 2019, driven
  by a strong Q4
- **Category Leader:** Office Supplies leads sales; Phones lead
  sub-categories
- **Geographic Concentration:** California, New York, and Texas
  drive a disproportionate share of revenue
- **Shipping Preference:** Customers favor cost (Standard Class)
  over delivery speed
- **Forecast Signal:** Volatile Q4 demand, with a projected
  slowdown into January 2021

---

👤 Author : Muhammad Ibtisam
Data Analyst | Power BI · SQL · Python · Excel
🔗 LinkedIn | GitHub
