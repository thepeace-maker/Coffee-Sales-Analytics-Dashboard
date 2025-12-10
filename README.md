# ☕ Coffee Sales Analytics Dashboard

### **Power BI Business Intelligence Project**

## 📌 **Project Overview**

This project analyzes sales performance across multiple coffee product
categories, stores, and time periods.
The dashboard provides a complete view of **revenue**, **transactions**,
**customer behavior**, and **top-selling products**, enabling
data-driven decisions for optimizing sales and operations.

## 📊 **Dashboard Pages**

### **1️⃣ Dashboard Page**

This page highlights overall business performance with key metrics:

-   **Total Revenue:** $263.36K
-   **Total Transactions:** 58K
-   **Avg Bill Value:** $4.52
-   **Total Days Opened:** 72

**Visuals include:** - Top 10 selling coffee products
- Sales by day of week
- Monthly sales trend
- Sales by time period (Morning/Afternoon/Evening)
- Top selling product categories



### **2️⃣ Insights Page**

A detailed table view showing product-level performance across time
periods:

-   Morning Sales
-   Afternoon Sales
-   Evening Sales



## 🧩 **Key Features**

-   Interactive slicers:
    -   Store
    -   Category
    -   Product Type
-   Dynamic revenue & sales insights
-   Clean and customized theme (coffee-themed UI)
-   DAX-powered KPIs
-   Time-based sales segmentation

## 🛠 **Tools Used**

-   Power BI Desktop
-   Power Query
-   DAX
-   Data Modeling (Star Schema)

## 🔧 **Sample DAX Measures**

    Total Revenue = SUM('Sales'[Revenue])
    Total Transactions = SUM('Sales'[Transactions])
    Avg Bill Value = DIVIDE([Total Revenue], [Total Transactions])
    Morning Sales = CALCULATE([Total Revenue], 'Sales'[Time Period] = "Morning")



## 📈 **Insights Summary**

-   Coffee category remains the strongest revenue driver.
-   Sales peak in the Afternoon.
-   Jamaican and Ethiopia coffee rank among top-selling products.
-   Revenue shows seasonal fluctuations.

## 🚀 **How to Use**

1.  Download the PBIX file.
2.  Open in Power BI Desktop.
3.  Refresh data.

## 📫 **Author**

**Abdulsalam Musediq**
Data Analyst | Power BI | SQL | Python
