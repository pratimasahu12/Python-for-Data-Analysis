📊 Customer Segmentation using RFM Analysis (Python)
🔍 Project Overview

This project performs RFM (Recency, Frequency, Monetary) Analysis to segment customers based on their purchase behavior. The goal is to help businesses identify high-value customers, loyal users, potential loyalists, at-risk customers, and lost customers to drive targeted marketing strategies and revenue growth.

The analysis includes:

Data cleaning & preprocessing

RFM metric calculation

RFM scoring and customer segmentation

Business insights and visualizations

📁 Dataset

Customer Master Data – Customer demographics

Customer Transactions Data – Purchase history


⚙️ Tools & Technologies

Python

Libraries:

Pandas

NumPy

Matplotlib

Seaborn

🧠 Key Steps Performed
1️⃣ Data Cleaning & Preparation

Handled missing values

Converted date columns to datetime format

Filtered valid customer transactions

2️⃣ RFM Metric Calculation

Recency: Days since last purchase

Frequency: Number of transactions

Monetary: Total revenue per customer

3️⃣ RFM Scoring

Customers were scored on a scale of 1–5 for:

Recency (lower is better)

Frequency (higher is better)

Monetary (higher is better)

Final RFM Score created by combining R, F, M scores.

🏷️ Customer Segments Created

🏆 Champions

💚 Loyal Customers

🌱 Potential Loyalists

⚠️ At Risk

❌ Lost Customers

📦 Others

📈 Visualizations

Customers by Segment (Bar Chart)

Revenue Contribution by Segment (Pie Chart)

Recency vs Monetary Scatter Plot (Colored by Segment)

📊 Business Insights

A small percentage of customers contribute to a large share of revenue (Pareto Principle)

Loyal & Champion customers drive most revenue

At-risk customers need re-engagement strategies

Lost customers have very low contribution
