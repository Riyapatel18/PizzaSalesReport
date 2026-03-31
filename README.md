# Pizza Sales Analysis Dashboard (SQL + Power BI)

## Project Overview

This project analyzes pizza sales data to uncover key business insights using **SQL (MySQL)** and **Power BI**.

The goal is to track business performance, identify trends, and understand customer behavior through an interactive dashboard.

---

## Objectives

- Analyze total revenue and order trends
- Identify peak sales hours and weeks
- Understand customer preferences (category & size)
- Find top-performing and underperforming pizzas
- Build a professional dashboard for business decision-making

---

## Tools & Technologies Used

- **MySQL** – Data storage & transformation
- **SQL** – Data querying and aggregation
- **Power BI** – Data visualization & dashboard creation

---

## Dataset Description

The dataset contains **150K+ records** of pizza sales with the following fields:

- `order_id`
- `pizza_name`
- `pizza_category`
- `pizza_size`
- `quantity`
- `order_date`
- `order_time`
- `unit_price`
- `total_price`

---

## Project Architecture

---

## SQL Data Preparation

Instead of directly loading raw data into Power BI, **SQL Views** were created for:

- Performance optimization
- Reusability
- Clean data modeling

### Key Views Created

- `kpi_summary`
- `hourly_orders`
- `weekly_orders`
- `sales_by_category`
- `sales_by_size`
- `orders_and_pizzas_by_category`
- `top_5_pizzas`
- `bottom_5_pizzas`

---

## Key Metrics (KPIs)

- **Total Revenue**
- **Total Orders**
- **Total Pizzas Sold**
- **Average Order Value**
- **Average Pizzas per Order**

---

## Dashboard Features

### 1. KPI Section
Displays key business metrics for quick insights.

### 2. Busiest Hours & Weeks
- Hourly trend of orders
- Weekly trend with average line

### 3. Sales Performance
- % of sales by pizza category
- % of sales by pizza size
- Orders vs pizzas sold by category

### 4. Best & Worst Sellers
- Top 5 pizzas by revenue
- Bottom 5 pizzas by performance

---

## Visualizations Used

- KPI Cards
- Stacked Column Chart
- Line Chart (with average line)
- Donut Chart
- Bar Chart
- Clustered Bar Chart
- Slicers (filters)

---

## Key Insights

- Peak orders occur during **lunch and evening hours**
- Certain pizza categories contribute significantly to revenue
- Medium and Large sizes are most preferred
- Top 5 pizzas generate a large portion of revenue
- Sales fluctuate weekly with peak demand periods

---

## Performance Optimization

- Used **SQL views** instead of raw data loading
- Reduced dataset size before Power BI ingestion
- Avoided heavy DAX calculations
- Ensured faster dashboard performance

---

## Challenges Faced

- Date & time stored as text → converted using SQL
- Avoiding duplicate order counting
- Designing dashboard layout similar to real-world reports

---

## Learnings

- Importance of SQL in data preparation
- Difference between SQL vs DAX responsibilities
- Real-world BI architecture
- Dashboard design best practices

---

## Future Improvements

- Add drill-through functionality
- Implement time-based filters (monthly/yearly)
- Add forecasting and trend prediction
- Optimize for larger datasets (1M+ rows)

---

## Dashboard Preview

<img width="1317" height="718" alt="DashBoard_Homepage" src="https://github.com/user-attachments/assets/194feb47-772a-4b91-9111-973084b02c61" />

<img width="1314" height="721" alt="BestWorstSeller" src="https://github.com/user-attachments/assets/66b92528-fdf7-428e-90cf-00186d8e57e7" />

---

## Author

**Riya Patel**

---
