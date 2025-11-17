📊 Blinkit Sales Performance Dashboard – Power BI

This project is an interactive Power BI Sales Analytics Dashboard built for Blinkit, providing deep insights into product performance, outlet behavior, and overall business sales trends. It helps business users understand KPIs, compare outlet performance, analyze product categories, and make data-driven decisions.

🚀 Project Overview

The Blinkit Sales Dashboard combines multiple datasets related to items, outlets, and sales to present:

- Total Sales

- Average Sales

- Number of Items

- Average Customer Rating

- Outlet Size & Location Performance

- Item Category Sales Contribution

- Trends in Outlet Establishment

This dashboard is fully interactive with slicers and navigation buttons to enhance user experience.

📌 Key Features

🔹 1. KPI Summary Cards

  - Total Sales: $1.20M

  - Avg Sales: $141

  - No of Items: 8523

  - Avg Rating: 3.9

🔹 2. Filter Panel

Users can slice the data by:

  - Outlet Location Type

  - Outlet Size

Item Type

🔹 3. Sales Trend Visualization

  - A year-over-year line chart showing outlet establishment and revenue growth from 2010 to 2020.

🔹 4. Item Category Analysis

  - Top Item Types (Fruits, Snacks, Household, Dairy, etc.)

  - Fat Content contribution (Low Fat vs Regular)

🔹 5. Outlet Insights

Visualization includes:

  - Sales by Outlet Size (Small, Medium, High)

  - Sales by Outlet Location (Tier 1, Tier 2, Tier 3)

Outlet Type Comparison Table with:

  - Total Sales

  - Number of Items

  - Average Sales

  - Average Rating

  - Item Visibility

🧠 DAX Measures Used :
  - Total Sales = SUM(Sales[Item_Outlet_Sales])

  - Avg Sales = AVERAGE(Sales[Item_Outlet_Sales])

  - No Of Items = DISTINCTCOUNT(Items[Item_Identifier])

  - Avg Rating = AVERAGE(Items[Item_Fat_Content])

🗂️ Data Model

The report uses a simple Star Schema:

- Fact Table: Sales

- Dimension Tables:

  - Items

  - Outlets

Relationships:

- Items → Sales (1:* )

- Outlets → Sales (1:* )

🛠️ Tools & Technologies

- Power BI Desktop

- DAX

- Power Query (ETL)

- Data Modeling

- Visualization & UI/UX Design

📸 Dashboard Screenshot

<img width="1241" height="835" alt="image" src="https://github.com/user-attachments/assets/77ed0a75-38d9-4a99-901c-90b4f90c75b4" />


⭐ Conclusion

This Power BI dashboard provides a complete 360° view of Blinkit's sales insights by combining product, outlet, and customer information. It enables business stakeholders to make smarter decisions about inventory, marketing, and outlet expansion.
