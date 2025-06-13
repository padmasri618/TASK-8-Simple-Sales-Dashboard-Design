#  Task 8 - Sales Performance Dashboard using Tableau

---

## 1.Objective

The objective of this project is to create a simple and interactive dashboard using Tableau that helps visualize and analyze sales performance across:
- **Time (Month-Year)**
- **Regions (Central, East, South, West)**
- **Product Categories (Furniture, Office Supplies, Technology)**

This dashboard enables business stakeholders to explore trends, identify top-performing areas, and derive actionable insights for data-driven decision-making.

---
## 2.  Dataset Explanation

- **Dataset**: `Sample - Superstore.csv`
- **Source**: Provided with the internship task
- **Key Fields Used**:
  - `Order Date`: Converted to Month-Year for trend analysis
  - `Region`: Used for both visual comparison and slicer
  - `Category`: Used for product segmentation
  - `Sales`: Used as the main KPI for analysis
  - `Profit`: Referenced in insights (not visualized directly)

---

## 3. Explanation of Charts

### 🔹 Monthly Sales Trend (Line Chart)
Displays how total sales have changed over the years (2014–2017), allowing stakeholders to observe growth patterns and seasonal spikes in revenue.

### 🔹 Sales by Region (Bar Chart)
Compares total sales across regions. This visualization highlights regional performance, helping to identify strong and weak markets geographically.

### 🔹 Sales by Category (Pie Chart)
Breaks down sales by product category to determine which product lines contribute the most to overall revenue.

Each chart is dynamically connected through a **Region filter**, enabling focused analysis.

---

## 4.  Dashboard Features

- **Interactive Region Filter (Slicer)**: A checklist filter that allows users to select specific regions and see corresponding updates across all charts.
- **Clean, professional layout** with three clear visual sections.
- **Color-coded legends** for category clarity.
- **Descriptive titles** and consistent formatting for a polished look.

📷 *Screenshot available:* `Task8 - Dashboard.png`

---

## 5.  Key Insights

1. The **West region** consistently had the highest total sales across all years.
2. **Technology** was the leading sales-generating category.
3. Sales showed strong **seasonal increases** in **November and December**.
4. The **South region** underperformed in both sales volume and consistency.
5. From 2015 to 2017, sales demonstrated **steady year-over-year growth**.

---

## 6. Patterns Identified

- **Growth Pattern**: Sales consistently increased over time, especially from 2016 to 2017.
- **Regional Dominance**: West and East regions were the most dominant in terms of sales.
- **Category Focus**: Technology led in revenue, likely due to high-value products and strong demand.
- **Seasonal Sales Peaks**: Significant spikes occurred in Q4 annually, indicating effective promotional cycles.

---

## 7. Anomalies Observed

- Despite high revenue, the **Furniture category** may have had **lower profitability**, hinting at high costs or discounts.
- The **South region** had consistently lower sales, potentially indicating issues with outreach, demand, or logistics.
- **East region** showed fluctuations—strong in some periods, weak in others—suggesting unstable sales cycles.

---
## 8. Conclusion

- This project illustrates how a simple dashboard in Tableau can deliver valuable business insights by combining time-based trends, regional comparisons, and product-category breakdowns. It empowers teams to monitor performance, detect problems, and capitalize on strengths using data-driven visuals.



