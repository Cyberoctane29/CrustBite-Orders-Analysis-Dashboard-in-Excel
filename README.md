# CrustBite Orders Analysis Dashboard in Excel - An Interactive Analysis of Order Performance, Revenue Trends & Discount Insights

## **Introduction**

This project is an interactive Excel dashboard built to analyze CrustBite’s sales performance across daily sales trends, sales amount buckets, products, and regions. By combining overall sales and average sales analysis, transaction-value distribution, sales volume across price buckets, and product-level performance comparisons, the dashboard provides a comprehensive view of sales activity and revenue patterns. Interactive **Slicers**, **PivotTables**, and **PivotCharts** enable dynamic filtering and exploration of regional sales performance, while multiple visualizations highlight sales distribution, transaction volume, product performance, and time-based trends. Designed with a clean and structured layout, the dashboard transforms sales data into clear, interactive, and accessible insights for understanding sales patterns and supporting data-driven business decisions.

![CrustBite Orders Analysis Dashboard](Image%20-%20CrustBite%20Orders%20Analysis%20Dashboard%20in%20Excel/CrustBite%20Orders%20Analysis%20Dashboard%20-%20Slicer%20State%201.png)

### Access the Dashboards

If you’d like to directly explore the interactive dashboards and project files, you can access them here:

[Google Drive link](https://drive.google.com/drive/u/0/folders/1eIdEI5kJ3qlnkdv6xZD-sawrl3oyT96H) : https://drive.google.com/drive/u/0/folders/1eIdEI5kJ3qlnkdv6xZD-sawrl3oyT96H

[Interactive dashboard video walkthrough](https://drive.google.com/file/d/1YpLi5Sjanp8F-Qyvnv9d_TC7lA05h1wc/view): https://drive.google.com/file/d/1YpLi5Sjanp8F-Qyvnv9d_TC7lA05h1wc/view

For the complete project details, including dataset context, analysis workflow, and documented insights, continue with this repository.

## **Project Overview**

The **CrustBite Orders Analysis Dashboard** project aims to:

* **Monitor Order Performance**: Track total orders, total revenue, average revenue, and average discount amounts to provide a comprehensive view of overall order and sales performance  
* **Analyze Product Performance**: Compare products based on the number of orders and revenue generated to identify differences in product-level performance  
* **Understand Discount Activity**: Examine discount amounts and discount usage across orders to understand how discounts are applied and how they relate to sales activity  
* **Explore Time-Based Order Trends**: Analyze daily order volumes and revenue generation to identify fluctuations, patterns, and changes in sales activity over the analysis period  
* **Examine Order Types**: Compare **Online** and **Physical Visit** orders to explore differences in order activity and sales performance  
* **Analyze Agent Performance**: Use agent-level filtering to explore order and revenue performance across individual sales agents  
* **Enable Interactive Analysis & Decision-Making**: Use **Slicers**, **PivotTables**, and **PivotCharts** to dynamically explore order performance by agent and order type, helping stakeholders identify product trends, revenue patterns, discount activity, and areas requiring further attention

## **Dataset Structure**

The project is built on an **Orders Dataset** containing individual order records along with product, pricing, discount, revenue, order type, and sales agent information. The dataset provides the foundation for analyzing order performance, revenue generation, product-level performance, discount activity, and order trends within the Excel dashboard.

**Orders Dataset:**  
Captures individual customer orders and their associated sales and order details. Key features include:

* `Order ID`: Unique identifier representing each order
* `Order Date`: Date on which the order was placed
* `Customer ID`: Identifier representing the customer associated with the order
* `Customer Name`: Name of the customer associated with the order
* `Product ID`: Identifier representing the product associated with the order
* `Product Name`: Product associated with the order
* `Price`: Price of the product associated with the order
* `No of Products in one Sale`: Number of products included in the order
* `Revenue before discount`: Revenue generated before applying the discount
* `Discount`: Discount percentage applied to the order
* `Revenue after discount`: Revenue generated after applying the discount
* `Discount Amount`: Difference between revenue before and after discount
* `Order Type`: Type of order, including **Online** and **Physical Visit**
* `Agent`: Sales agent associated with the order

The dataset combines order, customer, product, pricing, discount, revenue, order-type, and sales-agent information at the individual order level. The `Order Date` field supports daily order and revenue trend analysis, while `Product Name`, `No of Products in one Sale`, `Revenue before discount`, `Discount`, and `Revenue after discount` enable product, order-volume, discount, and revenue analysis within the Excel dashboard. The `Order Type` and `Agent` fields support interactive filtering and exploration of order performance across different sales channels and agents.

## **Dashboard Development & Analytical Workflow**

- **Defined Analytical Objectives**  
  Established the key analytical dimensions for evaluating CrustBite order performance, focusing on order volume, revenue generation, average revenue, discount activity, product performance, and order trends over time.

- **Data Preparation & Feature Engineering**  
  - Structured the underlying order data into an Excel table to support analysis and interactive reporting.
  - Organized order records across fields including order and customer details, products, pricing, revenue, discounts, order type, and agent information.
  - Prepared the dataset for dynamic aggregation, filtering, and analysis through Excel's table and PivotTable functionality.
  - Utilized the `Revenue after discount` and `Discount Amount` fields to support analysis of revenue performance and discount activity.

- **Pivot-Based Analytical Modeling**  
  - Developed PivotTables to calculate **total orders, total revenue, average revenue, and average discount** as key order-performance metrics.
  - Created product-level order analysis to compare the number of orders across different products.
  - Developed daily order trend analysis to examine changes in order volume throughout the analysis period.
  - Created daily revenue analysis to track changes in revenue generation over time.
  - Developed product-level revenue analysis to compare revenue performance across products.
  - Incorporated order-type analysis to enable comparison between **Online** and **Physical Visit** orders.
  - Structured supporting PivotTables to provide the analytical sources for the dashboard's charts, KPI elements, and visualizations.

- **Interactive Dashboard Construction**  
  - Designed a single-page **CrustBite Orders Dashboard** combining order KPIs, product-level order performance, daily order trends, daily revenue trends, and product revenue analysis.
  - Created multiple PivotCharts, including column charts and line charts, to present different aspects of order and revenue performance.
  - Added interactive **Agent** and **Order Type** slicers, enabling users to dynamically filter the dashboard by sales agent and order type.
  - Applied a clean and structured layout with clearly separated visualization panels, KPI-style summary elements, consistent chart formatting, whitespace, and a cohesive blue-gray visual theme.

- **Interactive Filtering & Dynamic Reporting**  
  - Connected the **Agent** and **Order Type** slicers to relevant PivotTables and PivotCharts to ensure that dashboard metrics and visualizations respond dynamically to user selections.
  - Enabled users to explore changes in total orders, revenue, average revenue, average discount, product performance, and daily trends based on selected agents and order types.
  - Designed the dashboard to support both an overall view of CrustBite order performance and focused analysis of specific order-type and agent segments.

- **Dashboard Validation & Presentation**  
  - Tested the dashboard across different Agent and Order Type slicer selections to ensure that charts and analytical summaries updated consistently.
  - Validated order counts, revenue totals, average revenue, average discount, product-level metrics, and daily trends against the underlying PivotTables.
  - Organized the workbook into four functional worksheets: **Orders Data**, **Dashboard Business Questions**, **Orders Pivot Sheet**, and **Orders Dashboard**, separating the raw data, analytical questions, supporting PivotTable analysis, and final dashboard presentation.

## **Dashboard Previews**  

### CrustBite Orders Dashboard - Slicer State 1

![CrustBite Orders Dashboard - Slicer State 1](Image%20-%20CrustBite%20Orders%20Analysis%20Dashboard%20in%20Excel/CrustBite%20Orders%20Analysis%20Dashboard%20-%20Slicer%20State%201.png)

### CrustBite Orders Dashboard - Slicer State 2

![CrustBite Orders Dashboard - Slicer State 2](Image%20-%20CrustBite%20Orders%20Analysis%20Dashboard%20in%20Excel/CrustBite%20Orders%20Analysis%20Dashboard%20-%20Slicer%20State%202.png)

### CrustBite Orders Dashboard - Slicer State 3

![CrustBite Orders Dashboard - Slicer State 3](Image%20-%20CrustBite%20Orders%20Analysis%20Dashboard%20in%20Excel/CrustBite%20Orders%20Analysis%20Dashboard%20-%20Slicer%20State%203.png)

### CrustBite Orders Dashboard - Slicer State 4

![CrustBite Orders Dashboard - Slicer State 4](Image%20-%20CrustBite%20Orders%20Analysis%20Dashboard%20in%20Excel/CrustBite%20Orders%20Analysis%20Dashboard%20-%20Slicer%20State%204.png)

## **Key Insights**

### **Overall Order & Revenue Performance**
- **Strong Order Activity**: The dashboard records **794 total orders** across the analysis period, generating approximately **₹2.40 lakh in total revenue** in the overall dashboard view.
- **Average Revenue per Order**: The overall average revenue is approximately **₹301.65 per order**, providing a view of the typical revenue generated from an individual order.
- **Stable Average Revenue Across Filter States**: Average revenue remained relatively consistent across the different dashboard selections, ranging from approximately **₹301.65 to ₹309.00**.
- **Consistent Discount Amounts**: The average discount amount remained relatively stable across the dashboard views, ranging from approximately **-₹245.94 to -₹250.33**, reflecting the workbook's calculation of discount amount as the difference between revenue after and before discount.
- **Order-Type Distribution**: The overall order activity is relatively balanced between **Online and Physical Visit** orders, with Online orders accounting for **403 orders** and Physical Visit orders accounting for **391 orders**.

### **Product Performance**
- **Paneer Tikka Pizzabun Leads Order Volume**: **Paneer Tikka Pizzabun** was the most frequently ordered product with **174 orders**, followed closely by **Crispy Chole Pizzabun and Large Paneer Tikka Pizzabun**, with **173 orders each**.
- **Medium Crispy Chole Pizzabun Shows Strong Order Activity**: **Medium Crispy Chole Pizzabun** recorded **169 orders**, placing it close to the three highest-volume products.
- **Lower Order Volume for Minty and Aloo Shots**: **Minty Pizzabun** recorded **70 orders**, while **Aloo Shots Pizzabun** recorded **35 orders**, considerably fewer than the other products.
- **Product Revenue Variation**: Revenue performance differs across products, with **Paneer Tikka Pizzabun, Large Paneer Tikka Pizzabun, and Medium Crispy Chole Pizzabun** contributing substantial revenue alongside their relatively high order volumes.
- **Revenue and Order Volume Comparison**: The product comparison chart highlights differences between the number of orders and revenue generated, allowing products to be evaluated from both order-volume and revenue perspectives.

### **Time-Based Order & Revenue Trends**
- **Daily Order Fluctuations**: The number of orders varied considerably across individual dates, with periods of higher activity followed by lower-volume periods throughout the June–September analysis period.
- **Peak Daily Order Activity**: The highest daily order volume reached approximately **34 orders**, occurring around **22 June**, followed by several other notable peaks during late June and July.
- **Higher Order Activity in the Earlier Period**: The daily order trend shows greater volatility and several higher peaks during **June and July**, while order volumes generally became lower and more stable during much of August and September.
- **Daily Revenue Fluctuation**: Revenue generated per day also varied substantially throughout the analysis period, with several pronounced peaks during June and July.
- **Peak Daily Revenue**: The highest daily revenue reached approximately **₹12,600**, occurring around **22 June**, coinciding with the highest daily order volume.
- **Revenue Variation Over Time**: The daily revenue chart highlights substantial fluctuations in sales generation, with periods of higher revenue interspersed with lower-revenue days across the analysis period.

### **Order Type & Agent Analysis**
- **Balanced Order-Type Activity**: Online and Physical Visit orders show relatively similar overall volumes, with **Online orders (403)** slightly exceeding **Physical Visit orders (391)**.
- **Variation in Revenue by Order Type**: The dashboard's interactive Order Type slicer allows revenue, order volume, product performance, and daily trends to be examined separately for **Online** and **Physical Visit** orders.
- **Agent-Level Order Distribution**: Across the overall dataset, order volumes were distributed across **Adrien Martin (259 orders), Albain Forestier (259 orders), and Roch Cousineau (276 orders)**.
- **Interactive Agent Exploration**: The Agent slicer enables users to examine how total orders, revenue, average revenue, discount amounts, product performance, and daily trends change for individual agents or selected combinations of agents.
- **Filter-Dependent Performance Patterns**: The different slicer states demonstrate that order volume, revenue, product-level order counts, and daily trends change depending on the selected **Agent** and **Order Type**, enabling more focused analysis of specific order segments.

### **Interactive & Business Analysis**
- **Dynamic Order Performance Analysis**: The combination of KPI cards, product comparisons, daily order trends, and daily revenue trends provides a consolidated view of CrustBite's order performance.
- **Product-Level Exploration**: The product comparison visualization allows users to examine both **revenue generated and number of orders** across six products within a single view.
- **Interactive Filtering**: The **Agent** and **Order Type** slicers enable users to move from the overall order picture to more focused analysis of specific agents and sales channels.
- **Order Volume vs. Revenue Analysis**: Comparing daily order counts with daily revenue provides visibility into how changes in order activity correspond with changes in revenue generation.
- **Business Decision Support**: Combining order KPIs, product performance, order-type analysis, agent-level filtering, and time-based trends provides a structured view of CrustBite's sales activity and highlights areas for further investigation.

## **Project Highlights**

* Developed a **fully interactive Excel orders dashboard** to provide a consolidated view of order performance, revenue generation, product performance, discount activity, and daily sales trends.
* Adopted a **question-driven analytical approach**, using **PivotTables, PivotCharts, Slicers, and supporting calculations** to transform raw order data into an interactive reporting solution.
* Analyzed **overall order performance** through total orders, total revenue, average revenue, and average discount amount to provide a comprehensive view of order and sales activity.
* Built **product-level order analysis** to compare the number of orders and revenue generated across six products, highlighting differences in product-level performance.
* Developed **daily order trend analysis** to examine fluctuations in order volume throughout the June–September analysis period.
* Created **daily revenue trend analysis** to track changes in revenue generation and identify periods of higher and lower sales activity over time.
* Implemented **interactive filtering through Agent and Order Type Slicers**, allowing users to dynamically explore order performance across individual agents and **Online** and **Physical Visit** order types.
* Developed **comparative product visualizations** combining revenue generated and number of orders to provide a broader perspective on product-level order and revenue performance.
* Incorporated **discount analysis** through average discount amount as a KPI, providing visibility into discount activity alongside overall order and revenue performance.
* Designed a **single-page interactive dashboard** combining KPI analysis, product comparisons, order trends, revenue trends, agent filtering, and order-type filtering within a structured reporting layout.
* Applied a **clean and consistent visual design** with structured visualization panels, KPI-style summary elements, interactive filter controls, annotations, whitespace, and a cohesive blue-gray visual theme for intuitive exploration.
* Delivered a **scalable Excel-based analytical solution** that connects structured data preparation, PivotTable-based analysis, interactive filtering, visualization, and reporting within a single workbook.

This project demonstrates how **Microsoft Excel can be used to build an interactive orders and sales analysis dashboard**, combining PivotTables, PivotCharts, Slicers, and structured analytical workflows to transform transactional order data into an accessible and decision-oriented reporting solution.
