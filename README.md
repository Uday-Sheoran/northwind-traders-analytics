# northwind-traders-analytics
A data analytics project exploring the Northwind Traders dataset using Excel (EDA) and Power BI to uncover insights into sales performance, customer behavior, employee productivity, and supplier trends. The project combines data cleaning, exploratory data analysis, and interactive dashboard creation to support data-driven decision-making.
# 🧭 Northwind Traders Analytics

### 📊 MySQL · Excel EDA · Power BI Project

This project explores and visualizes data from the **Northwind Traders** database — a classic dataset representing a global food trading company.  
The goal is to generate actionable business insights through **SQL-based data analysis**, **Exploratory Data Analysis (EDA)** in Excel, and a complementary **Power BI dashboard** for visual storytelling.

---

## 📁 Project Overview

The project provides a **comprehensive analytical view** of Northwind Traders’ operations by consolidating multiple datasets — including sales, customers, employees, products, and suppliers.  
The analysis pipeline integrates **MySQL** for querying and preparing raw data, **Excel** for detailed exploratory analysis, and **Power BI** for dynamic visualization and reporting.  
Through EDA, the analysis uncovers key patterns in customer behavior, employee productivity, and supplier dynamics, enabling data-driven decision-making.

---

## 🎯 Objectives

- Analyze **sales performance**, **customer behavior**, and **employee distribution**.  
- Explore **seasonality**, **category performance**, and **supplier relationships**.  
- Build a **Power BI dashboard** to visually summarize KPIs.  
- Support business decision-making with data-backed insights.

---

## 🧠 Key Questions Explored

### **Exploratory Data Analysis (EDA)**
- Who are the company’s high-value customers and what are their purchasing behaviors?  
- Which regions and countries drive the most sales?  
- How are employees distributed by geography and title?  
- What seasonal trends and category-level patterns can be observed?  
- How do supplier regions and pricing strategies differ?

---

## 🧾 Dataset Description

The **Northwind database** simulates a trading company’s global operations, covering customers, orders, products, and employees.

| Table | Description |
|-------|--------------|
| **Customers** | Details on buyers and their locations |
| **Orders** | Transaction data with dates and shipping details |
| **Order Details** | Line items per order with price and discount |
| **Products** | Product info including category, price, and stock |
| **Employees** | Company staff details and titles |
| **Suppliers** | Information on product suppliers and their regions |
| **Categories** | Product category names and descriptions |

---

## 🧩 Tools & Technologies

| Tool | Purpose |
|------|----------|
| **MySQL** | Data extraction, transformation, and SQL-based analysis |
| **Microsoft Excel** | Exploratory Data Analysis (EDA) and visualization |
| **Power BI Desktop** | Interactive dashboard for KPI visualization |
| **GitHub** | Version control and project documentation |

---

## 🔍 Insights & Observations (Based on EDA Results)

### 🧾 Customer Insights
- **High-Value Customers:** A small group of repeat customers contributes a significant share of total revenue. Customers such as *Save-a-lot Markets* and *Ernst Handel* appear among the top spenders, showing strong repeat ordering behavior.  
- **Order Patterns:** Customers in *Germany, USA, and UK* have the highest order volumes. European customers generally place more frequent but smaller orders, while North American customers place fewer, higher-value orders.  
- **Customer Segments:** There are clear clusters of customers based on total spend and order count — with “high spenders” representing about 15–20% of customers but contributing nearly 60% of sales.

---

### 👩‍💼 Employee Insights
- **Geographic Distribution:** Employees are concentrated in *Seattle, London, and Tacoma*, the company’s key operational hubs.  
- **Title-wise Spread:** Most employees hold sales-related titles such as *Sales Representative* or *Sales Manager*, with fewer in administrative or logistics roles.  
- **Hire Trends:** Hiring peaked in the mid-1990s, indicating a period of expansion and market growth.

---

### 📦 Product & Sales Insights
- **Demand Patterns:** Sales are strongest in *Q2 and Q4*, reflecting clear seasonality tied to holiday demand cycles.  
- **Top Categories:** *Beverages* and *Confections* dominate total sales, while *Seafood* and *Meat/Poultry* maintain consistent but moderate performance.  
- **Stock vs. Sales:** Products with moderate prices and steady stock levels (e.g., *Chai*, *Chang*) perform better than very high-priced or low-stock items.  

---

### 🚚 Supplier Insights
- **Supplier Distribution:** Most suppliers are based in *Western Europe* and *North America*. A few in *Japan* and *Australia* contribute premium-priced goods.  
- **Pricing Trends:** European suppliers typically offer mid-range products, while North American suppliers specialize in high-value, niche categories.  
- **Category Link:** Suppliers of *Beverages* and *Condiments* are the most common — aligning with the top-performing sales categories.

---

### 💡 Overall Summary
- The company has a **loyal base of high-value customers**, **strong category concentration**, and a **balanced supplier network**.  
- There’s clear **seasonality in demand**, particularly in Q2 and Q4.  
- Employee distribution aligns with market hubs, supporting efficient sales coverage.  
- Opportunities exist to **expand in underrepresented regions** and **optimize stock management** for high-turnover items.

---

## 🖼️ Power BI Dashboard
A Power BI dashboard was developed to visually complement the Excel analysis.  
It includes:
- Sales trends over time  
- Top customers and products  
- Category-wise revenue breakdowns  
- Employee and supplier distributions  

*(Dashboard visuals can be found in the `/images` folder.)*

---

## 🚀 Project Structure
northwind-traders-analytics/
│
├── README.md
│
├── data/
│
├── reports/
│ ├── Northwindeda.xlsx
│ └── northwindfinalproject.pbix
│
├── images/
│ ├── dashboard_overview.png
│ ├── sales_trends.png
│ ├── customer_distribution.png
│ └── category_sales.png
│
└── .gitignore (optional)

---

## 📈 Impact

This analysis provides a holistic view of Northwind Traders’ business operations and highlights key insights for decision-making.  
It demonstrates how combining **SQL querying**, **Excel EDA**, and **Power BI** visualization can uncover trends and inform strategic actions.

---

## 🧑‍💻 Author

**Uday Sheoran**  
📧 [udaysheoran2000@gmail.com](mailto:udaysheoran2000@gmail.com)  
💼 [LinkedIn](https://www.linkedin.com/in/uday-sheoran-a022b6227/)  
📂 GitHub: [Uday-Sheoran](https://github.com/Uday-Sheoran)

---

## 🏁 Conclusion

This project showcases how a full data pipeline — from **SQL data extraction** to **Excel-based EDA** and **Power BI visualization** — can transform raw business data into actionable intelligence.  
It emphasizes analytical thinking, storytelling, and the ability to extract value from multi-dimensional datasets.

---


