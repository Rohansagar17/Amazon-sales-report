# 📊 Amazon Sales Data Analysis Using Python

## 📌 Project Overview

This project focuses on analyzing Amazon sales data using Python to understand sales patterns, customer purchasing behaviour, product preferences, and order fulfilment trends.

The main objective is to perform Exploratory Data Analysis (EDA) and extract meaningful insights from the dataset through data cleaning, statistical analysis, and data visualization.

## 🎯 Project Objectives

- Analyze Amazon sales data to understand customer purchasing patterns.
- Identify the most popular product categories and sizes.
- Examine order and courier status.
- Understand state-wise customer distribution.
- Analyze B2B and B2C purchasing behaviour.
- Generate meaningful insights through visualizations.

## 📂 Dataset Information

- **Dataset:** Amazon Sale Report
- **Original Records:** 128,976
- **Time Period:** March 2022 – June 2022
- **Data Format:** CSV
- **Key Features:**
  - Order ID
  - Date
  - Order Status
  - Fulfilment
  - Sales Channel
  - Category
  - Size
  - Courier Status
  - Quantity
  - Amount
  - Shipping City
  - Shipping State
  - B2B

## 🛠️ Technologies & Libraries Used

- Python
- Pandas – Data manipulation and cleaning
- NumPy – Numerical operations
- Matplotlib – Data visualization
- Seaborn – Statistical data visualization
- Jupyter Notebook – Data analysis environment

## 🔍 Project Workflow

### 1. Data Loading
Imported the Amazon sales dataset using Pandas.

### 2. Data Cleaning
- Removed unnecessary columns.
- Identified missing values.
- Handled missing records.
- Converted date columns into datetime format.
- Converted postal codes into integer format.
- Renamed the Qty column to Quantity.

### 3. Exploratory Data Analysis (EDA)

Performed different analyses to understand:

- Product size distribution.
- Category-wise product demand.
- Courier and order status.
- B2B vs B2C customer distribution.
- State-wise customer distribution.
- Quantity and amount statistics.

### 4. Data Visualization

Created different visualizations using Matplotlib and Seaborn:

- Count plots
- Bar plots
- Histograms
- Pie charts
- Scatter plots

## 📈 Key Insights

Based on the analysis performed:

1. **Popular Product Size:** M-size recorded the highest quantity among the available sizes in the cleaned dataset.

2. **Product Demand:** T-shirts were among the most popular product categories in the original dataset.

3. **Customer Distribution:** Maharashtra recorded the highest number of orders in the original dataset.

4. **Customer Type:** Retail customers represented approximately 99.3% of the original dataset, while B2B customers accounted for approximately 0.7%.

5. **Order Fulfilment:** The analysis of the cleaned dataset showed that all retained records belonged to Merchant fulfilment.

6. **Courier Status:** Most retained orders had a shipped courier status.

## 📁 Repository Structure

```text
Amazon-Sales-Data-Analysis/
│
├── Amazon Sale Report.csv
├── amazon.ipynb
└── README.md
```

## ⚠️ Data Cleaning Note

The original dataset contains 128,976 records. The notebook removes all rows containing missing values, reducing the dataset to 37,514 records.

A significant number of records have missing values in the `fulfilled-by` column. Therefore, the cleaned dataset represents only a subset of the original data, and some findings may not represent the complete sales dataset.

## 🏁 Conclusion

This project helped me understand how Python can be used to transform raw sales data into meaningful business insights.

Through data cleaning, exploratory analysis, and visualization, I explored customer preferences, product demand, order fulfilment patterns, and geographical sales distribution.

The project strengthened my practical understanding of Python-based data analysis and the importance of data-driven decision-making.

## 👨‍💻 Author

**Rohan Sagar**

PGDM | Marketing & Business Analytics

Skills: Python | Pandas | NumPy | Matplotlib | Seaborn | Exploratory Data Analysis

---
⭐ If you find this project interesting, feel free to explore the repository!
