# Power BI Sales Analytics Dashboard

## Overview
This project presents an interactive **Power BI sales analytics dashboard** designed to analyze global sales performance across multiple business dimensions. The dashboard enables dynamic exploration of sales trends, customer behavior, and profitability through an intuitive multi-page interface.

Using an Excel dataset containing **2,100+ transaction records**, this project demonstrates end-to-end business intelligence development including **data modeling, data transformation, KPI creation, and interactive visualization**.

---

## Key Features

The Power BI report contains four interactive analysis pages:

- **Dashboard** – High-level overview of seasonal sales trends, country-level sales distribution, and annual performance comparison.
- **Sales Analysis** – KPI tracking for sales representatives including margin %, order volume, and average order value.
- **Details** – Deep-dive analysis with drill-down capability across customers, orders, and product-level performance.
- **Product Details** – Transaction-level product performance analysis.

---

## Interactive Business Insights
The dashboard allows users to dynamically analyze performance across key business dimensions:

- Time (Year, Month)
- Country
- Customer
- Product
- Salesperson

Interactive slicers enable users to filter results and drill down from summary insights to detailed transaction-level analysis.

---

## Key KPIs Implemented
The dashboard tracks multiple business performance metrics using custom **DAX measures**:

- **Total Sales**
- **Margin**
- **Margin Percentage**
- **Order Count**
- **Average Order Value**
- **Minimum Sale**
- **Maximum Sale**
- **Total Quantity**

A **margin target gauge (20%)** was implemented to visually evaluate sales performance against profitability goals.

---

## Data Model
The project uses a **star schema data model** designed for efficient analytics.

Tables included:

- **Orders** – Transaction-level sales data
- **Customers** – Customer information and geographic attributes
- **Employees** – Sales representative details

Relationships were created using primary keys such as `CustomerID` and `EmployeeID` to enable efficient filtering and aggregation across the model.

---

## Data Transformation
Data preparation was performed using **Power Query**, including:

- Creating derived time attributes (Year, Month, Month Index)
- Calculating order-level **margin values**
- Creating a **Large Sale Flag** for high-value transactions
- Cleaning and transforming Excel source data for analysis

---

## Visualizations Used
The dashboard includes multiple interactive visuals:

- KPI Cards
- Seasonal Sales Bar Chart
- Country Sales Pie Chart
- Annual Sales Trend Line Chart
- Margin Performance Chart
- Customer Sales Treemap
- Margin Target Gauge
- Order Details Table

These visualizations support both **executive-level summaries and detailed operational analysis**.

---

## Tools & Technologies

- **Power BI Desktop**
- **DAX (Data Analysis Expressions)**
- **Power Query**
- **Microsoft Excel (Data Source)**

---

## Example Insights Enabled

The dashboard enables users to quickly answer questions such as:

- Which countries generate the highest revenue?
- How does seasonal demand fluctuate across months?
- Which sales representatives exceed the margin target?
- Which customers generate the highest average order value?
- What products drive the largest sales volumes?

---

