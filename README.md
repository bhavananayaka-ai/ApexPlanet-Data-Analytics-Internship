# Task 3: Deep-Dive Analysis & Interactive Dashboarding

## Customer Segmentation & Sales Performance Dashboard

### 1. Project Overview

This project is part of my **60-Day Data Analytics Internship at ApexPlanet Software Pvt. Ltd.**

The main objective of this task is to perform an in-depth analysis of sales data, identify customer purchasing patterns, define important Key Performance Indicators (KPIs), and develop an interactive dashboard to support business decision-making.

This project uses **RFM (Recency, Frequency, Monetary) analysis** to segment customers based on their purchasing behavior and analyze sales performance across different categories, products, cities, and time periods.

### 2. Project Objectives

- Define and calculate important business KPIs.
- Perform customer segmentation using RFM analysis.
- Identify high-value, loyal, recent, and at-risk customers.
- Analyze revenue trends over time.
- Compare sales performance across products, categories, and cities.
- Develop an interactive dashboard using Microsoft Power BI.
- Generate actionable business insights from the analysis.

### 3. Tools and Technologies

- **Python** – Data analysis and processing
- **Pandas** – Data cleaning, transformation, and aggregation
- **NumPy** – Numerical calculations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualization
- **Google Colab** – Python notebook development
- **Microsoft Power BI** – Interactive dashboard development
- **Microsoft Excel** – Report preparation
- **GitHub** – Project version control and portfolio management

### 4. Dataset Description

The project uses a sales transaction dataset containing information about orders, customers, products, and sales.

The dataset includes the following fields:

| Column | Description |
|---|---|
| Order_ID | Identifier for an order |
| Order_Date | Date of the transaction |
| Customer_ID | Unique customer identifier |
| Customer_Name | Customer name |
| Gender | Customer gender |
| Age | Customer age |
| City | Customer location |
| Product | Product purchased |
| Category | Product category |
| Quantity | Number of units purchased |
| Unit_Price | Price per unit |
| Total_Sales | Total sales amount |

The data is prepared for analysis by handling missing values, standardizing data types, removing exact duplicate rows, validating sales calculations, and creating date-related columns.

### 5. Key Performance Indicators (KPIs)

The following KPIs are used to evaluate business and sales performance.

| KPI | Formula | Purpose |
|---|---|---|
| Total Revenue | Sum of Total_Sales | Measures overall sales revenue |
| Unique Orders | Distinct count of Order_ID | Measures the number of unique orders |
| Average Order Value | Total Revenue / Unique Orders | Measures average revenue per unique order |
| Average Units per Transaction | Total Quantity / Number of Transaction Rows | Measures average units sold per transaction row |
| Repeat-Customer Rate | Customers with 2 or more transaction rows / Total Customers × 100 | Measures customer repeat-purchase behavior |

These KPIs help evaluate revenue generation, transaction activity, purchasing behavior, and customer retention.

### 6. Customer Segmentation Using RFM Analysis

RFM analysis is used to understand customer purchasing behavior through three metrics.

- **Recency:** Number of days since the customer's most recent purchase.
- **Frequency:** Number of transaction records associated with the customer.
- **Monetary:** Total sales value associated with the customer.

Customers receive scores based on these metrics and are assigned to segments using a rule-based approach.

The analysis uses the day after the latest transaction date as the reference date for calculating recency.

#### Customer Segments

- **Champions:** Recent customers with high purchase frequency and spending scores.
- **Loyal Customers:** Customers with relatively strong recency and frequency scores.
- **Recent Customers:** Customers with recent purchases but comparatively low frequency scores.
- **At Risk:** Customers with lower recency scores but relatively strong frequency scores.
- **Needs Attention:** Customers with lower recency and frequency scores.
- **Potential Loyalists:** Customers who do not fit the other defined segment rules and may have potential for further engagement.

### 7. Analysis Performed

The project includes the following analytical activities:

1. Data inspection and preparation.
2. KPI calculation and business interpretation.
3. Customer-level RFM metric calculation.
4. Customer scoring and segment assignment.
5. Customer distribution analysis by segment.
6. Revenue contribution analysis by customer segment.
7. Monthly revenue trend analysis.
8. Product, category, and city-level sales analysis.
9. Data visualization to communicate key patterns.
10. Preparation of outputs for an interactive Power BI dashboard.

### 8. Interactive Dashboard

The dashboard is developed using Microsoft Power BI to provide an interactive view of sales performance and customer segments.

**Planned dashboard components:**

- KPI cards for total revenue, unique orders, average order value, average units per transaction, and repeat-customer rate.
- Customer count by segment.
- Revenue contribution by customer segment.
- Monthly revenue trend.
- Customer RFM scatter plot.
- Slicers for year, city, product category, and customer segment, where supported by the data model.

The dashboard allows users to explore sales performance and compare customer segments using filters.

**Live Dashboard:** Add your published Power BI dashboard link here after publishing and verifying access.

### 9. Repository Contents

This folder contains the following project deliverables, where available:

- `ApexPlanet_Task3_Customer_Segmentation.ipynb` – Python analysis notebook.
- `ApexPlanet_Task3_Cleaned_Sales.csv` – Prepared sales dataset.
- `ApexPlanet_Task3_Customer_Segments.csv` – Customer-level RFM metrics and segment labels.
- `ApexPlanet_Task3_KPI_Summary.csv` – KPI definitions, formulas, and business rationale.
- `ApexPlanet_Task3_Segment_Summary.csv` – Customer segment summary.
- `ApexPlanet_Task3_Deep_Dive_Report.xlsx` – Consolidated analytical report.
- `ApexPlanet_Task3_Customer_Segmentation.pbix` – Power BI dashboard file.
- `Task3_Customers_by_Segment.png` – Customer distribution visualization.
- `Task3_Revenue_by_Segment.png` – Revenue by customer segment.
- `Task3_RFM_Scatter.png` – RFM relationship visualization.
- `Task3_Monthly_Revenue.png` – Monthly revenue trend.

*Note: Include only the files you have generated and uploaded. File names may be adjusted to match your final deliverables.*

### 10. Expected Business Benefits

This analysis can help a business:

- Identify high-value customers and understand their contribution to revenue.
- Recognize customers who may need retention campaigns.
- Understand repeat-purchase behavior.
- Monitor monthly sales performance.
- Identify products and categories contributing to revenue.
- Compare performance across cities.
- Make more informed marketing and customer engagement decisions.

These are potential uses of the analysis; actual findings should be based on the calculated results from the dataset.

### 11. Methodology and Limitations

- Customer segmentation uses rule-based RFM scoring rather than machine learning clustering.
- Recency is calculated relative to the latest date in the dataset, not the current date.
- Frequency is based on transaction records, so repeated order IDs may affect order-related metrics.
- Unique Orders is calculated using the distinct count of `Order_ID`.
- High sales values are not automatically removed because they may represent valid transactions.
- KPI values and business conclusions should be interpreted using the actual analysis outputs.
- The dashboard's availability depends on publishing permissions and access settings.

### 12. Project Outcome

This project demonstrates the application of Python-based data analysis, RFM customer segmentation, KPI development, business reporting, data visualization, and interactive dashboard design.

It provides a structured approach to understanding customer behavior and sales performance using data analytics tools.

### 13. Internship Information

**Internship:** 60-Day Data Analytics Internship  
**Organization:** ApexPlanet Software Pvt. Ltd.  
**Task:** Task 3 – Deep-Dive Analysis & Interactive Dashboarding  
**Project:** Customer Segmentation & Sales Performance Dashboard  
**Intern:** Bhavana V

---

*Developed as part of the ApexPlanet Data Analytics Internship.*


