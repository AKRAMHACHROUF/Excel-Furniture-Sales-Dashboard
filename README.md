# 📊 Furniture Sales Dashboard | Microsoft Excel

<img width="1233" height="601" alt="mapss" src="https://github.com/user-attachments/assets/b7395e44-89dd-4c5f-9d93-aead0f8d7bae" />

# 📑 Table of Contents

- Introduction
- Executive Summary
- Business Objectives
- Business Questions
- Dataset
- Excel Skills Used
- Data Cleaning
- Dashboard Build
- Dashboard Components
- Interactive Filters
- Dashboard Walkthrough
- Key Insights
- Future Improvements
- Project Structure
- Author

---

# 📖 Introduction

The **Furniture Sales Dashboard** is an interactive Business Intelligence project built entirely in **Microsoft Excel**.

The purpose of this project is to transform raw furniture sales data into meaningful business insights through interactive dashboards, KPI cards, charts, and slicers.

The dashboard enables decision-makers to monitor business performance, analyze sales trends, evaluate profitability, and identify customer and regional sales patterns.

---

# 📋 Executive Summary

This dashboard analyzes furniture sales transactions across the United States.

Using Power Query and Excel Dashboard techniques, raw transactional data was transformed into an interactive reporting solution that helps users answer important business questions regarding sales performance, shipping operations, customer segmentation, and geographical distribution.

---

# 🎯 Business Objectives

The dashboard was created to help answer questions such as:

- What are the total sales?
- What is the total profit?
- How many products were sold?
- Which months generate the highest sales?
- Which product categories perform the best?
- Which states generate the highest revenue?
- Which cities contribute the most sales?
- Which shipping method is used the most?
- How long does shipping usually take?

---

# ❓ Business Questions

- How much revenue has been generated?
- Which month achieved the highest sales?
- Which state has the highest sales?
- Which city generates the highest revenue?
- Which category contributes the most sales?
- Which shipping mode is preferred by customers?
- What is the average shipping duration?
- Which customer segment contributes the highest revenue?

---

# 📂 Dataset

The dataset contains furniture sales transactions across multiple regions in the United States.

### Dataset Columns

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

### Custom Columns

The following calculated columns were created using Power Query.

| Column | Description |
|---------|-------------|
| Duration | Ship Date − Order Date |
| Month | Extracted from Order Date |

---

# 🛠 Excel Skills Used

This project demonstrates the following Excel skills:

- Microsoft Excel
- Power Query
- Data Cleaning
- Data Transformation
- Pivot Tables
- Pivot Charts
- KPI Cards
- Interactive Dashboard
- Map Charts
- Doughnut Charts
- Conditional Formatting
- Slicers

---

# 🧹 Data Cleaning

Power Query was used to clean and prepare the dataset before analysis.

The following transformations were performed:

- Imported CSV file
- Changed data types
- Removed unnecessary columns
- Created Shipping Duration column
- Extracted Month from Order Date
- Loaded transformed data into Excel

---

### 📷 Power Query Screenshot

```text
images/power_query.png
```

---

# 📊 Dashboard Build

The dashboard was designed to provide a complete overview of business performance through KPI cards and interactive visualizations.

---

# 📌 KPI Cards

The dashboard summarizes business performance using four key metrics.

### KPIs

- Total Sales
- Total Profit
- Total Quantity
- Year-over-Year Growth

### Purpose

Provide an instant overview of overall business performance.

### 📷 Screenshot

```text
images/kpi_cards.png
```

---

# 📈 Monthly Sales Trend

### Chart Type

Line Chart

### Purpose

Analyze monthly sales performance throughout the year.

### Business Insight

Helps identify peak and low sales periods.

### 📷 Screenshot

```text
images/sales_trend.png
```

---

# 🗺 Sales Distribution by State

### Chart Type

Excel Map Chart

### Purpose

Visualize geographical sales distribution.

### Business Insight

Identify the highest-performing states.

### 📷 Screenshot

```text
images/map.png
```

---

# 🏙 Top Selling Cities

### Chart Type

Horizontal Bar Chart

### Purpose

Compare sales among cities.

### Business Insight

Highlights the cities generating the highest revenue.

### 📷 Screenshot

```text
images/top_cities.png
```

---

# 📦 Sales by Category

### Chart Type

Horizontal Bar Chart

### Purpose

Compare sales across furniture categories.

### Categories

- Chairs
- Tables
- Furnishings
- Bookcases

### Business Insight

Shows which category contributes the highest revenue.

### 📷 Screenshot

```text
images/category.png
```

---

# 🚚 Shipping Mode Distribution

### Chart Type

Doughnut Chart

### Purpose

Analyze customer shipping preferences.

### Shipping Modes

- First Class
- Second Class
- Standard Class
- Same Day

### Business Insight

Shows the most commonly used shipping method.

### 📷 Screenshot

```text
images/shipping_mode.png
```

---

# ⏱ Shipping Duration Analysis

### Chart Type

Column Chart

### Purpose

Analyze the number of shipping days required for customer orders.

### Business Insight

Evaluate shipping efficiency.

### 📷 Screenshot

```text
images/shipping_duration.png
```

---

# 🎛 Interactive Filters

The dashboard includes interactive slicers.

### Available Filters

- Region
- Customer Segment

Users can dynamically filter all charts and KPI cards.

### 📷 Screenshot

```text
images/slicers.png
```

---

# 🚶 Dashboard Walkthrough

When a user selects a specific Region or Customer Segment, the dashboard automatically updates:

- KPI Cards
- Sales Trend
- State Map
- Sales by Category
- Top Cities
- Shipping Analysis

This enables interactive exploration without modifying the source data.

---

# 💡 Key Insights

The dashboard helps decision-makers quickly identify:

- Overall business performance
- Monthly sales trends
- Best-performing states
- Highest-selling cities
- Best-performing product categories
- Customer shipping preferences
- Shipping efficiency
- Regional sales performance

---

# 🚀 Future Improvements

Future versions of the dashboard may include:

- Customer Analysis Dashboard
- Product Performance Dashboard
- Profit Margin KPI
- Dynamic Timeline
- Power BI Version
- SQL Integration

---

# 📁 Project Structure

```
Furniture-Sales-Dashboard
│
├── Furniture_Sales_Dashboard.xlsx
├── README.md
│
├── images
│   ├── dashboard.png
│   ├── power_query.png
│   ├── kpi_cards.png
│   ├── sales_trend.png
│   ├── map.png
│   ├── top_cities.png
│   ├── category.png
│   ├── shipping_mode.png
│   ├── shipping_duration.png
│   └── slicers.png
```

---

# 👨‍💻 Author

**Akram Hachrouf**

Computer Science Graduate

Aspiring Data Analyst passionate about turning raw data into interactive dashboards and business insights.

## Connect with me

- LinkedIn: *(Add your profile)*
- GitHub: *(Add your profile)*

---

# ⭐ Support

If you found this project helpful, consider giving it a ⭐ on GitHub.
