# 📊 Superstore Sales Dashboard — Power BI

![Power BI](https://img.shields.io/badge/PowerBI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)

An interactive Power BI dashboard analysing US Superstore sales data across 9,994 orders from 2014–2017. Built to showcase data analysis, DAX, and data visualisation skills.

---

## 📸 Dashboard Preview
> *<img width="1371" height="767" alt="image" src="https://github.com/user-attachments/assets/dc6c3765-b27a-430e-a161-26ee0d82558c" />
*

---

## 🎯 Objective
To analyse sales performance across regions, customer segments, and product categories — and identify key trends and top-performing customers.

---

## 📁 Dataset
- **Source:** [Kaggle — Superstore Dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)
- **Records:** 9,994 orders
- **Period:** 2014 – 2017
- **Fields:** Order Date, Customer Name, Segment, Region, Category, Sub-Category, Sales, Quantity, Discount, Profit

---

## 🛠️ Tools Used
| Tool | Purpose |
|---|---|
| Power BI Desktop | Dashboard building & visualisation |
| Power Query | Data cleaning & transformation |
| DAX | Custom measures & calculations |

---

## 📐 DAX Measures Created
```dax
Total Sales = SUM('Sample - Superstore'[Sales])
Total Profit = SUM('Sample - Superstore'[Profit])
Total Orders = DISTINCTCOUNT('Sample - Superstore'[Order ID])
Total Quantity = SUM('Sample - Superstore'[Quantity])
Profit Margin = DIVIDE([Total Profit], [Total Sales], 0)
```

---

## 📊 Dashboard Features
| Visual | Description |
|---|---|
| KPI Cards | Total Sales, Profit, Orders, Quantity, Profit Margin |
| Bar Chart | Sales by Category |
| Donut Chart | Sales by Customer Segment |
| Table | Top 10 Customers by Sales |
| Map | Total Sales by US State |
| Slicers | Filter by Region & Segment |

---

## 💡 Key Insights
- 📦 **Technology** is the highest revenue-generating category at ~$0.83M
- 👥 **Consumer segment** dominates with 50.56% of total sales
- 📍 **California, New York & Texas** are the top performing states
- ⚠️ **Sean Miller** is the top sales customer but has negative profit (-$1,980) indicating heavy discounting
- 📈 Overall **Profit Margin** stands at **12.47%**

---

## 🚀 How to Use
1. Clone or download this repository
2. Open the `.pbix` file in **Power BI Desktop** *(free to download)*
3. Use the **Region** and **Segment** slicers to filter the dashboard interactively

---

## 👤 Author
**Vihar Yeole**
[LinkedIn](https://www.linkedin.com/in/viharyeole/) • [GitHub](https://github.com/Vihar2002)
