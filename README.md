# 🍕 Pizza Sales Power BI Dashboard

> End-to-end data analysis project — from raw Excel data to an interactive Power BI dashboard.

---

## 📌 Project Overview

This project analyzes pizza sales data for the year 2015. The goal was to extract meaningful business insights by performing full data cleaning, transformation, and visualization using Power BI.

---

## 📊 Key KPIs

| Metric | Value |
|---|---|
| Total Revenue | $817.9K |
| Total Pizzas Sold | 50K |
| Total Orders | 21K |
| Avg Order Value | $38.3 |
| Avg Pizzas Per Order | 2 |

---

## 🛠️ Tools & Technologies

- **Microsoft Excel** — Raw data source
- **Power BI Desktop** — Dashboard development
- **Power Query** — Data cleaning & transformation
- **DAX** — Custom KPI measures & calculations

---

## 🔄 Project Workflow

1. **Data Collection** — Raw pizza sales data in Excel format
2. **Data Cleaning** — Handled nulls, corrected data types, removed duplicates
3. **Data Transformation** — Structured tables, created date hierarchies via Power Query
4. **DAX Measures** — Built measures for Revenue, Orders, Avg Values, Rankings
5. **Dashboard Design** — 2-page interactive report with slicers & filters

---

## 📑 Dashboard Pages

### Page 1 — Sales Overview
- 5 KPI cards (Revenue, Avg Order Value, Pizzas Sold, Avg Per Order, Total Orders)
- Daily & Monthly order trend charts
- % of Sales by Pizza Category (donut chart)
- % of Sales by Pizza Size (donut chart)
- Pizzas sold by category (bar chart)
- Busiest days/times & sales performance insights

### Page 2 — Best/Worst Sellers
- Top 5 & Bottom 5 pizzas by Revenue
- Top 5 & Bottom 5 pizzas by Quantity
- Top 5 & Bottom 5 pizzas by Total Orders
- Category-level filter buttons (Chicken, Classic, Supreme, Veggie)

---

## 💡 Key Insights

- 📅 **Peak Days:** Orders are highest on **Fridays & Saturdays** (evenings)
- 📆 **Peak Months:** **July** and **January** record the most orders
- 🍕 **Top Category:** **Classic** pizzas lead in both sales and total orders
- 📏 **Top Size:** **Large** size contributes the highest revenue (45.89%)
- 🏆 **Best Seller:** The Thai Chicken Pizza (by revenue)
- ❌ **Worst Seller:** The Brie Carre Pizza (lowest revenue, quantity & orders)

---

## 📁 Repository Structure

```
Pizza-Sales-PowerBI-Dashboard/
│
├── data/
│   └── pizza_sales.xlsx          # Raw data file
│
├── dashboard/
│   └── Pizza_Sales_Dashboard.pbix  # Power BI file
│
├── screenshots/
│   ├── page1_overview.png
│   └── page2_best_worst.png
│
└── README.md
```

---

## 📸 Dashboard Screenshots

### Sales Overview
![Sales Overview](screenshots/page1_overview.png)

### Best / Worst Sellers
![Best Worst Sellers](screenshots/page2_best_worst.png)

---

## 🚀 How to Use

1. Clone the repository
2. Open `dashboard/Pizza_Sales_Dashboard.pbix` in Power BI Desktop
3. Explore using the date slicer and category filters

---

## 👤 Author

**[Your Name]**
- LinkedIn: [your-linkedin]
- GitHub: [your-github]

---

*Data source: Pizza Sales dataset (2015)*
