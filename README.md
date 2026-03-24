# My-first-practice
This project analyzes sales data using Python
# 📈 Sales Data Analysis Project

## 📝 Project Overview
This project presents a comprehensive data analysis of a sales records dataset using Python. The goal is to explore sales performance, identify trends, and generate actionable insights for business decision-making.

---

## 🎯 Objectives
- Analyze overall sales and profit performance
- Identify top-performing product categories
- Understand customer and regional behavior
- Evaluate sales representative performance
- Detect trends over time
- Examine relationships between key variables

---

## 📂 Dataset Description
The dataset contains transactional sales data with features such as:

- Order_ID
- Order_Date
- Product_Name
- Product_Category
- Quantity
- Unit_Price
- Total_Sales
- Profit
- Discount
- Customer_Name
- Gender
- Region
- Sales_Rep
- Payment_Method

---

## ⚠️ Data Issues Identified
During initial exploration, the following issues were found:

- Missing values in numeric and categorical columns
- Duplicate records
- Incorrect data types (e.g., date format)
- Inconsistent or empty categorical entries

---

## 🧹 Data Cleaning Process
The following steps were performed:

- Converted `Order_Date` to datetime format
- Removed duplicate rows
- Filled missing numeric values using median:
  - Quantity
  - Unit Price
  - Total Sales
  - Profit
- Replaced missing categorical values with:
  - Mode (e.g., Gender, Region)
  - "Unknown" for text fields
- Dropped rows with invalid dates

---

## 🏗️ Feature Engineering
New features were created to enhance analysis:

- Year
- Month
- Month Name
- Quarter
- Profit Margin (%)

---

## 📊 Exploratory Data Analysis (EDA)

### 🔹 Categorical Analysis
- Distribution of:
  - Gender
  - Region
  - Product Category
  - Payment Method
  - Sales Representatives

### 🔹 Numerical Analysis
- Histograms of:
  - Quantity
  - Unit Price
  - Total Sales
  - Profit
  - Discount

---

## 📈 Key Visualizations

### 📊 Sales by Product Category
- Horizontal bar chart showing total revenue per category

### 📅 Monthly Trends
- Line chart showing:
  - Total Sales over time
  - Profit over time

### 🌍 Regional Performance
- Bar chart of total profit by region

### 💳 Payment Method Distribution
- Donut chart showing percentage usage

### 👨‍💼 Sales Representative Performance
- Comparison of:
  - Total Sales
  - Profit

### 🔥 Correlation Heatmap
- Shows relationships between:
  - Sales
  - Profit
  - Discount
  - Quantity

### 📦 Category & Region Heatmap
- Sales distribution across product categories and regions

---

## 📊 Advanced Analysis
- Boxplots for:
  - Sales distribution by product category
  - Profit distribution by region
- Gender-based purchasing behavior
- Pivot table analysis for deeper insights

---

## 💡 Key Insights
- Certain product categories generate significantly higher revenue
- Sales and profit trends fluctuate over time
- Some regions outperform others in profitability
- Sales representatives have varying performance levels
- Discounts and pricing impact profit margins

---

## 🧠 Business Questions Answered
- Which product categories drive the most revenue?
- How do sales trends change over time?
- Which regions are most profitable?
- How effective are sales representatives?
- What factors influence profit?

---

## 🛠️ Tools & Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Jupyter Notebook

---

## ▶️ How to Run the Project

1. Install required libraries:
```bash
pip install pandas numpy matplotlib seaborn plotly openpyxl

**📌 Conclusion**
This analysis provides valuable insights into sales performance, customer behavior, and business trends. The results can support data-driven decision-making to improve profitability and operational efficiency.

📎 Author
IYOHA (Tega Emmanuel)
📊 Data Analyst |💻 Python Enthusiast |🎨 Interior Designer 
