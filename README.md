# 🛍️ Vrinda Store Annual Sales Report

An interactive sales analytics dashboard built entirely in **Microsoft Excel** — using Pivot Tables, Pivot Charts, and Slicers to turn raw e-commerce order data into a dynamic, filterable annual sales report.

---

## 📌 Problem Statement

Vrinda Store sells across multiple e-commerce channels (Amazon, Myntra, Flipkart, Ajio, Meesho, Nalli, and others). With thousands of orders spread across categories, cities, and customer segments, the business needs a single view to understand:
- Which channels and states drive the most revenue?
- How do sales differ by customer age group and gender?
- What percentage of orders are delivered vs. refunded, returned, or cancelled?
- Which product categories and months perform best?

This dashboard answers these questions without requiring any BI tool — built entirely with native Excel features, making it easy for small/medium retailers to adopt.

---

## 🗂️ Dataset

Raw order-level data with the following fields:
- Order ID, Customer ID, Gender, Age, Age Group
- Order Date, Month, Status (Delivered/Refunded/Returned/Cancelled)
- Sales Channel (Amazon, Myntra, Flipkart, Ajio, Meesho, Nalli, Others)
- SKU, Category, Size, Quantity, Currency, Amount
- Ship-to City

---

## 🛠️ Tools & Tech Stack

| Tool | Purpose |
|------|---------|
| **Microsoft Excel** | Data cleaning, Pivot Tables, Pivot Charts, Slicers |
| **Excel Functions** | Data validation and categorization (Age Group, Month) |

---

## ⚙️ Approach

1. **Data Cleaning** — Structured raw order data across dedicated sheets (Men vs Women, Order Status, State wise Sales, Age & Gender, Channels Contribution)
2. **Pivot Table Modeling** — Built pivot tables to summarize sales by category, channel, state, age group, and order status
3. **Pivot Charts** — Visualized each summary with the appropriate chart type (bar, pie, combo)
4. **Interactivity** — Added Slicers (Category, Month, Channel) so the entire dashboard updates dynamically based on user selection
5. **Dashboard Assembly** — Combined all visuals onto a single dashboard sheet for an at-a-glance annual report

---

## 📊 Dashboard Overview

**Key Metrics & Visuals:**
- **Orders vs Sales** — Combo chart showing order count against total sales amount by month
- **Orders: Age vs Gender** — Grouped bar chart comparing Adult, Senior, and Teenager purchase behavior by gender
- **Orders: Channels** — Pie chart showing revenue share across Amazon, Myntra, Flipkart, Ajio, Meesho, and others
- **Sales: Top 5 States** — Horizontal bar chart ranking states by revenue
- **Order Status** — Pie chart breaking down Delivered, Refunded, Returned, and Cancelled orders
- **Sales: Men vs Women** — Pie chart comparing total revenue share by gender

![Sales Dashboard](Vrinda-Sales-Dashboard.png)
![Raw Data Sheet](Vrinda-Raw-Data.png)

---

## 🔑 Key Findings

- **Women drive 63% of total orders** compared to 37% for men, indicating a strongly female-skewed customer base
- **Amazon is the dominant sales channel (36%)**, followed by Myntra and Flipkart (22% each)
- **Maharashtra and Karnataka are the top-performing states**, together contributing over 0.47M in sales
- **93% of orders are successfully delivered**, with only 3% cancelled and 2% each refunded/returned — indicating healthy fulfillment operations
- **Adult women (38.15%) are the single largest buyer segment**, far ahead of any other age-gender combination
- Teenagers show stronger purchase share among women (16.95%) than men (8.44%), suggesting gender-skewed category preferences worth exploring further

---

## 🚀 How to Use This Dashboard

1. Open `Vrindra_Sales_Dashboard.xlsx` in Excel
2. Navigate to the **Dashboard** sheet
3. Use the **Category**, **Month**, and **Channel** slicers to filter the entire report dynamically
4. Switch between underlying data sheets (Men vs Women, Order Status, State wise Sales, Age & Gender, Channels Contribution) to see the pivot tables behind each chart

---

## 📁 Repository Structure

```
├── Vrindra_Sales_Dashboard.xlsx   # Full Excel workbook with raw data, pivot tables, and dashboard
├── screenshots/                   # Dashboard preview images
└── README.md
```

---

## 👤 Author

**Farhan Adil**
Data Scientist | AI Automation
