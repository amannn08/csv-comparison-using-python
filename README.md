# 📦 Amazon Product Market Comparison (Brazil vs Canada)

This project performs a detailed comparative analysis of Amazon products listed in **Brazil** and **Canada** using Python. The goal was to understand market trends, pricing, and product performance between the two countries by processing and comparing datasets of listed items.

---

## 📌 Table of Contents

- [Overview](#overview)
- [Dataset Description](#dataset-description)
- [Tech Stack](#tech-stack)
- [Key Metrics Compared](#key-metrics-compared)
- [Results Preview](#results-preview)
- [Project Workflow](#project-workflow)
- [Key Insights](#key-insights)
- [How to Run](#how-to-run)
- [Contact](#contact)

---

## 📊 Overview

The project uses structured Amazon product datasets from Brazil and Canada to draw meaningful comparisons. Metrics like **average price**, **star ratings**, **review counts**, and **best sellers** were analyzed. The analysis was performed using Python with libraries like `pandas`, and the output was visualized as a comparative table.

---

## 📁 Dataset Description

- `amz_br_total_products_data_processed.csv` → Cleaned and structured Amazon Brazil product data  
- `amz_ca_total_products_data_processed.csv` → Cleaned and structured Amazon Canada product data  
- `comparison_results.csv` → Output comparison of key metrics between both markets  
- `com.ipynb` → Python notebook for data processing and metric calculation

---

## 🛠️ Tech Stack

- **Language**: Python  
- **Libraries**: pandas, numpy  
- **Data Format**: CSV  
- **Notebook**: Jupyter (`.ipynb`)  

---

## 📊 Key Metrics Compared

| Metric                         | Brazil     | Canada     |
|-------------------------------|------------|------------|
| Average Price                 | 169.61     | 41.27      |
| Average List Price            | 97.08      | 9.94       |
| Average Stars                 | 4.59       | 4.37       |
| Average Reviews               | 906.51     | 1518.63    |
| Number of Best Sellers        | 50         | 19         |
| Products Bought (Last Month)  | 174250     | 31700      |
| Max Price                     | 3799.05    | 990.0      |
| Min Price                     | 0.0        | 0.0        |
| Price Range                   | 3799.05    | 990.0      |
| Avg. Price Difference         | +128.34    | -128.34    |


---

## 🔄 Project Workflow

1. **Data Import & Cleaning**
   - Removed missing/null entries
   - Cleaned numerical values and currency formatting

2. **Metric Calculations**
   - Aggregated KPIs such as price, reviews, stars, and monthly sales

3. **Country-wise Comparison**
   - Created a final comparison dataframe using `pandas`

4. **Output Export**
   - Saved result as `comparison_results.csv`
   - Displayed output in tabular format for visualization

---

## 📌 Key Insights

- Products in **Brazil** tend to have a significantly **higher average price** than in Canada.
- Despite having fewer best sellers, **Brazil had more products bought** in the last month.
- **Canada** leads in average reviews, which may indicate stronger customer engagement.
- Both countries have similar max and min star ratings but differ in price distribution.

---


