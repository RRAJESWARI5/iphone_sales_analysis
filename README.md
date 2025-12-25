# iPhone Sales Analysis Using Python and Data Science

## Domain
Data Science

## Description
This project analyzes iPhone sales transaction data to identify **peak sales hours**. 
It uses Python with Pandas, NumPy, and Matplotlib to extract hour-wise transaction information 
and visualize sales trends throughout the day.  
The insights from this project can help businesses optimize **staffing, inventory, and marketing strategies**.

---

## Objectives
- Identify busiest sales hours for iPhone transactions  
- Understand hourly sales distribution  
- Visualize peak and low sales periods using graphs  

---

## Tools & Libraries Used
- **Python** (Jupyter Notebook)  
- **Pandas** – For data manipulation and analysis  
- **NumPy** – For numerical operations  
- **Matplotlib** – For creating visualizations  

---

## Dataset
- `Order_details-masked.csv` (Contains transaction date and time)  
- Primary column used: **Transaction Date**  
- The dataset is used to extract hourly sales data for analysis

---

## Analysis Steps
1. Convert the `Transaction Date` column to datetime format  
2. Extract the **hour** from each transaction timestamp  
3. Count the number of transactions for each hour  
4. Identify peak sales hours  
5. Plot a line graph showing **hourly sales trends**

---

## Output
- Table of transactions per hour  
- Line graph showing sales throughout the day  
- Insights about **peak and low-demand hours**  

---

## How to Run
1. Open `iphone_sales_analysis.ipynb` in **Jupyter Notebook**  
2. Ensure required libraries are installed:  
   ```bash
   pip install pandas numpy matplotlib

