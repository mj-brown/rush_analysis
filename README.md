# RUSH Sales Analysis

## Overview
This project analyzes sales data for **RUSH**, a global athletic brand, to uncover trends in products, retailers, and customer demographics over 2020–2021. Using Python in Jupyter Notebook, I cleaned, transformed, and visualized data from three source tables to answer key business questions and provide actionable insights.

## Business Questions Answered
- Which states generated the highest sales by gender in 2021?
- Which retailers purchased the most units in 2020 vs. 2021?
- How do quarterly and year-over-year sales trends compare across service types?
- What patterns emerge in unit price, product categories, and regional performance?

## Data Sources
- `TABLE_PRODUCTS_885.csv`  
- `TABLE_RETAILER_885.csv`  
- `TABLE_SALES_885.csv`  

These datasets were joined and validated in pandas to create a unified data model for analysis.

## Tools & Libraries
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Jupyter Notebook  

## Key Deliverables
- Cleaned and merged datasets prepared for analysis  
- Visualizations showing sales trends by retailer, product, and region  
- Insights on top-performing states, gender-based sales, and category mix  
- Year-over-year retailer comparison (e.g., Amazon in 2020 vs. Foot Locker in 2021)  

## Results & Impact
- Identified Maine and Delaware as 2021 top-performing states for women’s and men’s sales, respectively  
- Highlighted retailer shifts: **Amazon (2020)** vs. **Foot Locker (2021)**  
- Provided executives with a reproducible, data-driven tool for proactive decision-making  

## How to Run
1. Clone this repository.  
2. Install dependencies:  
   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
3. Open the notebook in Juypter:
    `jupyter notebook GB885_Final_Project_Brown_M.ipynb`
4. Run all cells to reproduce the analysis and visualizations.
