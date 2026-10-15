# Swiggy Food Order Sales & Customer Analytics Dashboard

An Excel-based Data Analyst project that transforms Swiggy food-order data into KPIs, analytical views, charts, and an interactive dashboard.

## Project Objective

The objective of this project is to analyze food-order sales and customer-related patterns and present the results in a clear, interactive Excel dashboard.

The project focuses on:

- Sales performance
- Monthly, weekly and daily trends
- Veg vs Non-Veg sales contribution
- State-wise and city-wise performance
- Quarterly performance
- Customer ratings and rating counts
- KPI development
- Interactive filtering with slicers and a timeline

## Dataset

The workbook contains approximately 197,430 records across fields related to:

- State
- City
- Order Date
- Day
- Quarter
- Week
- Restaurant Name
- Location
- Category
- Dish Name
- Food Type
- Price (INR)
- Rating
- Rating Count

## Tools & Techniques

**Tools**
- Microsoft Excel
- Power Query

**Excel techniques**
- Data cleaning and validation
- Excel Tables
- Formulas and calculated metrics
- PivotTables
- PivotCharts
- KPI cards
- Slicers
- Timeline
- Dashboard design

## Project Workflow

```text
Raw Data
   ↓
Data Preparation / Power Query
   ↓
Analytical Tables
   ↓
KPIs + PivotTables
   ↓
Charts / PivotCharts
   ↓
Interactive Dashboard
   ↓
Business Insights
```

## Key KPIs

The project includes metrics such as:

- Total Sales
- Average Rating
- Total Rating Count
- Record Count
- Average Value per Record

> Note: The source dataset does not contain an explicit unique Order ID. Therefore, record-based order metrics should be interpreted carefully and should not automatically be treated as distinct-order metrics.

## Key Analysis

### 1. Monthly Sales Trend
Used to understand how sales change over the available months.

### 2. Food Type Analysis
Compares sales contribution from Vegetarian and Non-Vegetarian food types.

### 3. Geographic Analysis
Identifies major states and cities contributing to sales.

### 4. Day-of-Week Analysis
Compares sales across weekdays and weekends.

### 5. Quarterly Analysis
Compares sales across available quarters while considering incomplete periods.

### 6. Top 5 Cities
Highlights the highest-sales cities in the dataset.

## Dashboard

The dashboard combines:

- KPI cards
- Interactive slicers
- Date timeline
- Monthly sales trend
- Food-type analysis
- Geographic analysis
- City ranking
- Supporting analytical charts

Screenshots are available in the `screenshots/` folder.

## Important Data Limitations

- No explicit unique Order ID is available in the source dataset.
- Average Value per Record should not automatically be interpreted as true Average Order Value.
- The available time period does not represent a complete full-year dataset, so incomplete quarters should be interpreted carefully.
- Rating Count should be treated as the supplied rating-count measure unless the source documentation confirms its exact definition.

## Files

```text
Swiggy_Food_Order_Analytics_Dashboard.xlsx
docs/
└── Swiggy_Food_Order_Analytics_Project_Report.docx

screenshots/
├── dashboard_overview.png
├── dashboard_detail.png
├── monthly_sales.png
├── food_type_sales.png
└── top_cities.png
```

## How to Use

1. Download `Swiggy_Food_Order_Analytics_Dashboard.xlsx`.
2. Open it in Microsoft Excel desktop.
3. Review the `Data`, `Analysis`, and `Dashboard` sheets.
4. Use the slicers and timeline to explore the dashboard.
5. Refresh Power Query/PivotTables when the underlying source data is updated.

## Portfolio Description

**Swiggy Food Order Sales & Customer Analytics Dashboard | Excel**

Built an interactive Excel analytics solution for Swiggy food-order data using data preparation, Power Query, PivotTables, PivotCharts, KPI calculations, slicers, timelines and dashboard design. Analyzed sales trends, food-type contribution, geographic performance, city rankings, customer ratings and quarterly patterns, while documenting important data-quality and metric-definition limitations.

## Author

**Saranga Abhishek**
