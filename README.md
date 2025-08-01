# Shein_E-commerce_Power-bi_project

SHEIN E-commerce Sales Dashboard
This project analyzes the SHEIN E-commerce dataset using Power BI, with all data cleaning and preprocessing done in Python. It uncovers product sales trends, discount patterns, and category-wise performance. The goal is to provide a clear, interactive dashboard that helps decision-makers identify what drives sales on the SHEIN platform.

# Project Overview
Tools Used: Python (Pandas), Power BI

Dataset Source: Kaggle - https://www.kaggle.com/datasets/oleksiimartusiuk/e-commerce-data-shein?

Raw Data: 21 CSV files

Final Cleaned Dataset: 82,105 rows × 13 columns

# Data Cleaning (Python)
The following preprocessing was done in Python before importing into Power BI:

Combined 21 CSV files into a single DataFrame

Extracted category from file names

Removed unnecessary columns

Converted selling_proposition into numeric selling_count

Handled missing values in key fields like price and goods-title-link

Exported clean data to cleaned_ecommerce.csv

 # Dashboard Features (Power BI)


 <img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/ee2309f8-959e-456a-868d-6c8197457979" />

Visualizations Used
Visual	Description
Matrix Table	Top-selling products by selling_count
Bar Chart	Total sales by product category
Donut Chart	Average discount by category
Card Tiles	Key KPIs: Avg. Price, Total Units Sold, Total Discount
Scatter Plot	Relationship between price and selling_count
Column Chart	Product count by price range (simulated histogram)

# Key Insights
Most products are priced below ₹500

Categories like Women's Clothing and Beauty Accessories have the highest sales

Higher discounts don't always correlate with higher sales

Some categories consistently show high average sales volume

# About Me
I am a Data Analyst Fresher who is passionate about real-world datasets and storytelling with data. This project demonstrates my skills in:

Data Cleaning using Python

Exploratory Data Analysis (EDA)

Interactive Dashboard Creation in Power BI

Business Insight Communication

# Future Scope
Add time-based trend analysis if timestamp data is available

Build predictive models (e.g., top-selling product prediction) in Python

Deploy dashboard using Power BI Cloud Service or SharePoint

