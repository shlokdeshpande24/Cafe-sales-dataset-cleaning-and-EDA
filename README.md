## ☕ Cafe Sales Data Analysis Using Python


# 📌 Project Overview

This project focuses on cleaning and analyzing a café sales dataset to transform raw data into meaningful business insights. The project follows a complete data analytics workflow, including Data Cleaning and Exploratory Data Analysis (EDA).

The primary objective is to improve the quality of the dataset and identify useful sales patterns that can help understand customer purchasing behavior.

The project includes:

Data Cleaning
Exploratory Data Analysis (EDA)
Statistical Summary
Correlation Analysis
Trend Identification
Insight Documentation


# 🎯 Problem Statement

Businesses often collect sales data containing missing values, incorrect entries, inconsistent data types, and duplicate records. Such issues reduce data quality and make analysis unreliable.

The objective of this project is to clean the café sales dataset and perform exploratory data analysis to discover meaningful insights that support better business decisions.


# 📂 Dataset

Dataset: Dirty Cafe Sales Dataset (Kaggle)

Features Used

Transaction ID

Item

Quantity

Price Per Unit

Total Spent

Payment Method

Location

Transaction Date


# 🛠️ Technologies Used
Python

Google Colab

Pandas

NumPy

Matplotlib

Seaborn


# 🧹 Data Cleaning

The following preprocessing steps were performed:

Replaced invalid values (UNKNOWN and ERROR) with missing values.
Handled missing values using suitable techniques.
Fixed incorrect data types.
Removed duplicate records.
Created a Data Quality Report.
Saved the cleaned dataset for further analysis.


# 📊 Exploratory Data Analysis (EDA)

EDA was performed to understand sales patterns and customer behavior.

Analysis Performed
Statistical Summary
Item Distribution Analysis
Payment Method Distribution
Sales by Location
Total Sales by Item
Correlation Analysis
Monthly Sales Trend


# 📈 Key Insights
C offee, Juice, Tea, Cake and Sandwich are among the frequently sold products.
Digital Wallet is one of the most commonly used payment methods.
Takeaway transactions are higher than In-store purchases.
Products with higher quantity sold generally contribute to higher total sales.
Sales trends vary across different months, indicating seasonal purchasing behavior.


# 📊 Statistical Summary

Statistical analysis was performed to understand the distribution of numerical variables such as Quantity, Price Per Unit and Total Spent.

The summary includes:

Count
Mean
Standard Deviation
Minimum Value
Maximum Value
Quartiles


# 🔗 Correlation Analysis

Correlation analysis was performed between:

Quantity
Price Per Unit
Total Spent

A heatmap was used to visualize relationships among numerical variables.


# 📅 Trend Identification

Monthly sales trends were analyzed using the Transaction Date column.

The trend analysis helped identify changes in sales over different months.


# 📁 Project Structure

Cafe Sales Project/

├── dirty_cafe_sales.csv

├── clean_cafe_sales.csv

├── Cafe_Sales_Cleaning.ipynb

├── EDA_Cleaned_CafeSales.ipynb

└── README.md


# 🚧 Challenges Faced

During the project, several challenges were encountered:

Handling missing values.
Replacing invalid entries such as UNKNOWN and ERROR.
Converting columns into appropriate data types.
Cleaning numerical columns.
Understanding relationships between different variables.
Presenting findings through simple visualizations.

These challenges helped improve practical knowledge of data cleaning and exploratory data analysis.


# 🔮 Future Improvements

Future enhancements for this project include:

Creating an interactive Power BI dashboard.
Performing predictive analysis using Machine Learning.
Building sales forecasting models.
Adding customer segmentation.
Creating an automated reporting system.


# 🚀 How to Run the Project
Install Required Libraries
pip install pandas numpy matplotlib seaborn
Run the Notebook

Open the notebook in Google Colab or Jupyter Notebook and execute all cells in sequence.


# 👩‍💻 Author

Shlok Sachin Deshpande


# ⭐ Project Highlights

✅ Data Cleaning

✅ Missing Value Handling

✅ Duplicate Removal

✅ Data Type Conversion

✅ Data Quality Report

✅ Exploratory Data Analysis

✅ Statistical Summary

✅ Correlation Analysis

✅ Trend Identification

✅ Insight Documentation

This project demonstrates a complete beginner-friendly data analytics workflow, transforming raw café sales data into clean, meaningful, and analysis-ready information.
