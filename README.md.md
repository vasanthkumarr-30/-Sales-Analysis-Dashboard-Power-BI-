# 📊 Sales Analysis Dashboard

A Power BI dashboard providing comprehensive sales insights across regions, products, salespersons, and time periods — built to support data-driven decision-making.

![Sales Analysis Dashboard](Sales_Analysis_Dashboard_png.png)

---

## 📁 Project Structure

```
Sales-Analysis-Dashboard/
│
├── Sales_Dashboard.pbix           # Power BI Dashboard file
├── Sales_dataset.csv              # Raw sales dataset
├── Sales_Analysis_Dashboard.png   # Dashboard screenshot/preview
└── README.md                      # Project documentation
```

---

## 📌 Project Overview

This project visualizes sales data spanning **2023–2024** across multiple dimensions including region, product, salesperson, and category. The dashboard is built in **Microsoft Power BI** and enables quick exploration of key performance metrics through interactive filters.

---

## 📊 Dataset Description

**File:** `Sales_dataset.csv`  
**Records:** 100 orders  
**Date Range:** January 2023 – November 2024

| Column | Description |
|---|---|
| `OrderID` | Unique identifier for each order |
| `Date` | Date of the transaction |
| `Region` | Sales region (North, South, East, West) |
| `Salesperson` | Name of the salesperson |
| `Product` | Product sold (Laptop, Monitor, Keyboard, Tablet, Mobile) |
| `Category` | Product category (Electronics, Accessories) |
| `Quantity` | Number of units sold |
| `Price` | Unit price |
| `Sales` | Total sales value (Quantity × Price) |

---

## 📈 Dashboard Features

### 🔢 KPI Cards
- **Total Sales** — 15M
- **Total Quantity** — 563
- **Total Orders** — 100
- **Average Sales** — 147.99K

### 📊 Visualizations
| Chart | Description |
|---|---|
| Total Sales by Region | Horizontal bar chart comparing North, West, East, South |
| Total Sales by Product | Column chart for all 5 products |
| Total Sales by Year | Donut chart comparing 2023 vs 2024 |
| Total Sales by Category | Pie chart — Electronics (76.38%) vs Accessories (23.62%) |
| Sales by Salesperson | Bar chart ranking all 6 salespersons |
| Top 5 Sales by Product | Ranked horizontal bar chart |
| Sales by Day of Week | Horizontal bar chart by day |
| Sales by Month | Line chart tracking monthly trends |

### 🔍 Filters / Slicers
- Filter by **Salesperson** (Amit, Karan, Neha, Priya, Rahul, Sneha)

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| Microsoft Power BI Desktop | Dashboard creation and visualization |
| Microsoft Excel / CSV | Data source |
| DAX (Data Analysis Expressions) | Calculated measures and KPIs |

---

## 🚀 How to Use

1. Download and install [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free).
2. Clone or download this repository.
3. Open `Sales_Dashboard.pbix` in Power BI Desktop.
4. The dataset is embedded — the dashboard will load automatically.
5. Use the **Salesperson slicer** on the top-right to filter data interactively.

---

## 💡 Key Insights

- **North and West** regions lead in total sales (~4.2M each).
- **Laptops and Keyboards** are the top-performing products (~3.5M each).
- **Electronics** dominates category sales at 76.38%.
- **Sneha** is the highest-performing salesperson at 3.4M in sales.
- Sales dipped mid-year (**June–July**) and recovered toward year-end.

---

## 👤 Author

> Vasanth Kumar R,
> www.linkedin.com/in/vasanth-kumar-r-125092229
 


---

## 📄 License

This project is for educational and portfolio purposes. Feel free to use and modify with attribution.
