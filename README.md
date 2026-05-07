# 🍕 Pizza Sales Power BI Dashboard

> End-to-end data analysis project — from raw Excel data to an interactive 2-page Power BI dashboard.

---

## 📌 Project Overview

This project analyzes pizza sales data for the full year **2015**. The goal was to extract meaningful business insights by performing complete data cleaning, transformation, DAX calculations, and interactive dashboard design using Power BI.

The dashboard answers real business questions:
- When are orders highest?
- Which pizza categories and sizes drive the most revenue?
- Who are the best and worst performing pizzas?

---

## 📊 Key KPIs

| Metric | Value |
|---|---|
| 💰 Total Revenue | $817.9K |
| 🍕 Total Pizzas Sold | 50K |
| 🛒 Total Orders | 21K |
| 💳 Avg Order Value | $38.3 |
| 📦 Avg Pizzas Per Order | 2 |

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| **Microsoft Excel** | Raw data source |
| **Power BI Desktop** | Dashboard development & visualization |
| **Power Query** | Data cleaning & transformation |
| **DAX** | Custom KPI measures & calculated columns |

---

## 🔄 Project Workflow

1. **Data Collection** — Raw pizza sales data in Excel format (.xlsx)
2. **Data Cleaning** — Handled nulls, corrected data types, removed duplicates via Power Query
3. **Data Transformation** — Structured tables, created date hierarchies and calculated columns
4. **DAX Measures** — Built measures for Revenue, Orders, Avg Values, Rankings (Top/Bottom N)
5. **Dashboard Design** — 2-page interactive report with slicers, filters, and drill-down

---

## 📑 Dashboard Pages

### Page 1 — Sales Overview
- 5 KPI summary cards (Revenue, Avg Order Value, Pizzas Sold, Avg Per Order, Total Orders)
- Daily order trend (bar chart — Fri leads, Sun lowest)
- Monthly order trend (area chart — July & January peak)
- % of Sales by Pizza Category (donut chart)
- % of Sales by Pizza Size (donut chart)
- Pizzas sold by category (horizontal bar chart)
- Busiest days/times & sales performance insights panel

### Page 2 — Best / Worst Sellers
- Top 5 & Bottom 5 pizzas by **Revenue**
- Top 5 & Bottom 5 pizzas by **Quantity**
- Top 5 & Bottom 5 pizzas by **Total Orders**
- Category-level filter buttons (Chicken, Classic, Supreme, Veggie)
- Date range slicer for dynamic filtering

---

## 💡 Key Insights

| # | Insight |
|---|---|
| 📅 | **Peak days:** Orders are highest on **Fridays & Saturdays** (evenings) |
| 📆 | **Peak months:** **July** and **January** record the most orders |
| 🏆 | **Top category:** **Classic** pizzas lead in both sales and total orders (26.91%) |
| 📏 | **Top size:** **Large** size contributes the highest revenue — **45.89%** of all sales |
| ⭐ | **Best seller:** The Thai Chicken Pizza leads by revenue |
| ❌ | **Worst seller:** The Brie Carre Pizza — lowest in revenue, quantity & orders (only 480 orders) |

---

## 🏁 Final Conclusion

After a full year of data (2015), the analysis paints a clear picture of a **healthy and consistent pizza business** generating **$817.9K in revenue** across **21,000 orders**.

### What the data tells us:

**Timing is predictable and actionable.**
Demand spikes every Friday and Saturday evening, and peaks again in July and January. This consistency means the business can plan staffing, inventory, and promotions with confidence rather than guesswork.

**Classic pizzas and Large sizes are the backbone of the business.**
The Classic category contributes 26.91% of category revenue and leads in total orders. Large size alone accounts for nearly half (45.89%) of all revenue. These two dimensions — category and size — are the highest-leverage areas for upselling and bundle strategies.

**The best and worst performers are clearly defined.**
The Thai Chicken Pizza tops revenue, while the Brie Carre Pizza consistently ranks last — in revenue, quantity, and orders (only 480 orders vs. 2,329 for the top performer). This 5x gap signals a product that is either poorly positioned, poorly priced, or simply not resonating with customers.

**The Chicken category has untapped potential.**
With 11K pizzas sold — the lowest of the four categories — yet its top item (Thai Chicken) leading in revenue, there is a clear mismatch between menu strength and promotion effort. Better visibility for Chicken items could significantly lift overall revenue.

### Business Recommendations:

1. **Run targeted promotions on Friday & Saturday evenings** to capitalize on peak demand windows.
2. **Increase inventory and staffing in July and January** to handle the seasonal surge without service drops.
3. **Push Large-size bundle deals** (e.g., Large pizza + drink) to grow average order value beyond $38.3.
4. **Review the Brie Carre Pizza** — with only 480 orders, consider reformulating, repricing, or discontinuing it to make room for stronger performers.
5. **Invest in promoting the Chicken category** — Thai Chicken's revenue performance proves there is demand; the category just needs more exposure.

### Overall verdict:

> The data tells a coherent and actionable story. The business has stable demand patterns, clear category winners, and specific underperformers that can be addressed immediately. This dashboard transforms raw sales data into a decision-making tool — and that is exactly the goal of data analysis.

---

## 📁 Repository Structure

```
Pizza-Sales-PowerBI-Dashboard/
│
├── data/
│   └── pizza_sales.xlsx              # Raw data file
│
├── dashboard/
│   └── Pizza_Sales_Dashboard.pbix    # Power BI report file
│
├── screenshots/
│   ├── Home Dashboard.png            # Sales Overview page
│   └── Pizza Dashboard.png          # Best/Worst Sellers page
│
└── README.md
```

---


## 🚀 How to Use

1. Clone this repository
   ```bash
   git clone https://github.com/your-username/Pizza-Sales-PowerBI-Dashboard.git
   ```
2. Open `dashboard/Pizza_Sales_Dashboard.pbix` in **Power BI Desktop**
3. Explore the report using the date slicer and category filter buttons

---

## 👤 Author

**[Ahmed Gamal]**
- 🔗 LinkedIn: [https://www.linkedin.com/in/ahmed-gamal-ahmed-824844263/?skipRedirect=true]
- 🐙 mail: [midog8867@gmail.com]

---

*Data source: Pizza Sales dataset (2015) | Built with Power BI Desktop*
