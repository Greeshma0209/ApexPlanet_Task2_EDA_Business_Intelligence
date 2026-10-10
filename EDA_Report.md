# Exploratory Data Analysis (EDA) & Business Intelligence

## 1. Project Overview

This project is part of the ApexPlanet Data Analytics Internship – Task 2.

The objective is to explore the cleaned e-commerce sales dataset, identify important patterns and trends, answer business questions using SQL, and generate meaningful business insights.

## 2. Dataset Overview

The cleaned dataset contains 1,000 records and 13 columns.

Key fields include:

- Order_ID
- Order_Date
- Customer_ID
- Customer_Name
- Age
- Gender
- City
- Product
- Category
- Quantity
- Unit_Price
- Total_Sales
- Sales_Outlier

The dataset was cleaned and prepared during Task 1 before performing this EDA.

## 3. Descriptive Statistics

### Age
- Mean: 41.35
- Minimum: 18
- Maximum: 65

### Quantity
- Mean: 5.44
- Minimum: 1
- Maximum: 10

### Unit Price
- Mean: 25,486.78
- Minimum: 145.78
- Maximum: 49,997.53

### Total Sales
- Mean: 139,399.44
- Minimum: 437.34
- Maximum: 493,677.50

## 4. Univariate Analysis

### Sales by Category

Electronics generated the highest total sales, followed by Education, Grocery, Furniture, and Fashion.

### Sales by Gender

Male customers generated higher total sales than female customers.

### Sales by City

Patna generated the highest total sales among the cities in the dataset.

### Quantity by Category

Electronics had the highest quantity sold, while Fashion had the lowest.

## 5. Multivariate Analysis

Correlation analysis showed:

- Quantity vs Total Sales: 0.647
- Unit Price vs Total Sales: 0.686
- Age vs Total Sales: 0.001

Quantity and Unit Price showed positive relationships with Total Sales, while Age showed almost no relationship with Total Sales.

A correlation heatmap and scatter plots were used to visualize these relationships.

## 6. SQL Business Questions

Seven business questions were analyzed using SQL:

1. Which product category generates the highest total sales?
2. Which gender generates the highest total sales?
3. Which cities generate the highest total sales?
4. Which product categories have the highest quantity sold?
5. Which category has the highest average sales per order?
6. How do sales vary across category and gender?
7. Which product categories perform best in each city?

The SQL queries are available in:

`ApexPlanet_Task2_Business_Questions.sql`

## 7. Key Business Insights

- Electronics is the highest-selling category.
- Electronics also has the highest quantity sold.
- Grocery has the highest average sales per order.
- Male customers generated higher overall sales than female customers.
- Patna generated the highest total sales among the cities.
- Electronics was the top-performing category across all known cities.
- Quantity and Unit Price have positive relationships with Total Sales.
- Age has almost no relationship with Total Sales.

## 8. Conclusion

The EDA helped identify important sales patterns across categories, genders, cities, and customer-related variables.

The analysis provides useful business insights that can support category-level and city-level sales decisions. The findings will also be useful for developing the dashboard and deeper analysis in the upcoming internship tasks.



## Task 2: Exploratory Data Analysis (EDA) & Business Intelligence

### Project Overview
This project is part of the ApexPlanet Data Analytics Internship. The goal is to analyze an e-commerce sales dataset, identify trends, answer business questions, and present useful business insights.

### Tools Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Microsoft SQL Server (SSMS)
- Microsoft Excel
- GitHub

### Dataset
- 1,000 records
- 13 columns
- Cleaned dataset prepared during Task 1

### Analysis Performed
- Descriptive statistics
- Sales analysis by category, gender, and city
- Quantity analysis by product category
- Correlation analysis
- Scatter plots and pair plot
- Correlation heatmap
- Seven SQL business questions
- Excel dashboard chart

### Key Business Insights
- Electronics generated the highest total sales.
- Electronics had the highest quantity sold.
- Grocery had the highest average sales per order.
- Male customers generated higher overall sales than female customers.
- Patna recorded the highest total sales among the cities.
- Quantity and Unit Price showed positive relationships with Total Sales.
- Age showed almost no relationship with Total Sales.

### Project Files
- `ApexPlanet_Task1_Final_Cleaned.csv` — cleaned dataset
- `ApexPlanet_Task2_Business_Questions.sql` — SQL business questions
- `EDA_Report.md` — detailed EDA report
- `Correlation_Heatmap.png` — correlation visualization
- `Quantity_vs_Total_Sales.png` — scatter plot
- `Unit_Price_vs_Total_Sales.png` — scatter plot
- `Pair_Plot_Ecommerce_Sales.png` — pair plot
- `ApexPlanet_Task2_Dashboard.xlsx` — Excel dashboard

### Conclusion
This project helped strengthen practical skills in exploratory data analysis, SQL, data visualization, and business intelligence. The findings can support further analysis and dashboard development.
