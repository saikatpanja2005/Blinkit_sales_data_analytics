# Blinkit Sales Data Analytics Dashboard

## 📊 Project Overview

This project is a **Blinkit Sales Data Analytics Dashboard** developed
in **Microsoft Power BI** to analyze grocery and outlet sales
performance through interactive visualizations.

The dashboard provides a consolidated view of key business metrics and
allows users to explore sales based on:

-   Outlet location
-   Outlet size
-   Outlet type
-   Item type
-   Fat content
-   Outlet establishment year
-   Item visibility
-   Average rating
-   Number of items
-   Total sales

The objective of this project is to transform sales data into meaningful
business insights using **data cleaning, data modeling, DAX
calculations, filtering, and interactive Power BI visualizations**.

------------------------------------------------------------------------

## 🎯 Project Objectives

The main objectives of this dashboard are:

1.  Analyze overall sales performance.
2.  Understand sales distribution across different outlet types.
3.  Compare outlets based on their size and location tier.
4.  Analyze the contribution of different item categories.
5.  Compare Low Fat and Regular fat-content products.
6.  Analyze outlet establishment trends over the years.
7.  Track the number of items and average item sales.
8.  Analyze average customer ratings.
9.  Provide interactive filters for business analysis.
10. Build an easy-to-understand dashboard for decision-making.

------------------------------------------------------------------------

## 🛠️ Tools & Technologies

  Tool / Technology              Purpose
  ------------------------------ -----------------------------------------
  **Microsoft Power BI**         Dashboard development and visualization
  **Power Query**                Data cleaning and transformation
  **DAX**                        Measures and calculations
  **Data Modeling**              Organizing data for analysis
  **Power BI Filters/Slicers**   Interactive data exploration
  **Charts & KPIs**              Business performance visualization

------------------------------------------------------------------------

## 📌 Key Performance Indicators

The dashboard displays the following major KPIs:

  KPI                           Value
  --------------------- -------------
  **Total Sales**         **\$1.20M**
  **Average Sales**         **\$141**
  **Number of Items**       **8,523**
  **Average Rating**          **3.9**

> **Note:** The currency symbols and values shown above are based on the
> uploaded dashboard design.

------------------------------------------------------------------------

## 📈 Dashboard Features

### 1. Total Sales

The Total Sales KPI provides an overview of the overall revenue
generated across the analyzed outlets and products.

**Displayed value:** \$1.20M

------------------------------------------------------------------------

### 2. Average Sales

This KPI represents the average sales value associated with the analyzed
items/outlets.

**Displayed value:** \$141

------------------------------------------------------------------------

### 3. Number of Items

The dashboard tracks the total number of items included in the analysis.

**Displayed value:** 8,523

------------------------------------------------------------------------

### 4. Average Rating

This KPI shows the average rating associated with the products/outlets.

**Displayed value:** 3.9

------------------------------------------------------------------------

## 📅 Outlet Establishment Analysis

The **Outlet Establishment** line/area chart analyzes sales performance
according to the outlet establishment year.

The visualization helps identify changes in sales across different
establishment periods.

Examples visible in the dashboard include:

-   2012: approximately \$78K
-   2014: approximately \$130K
-   2015: approximately \$132K
-   2016: approximately \$131K
-   2017: approximately \$133K
-   2018: approximately \$205K
-   2020: approximately \$129K
-   2022: approximately \$131K

This analysis can help understand how outlet establishment periods
relate to sales performance.

------------------------------------------------------------------------

## 🥛 Fat Content Analysis

The dashboard contains a donut chart showing sales distribution by **Fat
Content**.

The two categories analyzed are:

-   **Low Fat**
-   **Regular**

The visualization helps compare the contribution of different product
fat-content categories to total sales.

The dashboard shows approximately:

-   **Low Fat:** \$776.32K
-   **Regular:** \$425.36K

------------------------------------------------------------------------

## 🛒 Item Type Analysis

The **Item Type** chart compares sales across different grocery product
categories.

Categories displayed include:

-   Fruits and Vegetables
-   Snack Foods
-   Household
-   Frozen Foods
-   Dairy
-   Canned
-   Baking Goods
-   Health and Hygiene
-   Meat
-   Soft Drinks
-   Breads
-   Hard Drinks
-   Others
-   Starchy Foods
-   Breakfast
-   Seafood

This visualization helps identify which product categories contribute
more to overall sales.

------------------------------------------------------------------------

## 🏪 Fat Content by Outlet

The **Fat by Outlet** visualization compares Low Fat and Regular
products across different outlet location tiers:

-   Tier 1
-   Tier 2
-   Tier 3

This allows the user to compare the sales contribution of fat-content
categories across outlet locations.

------------------------------------------------------------------------

## 📏 Outlet Size Analysis

The dashboard includes an **Outlet Size** donut chart that divides
outlets into:

-   Small
-   Medium
-   High

The visualization helps analyze the relationship between outlet size and
sales/item volume.

The dashboard displays item counts of approximately:

-   Medium: 3.63K
-   Small: 3.14K
-   High: 1.75K

------------------------------------------------------------------------

## 📍 Outlet Location Analysis

The **Outlet Location** section analyzes sales by location tier:

-   Tier 1
-   Tier 2
-   Tier 3

The dashboard displays approximately:

  Location Tier         Sales
  --------------- -----------
  Tier 3            \$472.13K
  Tier 2            \$393.15K
  Tier 1            \$336.40K

This comparison helps understand how different location tiers contribute
to total sales.

------------------------------------------------------------------------

## 🏬 Outlet Type Analysis

The dashboard contains a detailed table comparing different outlet
types.

The analysis includes:

-   Total Sales
-   Number of Items
-   Average Sales
-   Average Rating
-   Item Visibility

Outlet types shown include:

-   Supermarket Type1
-   Supermarket Type2
-   Supermarket Type3
-   Grocery Store

The dashboard shows that **Supermarket Type1** has the largest sales
contribution among the displayed outlet types.

------------------------------------------------------------------------

## 🎛️ Interactive Filter Panel

The dashboard includes an interactive filter panel on the left side.

Users can filter the dashboard using:

### Outlet Location

Filter the analysis according to outlet location.

### Outlet Size

Filter outlets based on size.

### Item Type

Filter the dashboard by product category.

These filters allow users to dynamically explore different segments of
the sales data.

------------------------------------------------------------------------

## 📊 Dashboard Visualizations

The dashboard contains several visualization types:

-   KPI Cards
-   Line/Area Chart
-   Donut Charts
-   Bar Charts
-   Detailed Matrix/Table
-   Interactive Slicers

These visualizations provide both high-level KPIs and detailed business
analysis.

------------------------------------------------------------------------

## 🔄 Data Analysis Workflow

The project follows a typical business intelligence workflow:

``` text
Raw Sales Data
      ↓
Data Cleaning
      ↓
Data Transformation
      ↓
Data Modeling
      ↓
DAX Measures
      ↓
Power BI Visualizations
      ↓
Interactive Dashboard
      ↓
Business Insights
```

------------------------------------------------------------------------

## 🧹 Data Preparation

Data preparation can include the following Power Query operations:

-   Removing unnecessary columns
-   Handling missing values
-   Correcting data types
-   Renaming columns
-   Removing duplicate records
-   Standardizing categorical values
-   Creating calculated fields
-   Preparing data for visualization

------------------------------------------------------------------------

## 🧮 DAX & Calculations

The dashboard uses Power BI calculations/measures to generate important
metrics such as:

``` dax
Total Sales = SUM(Sales[Sales])
```

``` dax
Average Sales = AVERAGE(Sales[Sales])
```

``` dax
Total Items = COUNTROWS(Sales)
```

``` dax
Average Rating = AVERAGE(Sales[Rating])
```

> The exact DAX expressions may vary depending on the column names and
> data model used in the `.pbix` file.

------------------------------------------------------------------------

## 🔍 Business Questions Answered

This dashboard can help answer questions such as:

1.  What is the total sales generated?
2.  What is the average sales value?
3.  How many items are included in the analysis?
4.  What is the average rating?
5.  Which item categories generate higher sales?
6.  How do Low Fat and Regular products compare?
7.  Which outlet location tier generates higher sales?
8.  How does outlet size relate to item volume?
9.  How have sales changed according to outlet establishment year?
10. Which outlet type contributes the most sales?
11. How does item visibility vary between outlet types?
12. How do sales and ratings differ between outlet categories?

------------------------------------------------------------------------

## 💡 Key Insights From the Dashboard

Based on the displayed dashboard:

-   The dashboard reports **\$1.20M in total sales**.
-   The reported **average sales is \$141**.
-   The analysis contains **8,523 items**.
-   The reported **average rating is 3.9**.
-   Low Fat products contribute a larger displayed sales amount than
    Regular products.
-   The Item Type chart shows different levels of contribution across
    grocery categories.
-   Outlet Location Tier 3 shows approximately **\$472.13K** in
    displayed sales.
-   Outlet Location Tier 2 shows approximately **\$393.15K** in
    displayed sales.
-   Outlet Location Tier 1 shows approximately **\$336.40K** in
    displayed sales.
-   The outlet establishment chart shows variation in sales across
    establishment years.
-   Supermarket Type1 represents a major portion of the displayed
    outlet-type sales.

------------------------------------------------------------------------

## 🖥️ Dashboard Preview

The project dashboard includes:

-   A yellow Blinkit-style navigation/filter panel
-   KPI cards
-   Outlet establishment trend
-   Fat content analysis
-   Item type analysis
-   Fat by outlet analysis
-   Outlet size analysis
-   Outlet location analysis
-   Outlet type performance table

------------------------------------------------------------------------

## 📂 Recommended Project Files

A Kaggle/GitHub project can be organized as:

``` text
Blinkit-Sales-Data-Analytics/
│
├── Blinkit_Sales_Dashboard.pbix
├── Blinkit_Sales_Data.csv
├── README.md
│
└── screenshots/
    └── Blinkit_sales_data_analytics.png
```

### File Description

**`Blinkit_Sales_Dashboard.pbix`**\
Power BI dashboard/project file.

**`Blinkit_Sales_Data.csv`**\
Source dataset used for analysis, if available and permitted to share.

**`README.md`**\
Project documentation and dashboard description.

**`screenshots/Blinkit_sales_data_analytics.png`**\
Dashboard preview image.

------------------------------------------------------------------------

## 🚀 How to Use the Power BI Dashboard

1.  Download the `.pbix` file.
2.  Open it using Microsoft Power BI Desktop.
3.  Load or reconnect the source dataset if required.
4.  Refresh the data.
5.  Use the filter panel to select:
    -   Outlet Location
    -   Outlet Size
    -   Item Type
6.  Explore the charts and KPI cards.
7.  Select different visual elements to cross-filter the dashboard.

------------------------------------------------------------------------

## 📚 Skills Demonstrated

This project demonstrates practical skills in:

-   Data Analysis
-   Business Intelligence
-   Microsoft Power BI
-   Power Query
-   DAX
-   Data Cleaning
-   Data Transformation
-   Data Visualization
-   KPI Development
-   Interactive Dashboard Design
-   Business Reporting
-   Analytical Thinking

------------------------------------------------------------------------

## 🎓 Project Type

**Data Analytics / Business Intelligence Project**

**Domain:** Retail & Grocery Sales Analytics

**Primary Tool:** Microsoft Power BI

**Project Level:** Portfolio / Academic / Practice Project

------------------------------------------------------------------------

## 👨‍💻 Author

**Saikat Panja**

BCA Graduate \| Data Analytics & Web Development

### Areas of Interest

-   Data Analytics
-   Power BI
-   SQL
-   Python
-   Data Visualization
-   Web Development

------------------------------------------------------------------------

## ⭐ Conclusion

The Blinkit Sales Data Analytics Dashboard converts sales information
into an interactive business intelligence report. It combines KPI cards,
charts, filters, and detailed tables to provide a structured view of
outlet and product performance.

The project demonstrates how **Power BI, Power Query, DAX, and data
visualization techniques** can be used to analyze retail sales data and
present business information in an understandable format.

------------------------------------------------------------------------

## 📌 Disclaimer

This project is created for **educational, portfolio, and data analytics
practice purposes**. The dashboard design and displayed metrics are
based on the dataset used for the project and should not be interpreted
as official Blinkit business reporting.

------------------------------------------------------------------------

## 🔖 Tags

`Power BI` `Blinkit` `Sales Analysis` `Data Analytics`
`Business Intelligence` `Dashboard` `Power Query` `DAX`
`Data Visualization` `Retail Analytics` `Grocery Sales` `KPI Dashboard`
`Data Analysis`
