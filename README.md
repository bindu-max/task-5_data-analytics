# Task 5: Sales Data Analysis and Visualization using Python

This project analyzes the **ApexPlanet Data Analytics Dataset** using **Python**, **Pandas**, and **Matplotlib**. The objective is to clean the data, calculate business Key Performance Indicators (KPIs), and create visualizations that help understand sales performance, customer behavior, and product trends.

---

## Features

* Data loading from an Excel file
* Data cleaning by removing missing values
* KPI calculations
* Sales analysis by category, city, gender, and product
* Sales trend analysis over time
* Data visualization using multiple chart types

---

## Technologies Used

* Python 3.x
* Pandas
* Matplotlib
* Squarify
* OpenPyXL

---

## Dataset

**File Name:**

`ApexPlanet_DataAnalytics_Dataset.xlsx`

The dataset includes information such as:

* Order ID
* Customer ID
* Product
* Category
* City
* Gender
* Age
* Quantity
* Unit Price
* Total Sales
* Order Date

---

## Key Performance Indicators (KPIs)

The project calculates the following metrics:

* Total Sales
* Total Quantity Sold
* Average Unit Price
* Average Customer Age
* Total Customers
* Total Orders

---

## Data Analysis

The project performs the following analyses:

* Sales by Category
* Sales by City
* Sales by Gender
* Quantity Sold by Product
* Sales Trend by Order Date

---

## Visualizations

The project includes the following charts:

1. Bar Chart – Sales by Category
2. Line Chart – Sales Trend
3. Pie Chart – Sales by Category
4. Donut Chart – Sales by Gender
5. Treemap – Sales by Product

These visualizations provide clear insights into overall business performance and customer purchasing patterns.

---

## Project Structure

```
ApexPlanet_DataAnalytics_Project/
│
├── ApexPlanet_DataAnalytics_Dataset.xlsx
├── data_analysis.py
├── README.md
└── requirements.txt
```

---

## Installation

Install the required libraries using pip:

```bash
pip install pandas matplotlib openpyxl squarify
```

---

## How to Run

1. Place the dataset (`ApexPlanet_DataAnalytics_Dataset.xlsx`) in the project folder.
2. Install the required libraries.
3. Run the Python script:

```bash
python data_analysis.py
```

The program will:

* Load the dataset
* Clean missing values
* Calculate KPIs
* Print analytical results
* Display all charts

---

## Project Outcomes

* Improved understanding of sales performance
* Identified top-performing product categories
* Compared sales across cities and genders
* Analyzed customer purchasing trends
* Visualized business insights through charts

---

## Future Improvements

* Build an interactive dashboard using Dash or Streamlit.
* Add filters for city, category, and date.
* Include predictive sales forecasting using Machine Learning.
* Export reports to PDF or Excel.
* Deploy the project as a web application.

