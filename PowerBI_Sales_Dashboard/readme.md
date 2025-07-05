# 📊 Power BI Sales Dashboard — Supervisor-Wise Sales Analysis

This project showcases a fully interactive **Sales Dashboard** built using **Power BI**.  
It helps analyze product-wise, region-wise, and supervisor-wise performance through advanced visuals, slicers, and DAX-based KPIs.

---

## 🧠 1. Problem Statement

The business team was struggling to track **sales performance supervisor-wise**.  
Despite having the data, they couldn’t derive insights such as:
- Which supervisors are performing best?
- Which product categories and brands are driving the most revenue?
- Which states are leading in sales?

---

## 🎯 2. Objective

- Build an interactive, user-friendly dashboard to track:
  - Supervisor-level sales performance
  - Key KPIs like Total Sales, Profit, Quantity Sold, and Orders
  - Region-wise, brand-wise, and product-wise analysis
- Allow decision-makers to slice data and view real-time performance

---

## 🛠️ 3. Tools & Techniques Used

| Tool / Feature         | Usage |
|------------------------|-------|
| Excel                  | Data Source |
| Power Query            | Data cleaning & transformation |
| Power BI Data Model    | Created relationships among tables |
| DAX (Data Analysis Expressions) | Created KPIs like Total Profit |
| Slicers & Filters      | Image slicer for supervisors |
| Cards, Charts, Maps    | For visualization |

---

## ⚙️ 4. Implementation Steps

- Imported sales and supervisor data from Excel
- Transformed and cleaned data using Power Query
- Created relationships between multiple tables (Product, Region, Sales)
- Added calculated columns & measures using DAX:
  ```DAX
  Total Profit = [Total Sales] - [Total Cost]
