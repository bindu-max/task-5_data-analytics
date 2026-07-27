# Task 5: Interactive Sales Dashboard

## Project Overview

This project presents an **Interactive Sales Dashboard** developed using **Python, Dash, Plotly Express, and Pandas**. The dashboard transforms raw sales data into meaningful visual insights by displaying key performance indicators (KPIs) and interactive charts. It enables users to monitor sales performance, identify trends, and make data-driven decisions.

---

## Objectives

- Build an interactive web dashboard using Dash.
- Visualize sales data through dynamic charts.
- Display important business KPIs.
- Demonstrate practical data analysis and visualization skills.

## Technologies Used

- Python 3.x
- Pandas
- Dash
- Plotly Express
- OpenPyXL


## Features

### Key Performance Indicators (KPIs)

The dashboard provides the following business metrics:

- Total Sales
- Average Unit Price
- Total Quantity Sold
- Average Customer Age

### Interactive Visualizations

- **Sales Trend:** Line chart showing sales over time.
- **Sales by Gender:** Doughnut chart illustrating gender-wise sales distribution.
- **Sales by Category:** Pie chart representing category-wise sales.
- **Product Sales Treemap:** Hierarchical view of sales by product.
- **Category Comparison:** Horizontal bar chart comparing total sales across categories.

---

## Dataset Requirements

The application requires an Excel dataset containing the following columns:

| Column Name | Description |
|------------|-------------|
| Order_Date | Date of purchase |
| Total_Sales | Total sales amount |
| Unit_Price | Price per unit |
| Quantity | Quantity sold |
| Age | Customer age |
| Gender | Customer gender |
| Category | Product category |
| Product | Product name |

---
## Project Structure

```
Sales-Dashboard/
│
├── app.py
├── ApexPlanet_DataAnalytics_Dataset.xlsx
├── README.md
└── requirements.txt

## Learning Outcomes

Through this project, the following concepts were implemented:

- Data loading and preprocessing using Pandas
- KPI calculation and business metric analysis
- Interactive dashboard development with Dash
- Data visualization using Plotly Express
- Business intelligence and reporting techniques

## Future Enhancements

- Add filters for date, category, and gender.
- Implement real-time data updates.
- Enhance the user interface with Bootstrap themes.
- Export dashboard reports to PDF or Excel.
- Deploy the dashboard on a cloud platform such as Render or Heroku.


## Conclusion

This project demonstrates how Python-based visualization tools can be used to create an interactive business dashboard. It provides valuable insights into sales performance through intuitive charts and KPIs, making it an effective solution for data analysis and decision-making.

