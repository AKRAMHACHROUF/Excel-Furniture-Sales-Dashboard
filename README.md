# 📊 Furniture Sales Dashboard in Excel

<img width="1233" height="601" alt="mapss" src="https://github.com/user-attachments/assets/4e131bd2-9e61-40d8-88e3-2b6f5987dbdb" />

<p align="center">
Interactive Excel Dashboard built with Microsoft Excel, Power Query, Pivot Tables, Pivot Charts, KPI Cards, Map Charts, and Slicers to analyze furniture sales performance and transform raw data into actionable business insights.
</p>

---

# 📖 Project Overview

This project demonstrates how Microsoft Excel can be transformed into a complete Business Intelligence (BI) solution.

Using Power Query, Pivot Tables, Pivot Charts, KPI Cards, Map Charts, and Interactive Slicers, this dashboard converts raw furniture sales data into meaningful visual insights that support business decision-making.

The dashboard enables users to analyze:

- 💰 Total Sales
- 📈 Total Profit
- 📦 Quantity Sold
- 🏷 Product Categories
- 🏙 Top Selling Cities
- 🗺 Sales by State
- 🚚 Shipping Modes
- ⏱ Shipping Duration
- 👥 Customer Segments

---

# 📷 Dashboard Preview

<img width="1239" height="601" alt="dashboard" src="https://github.com/user-attachments/assets/02d7a01f-4a05-4b8d-97cc-7f48142267b7" />

The dashboard provides an interactive overview of furniture sales performance, allowing users to explore sales, profitability, customer segments, regional performance, and shipping operations through dynamic visualizations.

---

# ❓ Business Questions

This dashboard was designed to answer important business questions, including:

- What are the Total Sales?
- What is the Total Profit?
- How many products were sold?
- Which month generated the highest sales?
- Which states generated the most revenue?
- Which cities contribute the highest sales?
- Which furniture category performs the best?
- Which shipping method is used most frequently?
- What is the average shipping duration?
- How do customer segments influence sales performance?

---

# 📂 Dataset Information

The dataset contains furniture sales transactions collected across different states in the United States.

Each transaction includes information about:

- Order ID
- Order Date
- Ship Date
- Ship Mode
- Customer ID
- Customer Name
- Segment
- Country
- City
- State
- Region
- Product ID
- Category
- Sub-Category
- Product Name
- Sales
- Quantity
- Profit

---

## Additional Columns Created

### 📅 Month

Extracted from Order Date to support monthly sales analysis.

```text
Month = Date.MonthName([Order Date])
```

---

### 🚚 Duration

Calculated to measure the number of days between placing an order and shipping it.

```text
Duration = Ship Date - Order Date
```

---

# 🛠 Excel Skills Used

Throughout this project, the following Microsoft Excel features were used:

- Power Query
- Pivot Tables
- Pivot Charts
- KPI Cards
- Line Chart
- Horizontal Bar Charts
- Doughnut Chart
- Map Chart
- Slicers
- Conditional Formatting
- Custom Number Formatting
- Dashboard Design
- Data Cleaning
- Data Visualization

---

# 📊 Dashboard Components

The dashboard consists of the following analytical sections:

- 📊 KPI Cards
- 📈 Monthly Sales Trend
- 🗺 Sales Distribution by State
- 🏙 Top Selling Cities
- 📦 Sales by Category
- 🚚 Shipping Mode Distribution
- ⏱ Shipping Duration Analysis
- 🎛 Interactive Filters (Slicers)

---

# 🧹 Data Cleaning with Power Query

<img width="1365" height="604" alt="power qq" src="https://github.com/user-attachments/assets/34bd5886-b17f-4b43-993b-4111c181ae2e" />

Power Query was used to import, clean, and prepare the raw dataset before building the dashboard.

### 🛠️ Excel Features

Utilized Power Query to automate the ETL (Extract, Transform, Load) process and ensure the dataset was ready for analysis.

### 🎨 Design Choice

Created a structured workflow that enables the dashboard to refresh automatically whenever new data is imported.

### 📊 Data Preparation

The following transformations were applied:

- Imported the CSV dataset.
- Changed data types.
- Renamed columns.
- Created a Month column.
- Created a Duration column.
- Removed unnecessary columns.
- Loaded the cleaned dataset into Excel.

### 💡 Insights Gained

Power Query significantly reduces manual work, improves data quality, and provides a repeatable workflow for future dashboard updates.

---
# 📊 KPI Cards

<img width="342" height="133" alt="KPIC" src="https://github.com/user-attachments/assets/f7881229-d55a-456a-8348-41f406b14ef8" />

The KPI Cards provide an immediate summary of the company's overall performance, allowing users to evaluate key business metrics without exploring the detailed charts.

### 🛠️ Excel Features

Built KPI Cards using Pivot Tables, linked cells, formulas, and custom formatting.

### 🎨 Design Choice

Positioned KPI Cards at the top of the dashboard to provide an instant overview of the most important business metrics.

### 📊 Data Representation

The dashboard displays:

- 💰 Total Sales
- 📈 Total Profit
- 📦 Total Quantity Sold
- 📊 Year-over-Year (YoY) Growth

### 💡 Insights Gained

Allows decision-makers to evaluate business performance instantly and quickly identify whether overall performance is improving or declining.

---

# 📈 Monthly Sales Trend

<img width="446" height="223" alt="MOUNTH" src="https://github.com/user-attachments/assets/962f8712-6cf0-4012-976f-69ca7ff50d21" />

The Monthly Sales Trend visualizes how sales evolve throughout the year, making it easier to detect seasonal patterns and performance changes.

### 🛠️ Excel Features

Utilized a Line Chart connected to Pivot Tables.

### 🎨 Design Choice

A line chart was selected because it effectively highlights trends and changes over time.

### 📊 Data Representation

Displays total monthly sales based on the **Month** field extracted from the Order Date.

### 💡 Insights Gained

- Identifies peak sales months.
- Detects low-performing periods.
- Reveals seasonal demand patterns.
- Supports sales forecasting.

---

# 🗺️ Sales Distribution by State

<p align="center">
<img src="images/map.png" width="850">
</p>

This visualization provides a geographic overview of furniture sales across the United States.

### 🛠️ Excel Features

Utilized Excel's Map Chart feature to visualize sales across U.S. states.

### 🎨 Design Choice

Applied a color-coded map to visually differentiate sales performance across geographic regions.

### 📊 Data Representation

Displays total sales for each state included in the dataset.

### 👁️ Visual Enhancement

The geographic visualization improves readability and provides an immediate understanding of regional sales performance through intuitive color coding.

### 💡 Insights Gained

- Highlights the highest-performing states.
- Identifies regions with lower sales.
- Supports regional sales analysis.
- Helps management prioritize business expansion opportunities.

---

# 🏙️ Top Selling Cities

<p align="center">
<img src="images/top_cities.png" width="750">
</p>

This chart ranks the cities generating the highest furniture sales.

### 🛠️ Excel Features

Utilized a Horizontal Bar Chart connected to Pivot Tables.

### 🎨 Design Choice

A horizontal bar chart was selected because it improves readability when comparing multiple city names.

### 📉 Data Organization

Cities are ranked in descending order based on total sales, making the highest-performing markets immediately visible.

### 💡 Insights Gained

- Identifies the company's strongest markets.
- Highlights cities contributing the largest share of revenue.
- Helps support regional marketing and sales strategies.

---
# 📦 Sales by Category

<p align="center">
<img src="images/category.png" width="750">
</p>

This chart compares the sales performance of each furniture category, helping users identify which categories contribute the most revenue.

### 🛠️ Excel Features

Utilized a Horizontal Bar Chart connected to Pivot Tables.

### 🎨 Design Choice

A horizontal bar chart was chosen to simplify comparisons between product categories.

### 📉 Data Organization

Categories are sorted in descending order based on total sales.

The dashboard compares:

- Chairs
- Tables
- Bookcases
- Furnishings

### 💡 Insights Gained

- Identifies the best-performing product categories.
- Supports inventory and purchasing decisions.
- Helps prioritize high-revenue product lines.

---

# 🚚 Shipping Mode Distribution

<p align="center">
<img src="images/shipping_mode.png" width="500">
</p>

This visualization analyzes how customers choose to receive their orders.

### 🛠️ Excel Features

Utilized Excel's Doughnut Chart feature connected to Pivot Tables.

### 🎨 Design Choice

A doughnut chart was selected because it clearly displays the percentage share of each shipping method.

### 📊 Data Representation

Displays the distribution of orders across:

- Standard Class
- Second Class
- First Class
- Same Day

### 💡 Insights Gained

- Reveals customer shipping preferences.
- Identifies the most frequently used shipping method.
- Supports logistics and shipping optimization.

---

# ⏱️ Shipping Duration Analysis

<p align="center">
<img src="images/shipping_duration.png" width="700">
</p>

This chart evaluates shipping performance by measuring the number of days required to deliver customer orders.

### 🛠️ Excel Features

Utilized a Column Chart based on the calculated **Duration** field.

### 🎨 Design Choice

A column chart was selected to compare delivery durations clearly.

### 📊 Data Representation

The analysis is based on:

```text
Duration = Ship Date - Order Date
```

It displays the number (or percentage) of orders delivered within each shipping duration.

### 💡 Insights Gained

- Evaluates shipping efficiency.
- Identifies the most common delivery time.
- Helps monitor logistics performance.

---

# 🎛️ Interactive Dashboard (Slicers)

<p align="center">
<img src="images/slicers.png" width="400">
</p>

The dashboard includes interactive slicers that allow users to explore the data dynamically without modifying the source dataset.

### 🛠️ Excel Features

Implemented Excel Slicers connected to all Pivot Tables and Pivot Charts.

### 🎨 Design Choice

Placed slicers at the top of the dashboard for quick and intuitive filtering.

### 🔒 Enhanced Dashboard Interaction

Users can instantly filter the entire dashboard by:

- 🌎 Region
- 👥 Customer Segment

This interaction:

- 🎯 Updates every visualization automatically.
- 🚫 Eliminates manual filtering.
- 👥 Improves dashboard usability.
- ⚡ Makes business analysis faster and more interactive.

### 💡 Insights Gained

Allows users to compare business performance across different regions and customer segments in real time.

---

# 💡 Key Insights

The dashboard provides several important business insights:

- 📈 Sales performance changes throughout the year, revealing seasonal demand patterns.
- 🗺 Certain states generate significantly higher revenue than others.
- 🏙 A small number of cities contribute a large portion of total sales.
- 📦 Some furniture categories consistently outperform others.
- 🚚 Standard Class is the most commonly used shipping method.
- ⏱ Most orders are delivered within a relatively short shipping duration.
- 👥 Customer segments exhibit different purchasing behaviors that can be analyzed through interactive filtering.

---

# 📷 Final Dashboard

<p align="center">
<img src="images/dashboard.png" width="100%">
</p>

---

# 🎯 Conclusion

This project demonstrates how Microsoft Excel can be used as a powerful Business Intelligence (BI) tool to transform raw sales data into meaningful business insights.

By combining Power Query, Pivot Tables, Pivot Charts, KPI Cards, Map Charts, and Interactive Slicers, the dashboard enables users to explore sales performance, identify trends, and support data-driven decision-making.

## Skills Demonstrated

- ✅ Data Cleaning
- ✅ Data Transformation
- ✅ Power Query
- ✅ Pivot Tables
- ✅ Pivot Charts
- ✅ Dashboard Design
- ✅ KPI Reporting
- ✅ Interactive Dashboards
- ✅ Business Analysis
- ✅ Data Visualization

This project reflects my ability to build professional Excel dashboards that combine data preparation, analysis, visualization, and storytelling into a single interactive reporting solution.

---

# 📁 Project Structure

```text
Furniture-Sales-Dashboard/
│
├── README.md
├── Excel Project.xlsx
├── dataset/
│   └── Furniture_Sales.csv
│
└── images/
    ├── dashboard.gif
    ├── dashboard.png
    ├── power_query.png
    ├── kpi_cards.png
    ├── sales_trend.png
    ├── map.png
    ├── top_cities.png
    ├── category.png
    ├── shipping_mode.png
    ├── shipping_duration.png
    └── slicers.png
```

---

# 👨‍💻 Author

**Akram Hachrouf**

Data Analyst | Excel | Power Query | Data Visualization

If you found this project useful, feel free to ⭐ this repository.
