# Global Store Data Analysis
**Portfolio project:** analyzing sales data of a company operating in the global market, selling products both in physical stores and online using **Python**.

---

## Project Objective
The goal of this project is to **clean, explore, and analyze sales data** to uncover key business patterns and performance trends. The analysis covers **sales dynamics**, **top-performing categories**, **regional differences**, **sales channels (online vs offline)**, **delivery time performance** and **weekly and monthly seasonality**.

---

## Tools & Technologies
To complete this project, the following tools and technologies were used:
- **Python** – used as the primary tool throughout the entire project, with the following core libraries:
  - **Pandas**, **NumPy** – data cleaning, transformation and aggregation
  - **Matplotlib**, **Seaborn** – data visualization
  - **ipywidgets** – interactive widgets for creating charts by selecting different metrics such as **Revenue**, **Cost**, **Profit** and **Units Sold**  
    *(⚠️ not displayed on GitHub; open in Google Colab and **`run the code`** to view charts)*
  - **Plotly Express** – interactive charts *(⚠️ not displayed on GitHub; open in Google Colab to view them)*
    
- **Google Colab** – environment for code execution and data analysis.

---

## Dataset Overview
The dataset consists of three tables:

- **File:** `events.csv` – sales data across years  
- **File:** `products.csv` – product categories and their codes  
- **File:** `countries.csv` – countries, regions and their codes

The datasets were loaded into the notebook directly from GitHub using raw file links.

---

## Notebook Structure

**File:** `store_analysis.ipynb`

The Google Colab notebook is organized into the following main sections:
1. **Data Overview** – loading the datasets, reviewing the column content and describing their structure. Identifying key fields that connect the three tables.
2. **Data Cleaning** – verifying that all data types are correctly recognized and checking for missing values, duplicates and anomalies. Missing values were filled or removed when necessary, and data types were validated and adjusted.
3. **Data Analysis and Visualization** – merging all tables into a single dataset, calculating key metrics, and analyzing and visualizing data to identify valuable business insights.
4. **Reporting** – final results and practical recommendations.

---

## Author

**Sviatoslav Mykytyn**  
📅 November 2025  
💼 Data Analytics Portfolio  
🔗 [LinkedIn](https://www.linkedin.com/in/sviatoslav-mykytyn-758997242/)
