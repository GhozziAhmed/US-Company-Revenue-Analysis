# 📈 US Top 100 Companies: Revenue & Efficiency Analysis

## 📌 Project Overview
This project involves **web scraping** the list of the largest companies in the United States by revenue from Wikipedia. The goal was to transform messy web data into a clean dataset for **Exploratory Data Analysis (EDA)** to understand industry trends and corporate efficiency.

## 🛠️ Tools Used
* **Python** (Requests & BeautifulSoup) for web scraping.
* **Pandas** for data cleaning (handling footnotes, currency conversion, and data types).
* **Seaborn & Matplotlib** for data visualization.

## 🧹 Data Cleaning Process
The raw data from Wikipedia required several cleaning steps:
1.  **Numeric Conversion:** Converted strings with commas and dollar signs (e.g., `$611,289`) into floats.
2.  **Handling Percentages:** Stripped `%` symbols from revenue growth and converted them to numeric values.
3.  **Feature Engineering:** Split the `Headquarters` column into `City` and `State` for geographic analysis.

## 📊 Key Visualizations

### 1. Revenue vs. Employee Count (Efficiency)
This scatter plot highlights the relationship between workforce size and revenue. 
![Business Efficiency](images/efficiency_scatter.png)
> **Insight:** Companies like Walmart and Amazon are extreme outliers in terms of employee count, whereas Tech giants show higher revenue-per-employee.

### 2. Top 10 Companies by Revenue
A look at the giants leading the US economy.
![Top 10 Revenue](images/top_10_revenue.png)

### 3. Geographic Distribution
Which states host the most corporate power?
![State Distribution](images/state_distribution.png)
> **Insight:** Texas and New York dominate the headquarters landscape for the Top 100 companies.

## 🏁 Conclusion
The analysis shows that while retail giants lead in total revenue, technology and healthcare sectors often demonstrate superior operational efficiency. This dataset provides a snapshot of the economic heavyweights in the US as of 2024.

---
*Developed as part of my Data Analytics Portfolio.*
