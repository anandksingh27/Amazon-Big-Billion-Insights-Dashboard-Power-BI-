🛒 Amazon Big Billion Insights Dashboard (Power BI)

This project presents an interactive Amazon Big Billion Sale Insights Dashboard built in Power BI to analyze sales, orders, profit, ratings, categories, and customer behavior during mega-sale events.

---

📊 Key Insights

Total Sales Amount, Revenue & Profit

Total Orders (Distinct Count)

Rating Distribution (1–5 Stars)

Category & Region-wise Performance

Discount & Payment Method Analysis

---

🛠 Skills Used

Power BI

DAX

Data Modeling

Data Cleaning

Visualization Design

---

📐 Main DAX Measures

Total Orders = DISTINCTCOUNT(amazon_big_billion_dataset_extended[OrderID])
Profit = SUM(amazon_big_billion_dataset_extended[Revenue]) - SUM(amazon_big_billion_dataset_extended[ShippingCharge])

---

📂 Project Summary

The Amazon Big Billion Insights Dashboard provides a clear view of how products performed during high-sale periods, helping identify best-selling categories, customer preferences, and profit behavior.
