# Chicago Data Analysis with SQL and Python

A comprehensive data analysis project examining Chicago's socioeconomic indicators, public schools, and crime data using SQL queries and Python visualizations.

## 📋 Overview

This Jupyter Notebook performs SQL-based analysis on three Chicago datasets:
- **Census Data**: Socioeconomic indicators including poverty rates, income levels, and hardship index
- **Public Schools**: School performance metrics and safety scores from 2011-2012
- **Crime Data**: Reported crime incidents across Chicago communities

## 🎯 Project Objectives

The notebook answers 10 analytical questions using SQL queries:
1. Total number of crimes recorded
2. Community areas with per capita income < $11,000
3. Crimes involving minors
4. Kidnapping crimes involving children
5. Types of crimes at schools
6. Average safety score by school type
7. Top 5 community areas with highest poverty rates
8. Most crime-prone community area
9. Community area with highest hardship index (using subquery)
10. Community area with most crimes (using subquery)

## 🛠️ Technologies Used

- **Python 3.8+**
- **SQLite** - Database management
- **pandas** - Data manipulation and loading
- **ipython-sql** - SQL magic commands in Jupyter
- **matplotlib** - Data visualization

## 📦 Installation
```bash
pip install pandas ipython-sql matplotlib
```

## 🚀 Usage

1. Clone this repository
2. Open the notebook in Jupyter:
```bash
   jupyter notebook Chicago_SQL_Analysis_Assignment.ipynb
```
3. Run all cells sequentially

The notebook will:
- Create a local SQLite database (`ChicagoData.db`)
- Load CSV data from IBM cloud storage
- Execute SQL queries
- Generate visualizations

## 📊 Visualizations

The notebook includes three bonus visualizations:
- **Top 10 Community Areas by Crime Count** - Horizontal bar chart
- **Hardship Index vs Per Capita Income** - Scatter plot showing correlation
- **Crime Types Distribution** - Pie chart of top 10 crime categories

## 📁 Data Sources

All datasets are sourced from IBM Developer Skills Network:
- Chicago Census Data
- Chicago Public Schools Data
- Chicago Crime Data

## 📝 Key Findings

- Strong inverse correlation between per capita income and hardship index
- Significant economic disparity across community areas
- Varying crime rates and types across different neighborhoods
- School safety scores differ by school type

## 👤 Author

**Burak Aktas*  
Date: January 11, 2025

## 📄 License

This project is created for educational purposes as part of a graded assessment.

---
