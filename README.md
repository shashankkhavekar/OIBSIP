# OASIS INFOBYTE – Data Analytics Internship

## Task 1: Exploratory Data Analysis (EDA) on Retail Sales Data

### Project Overview

This project focuses on performing Exploratory Data Analysis (EDA) on a retail sales dataset containing 100,000 transaction records.

The main objective is to understand sales performance, customer purchasing behaviour, product performance, and business trends using Python.

Through data cleaning, statistical analysis, and data visualization, this project aims to identify meaningful patterns and generate actionable business insights.

### Project Objective

- Analyze retail sales transactions.
- Understand customer purchasing behaviour.
- Identify top-performing products and categories.
- Analyze monthly and quarterly sales trends.
- Discover useful business insights and recommendations.

## Dataset Information

The dataset used in this project is a synthetic retail sales dataset created for educational and analytical purposes.

### Dataset Details

- **Dataset Name:** OASIS_Retail_Sales_Dataset_100K.csv
- **Total Records:** 100,000 transactions
- **Original Columns:** 15
- **Date Range:** January 2023 – December 2025
- **Data Type:** Retail transaction data
- **Format:** CSV

### Important Dataset Columns

| Column | Description |
|---|---|
| Transaction_ID | Unique transaction identifier |
| Date | Transaction date |
| Customer_ID | Customer identifier |
| Customer_Age | Customer age |
| Gender | Customer gender |
| Product_Category | Product category |
| Product_Name | Product name |
| Quantity | Purchased quantity |
| Unit_Price | Price per unit |
| Discount_Percentage | Discount applied |
| Total_Amount | Transaction amount |
| City | Customer city |
| Payment_Method | Payment method |
| Sales_Channel | Online or in-store |
| Store_ID | Store identifier |

**Note:** This is a synthetic dataset for learning and demonstration. It does not contain actual OASIS INFOBYTE business data.


## Technologies Used

The following tools and libraries were used in this project:

| Technology | Purpose |
|---|---|
| Python | Main programming language |
| Pandas | Data cleaning and manipulation |
| NumPy | Numerical calculations |
| Matplotlib | Data visualization |
| Seaborn | Statistical charts and heatmaps |
| Google Colab | Development environment |
| Jupyter Notebook | Writing and executing analysis code |

### Why These Technologies?

- **Python:** Used to perform the complete analysis.
- **Pandas:** Used to load, clean, filter, and analyze data.
- **NumPy:** Used for numerical operations.
- **Matplotlib:** Used to create charts and graphs.
- **Seaborn:** Used to create advanced statistical visualizations.
- **Google Colab:** Used to execute Python code online.

## Project Workflow

The project was completed through the following stages:

### 1. Data Loading
- Imported the required Python libraries.
- Loaded the retail sales CSV dataset using Pandas.

### 2. Data Understanding
- Checked dataset shape and column names.
- Inspected the first and last records.
- Checked data types and statistical summaries.
- Identified missing values and duplicate records.

### 3. Data Cleaning
- Handled missing values.
- Checked duplicate records.
- Converted the Date column into datetime format.
- Checked invalid and inconsistent values.

### 4. Feature Engineering
- Extracted year, month, and quarter from transaction dates.
- Created customer age groups.
- Prepared revenue information for analysis.

### 5. Exploratory Data Analysis
- Performed univariate analysis.
- Compared sales across different categories.
- Analyzed customer purchasing behaviour.
- Studied product and category performance.

### 6. Time Series Analysis
- Analyzed monthly sales trends.
- Compared quarterly sales performance.
- Identified high- and low-performing periods.

### 7. Customer Analysis
- Analyzed customer age groups and gender distribution.
- Identified top customers.
- Examined customer spending patterns.

### 8. Product Analysis
- Identified top-selling products.
- Compared product category revenue.
- Analyzed product demand.

### 9. Correlation Analysis
- Created a correlation matrix.
- Used a heatmap to understand relationships between numerical variables.

### 10. Business Insights
- Analyzed city-wise sales.
- Examined discount patterns.
- Compared sales channels.
- Developed actionable business recommendations.

## Project Folder Structure

```text
OIBSIP/
│
└── DataAnalytics-L1-EDARetailSales/
    │
    ├── data/
    │   ├── OASIS_Retail_Sales_Dataset_100K.csv
    │   └── OASIS_Retail_Sales_Cleaned.csv
    │
    ├── outputs/
    │   ├── charts/
    │   ├── descriptive_statistics.csv
    │   └── business_summary.csv
    │
    ├── OASIS_Retail_Sales_EDA.ipynb
    │
    └── README.md
```

### Folder Description

- **data/** – Contains the original and cleaned retail sales datasets.
- **outputs/** – Contains charts, statistical results, and business summaries.
- **charts/** – Stores exported visualization images.
- **OASIS_Retail_Sales_EDA.ipynb** – Contains the complete Python analysis.
- **README.md** – Explains the project, workflow, and findings.



## Key Analysis and Visualizations

The project includes the following data visualizations:

### 1. Univariate Analysis
- Customer age distribution.
- Gender distribution.
- Product category distribution.
- Payment method distribution.
- Sales channel distribution.

### 2. Bivariate Analysis
- Revenue by gender.
- Revenue by product category.
- Revenue by sales channel.
- Relationship between quantity and revenue.
- Revenue by customer age group.

### 3. Time Series Analysis
- Monthly sales trend.
- Quarterly sales trend.
- Yearly revenue comparison.

### 4. Customer Analysis
- Customer age-group distribution.
- Gender-wise customer analysis.
- Top 10 customers by revenue.
- Average customer spending.

### 5. Product Analysis
- Top 10 best-selling products.
- Top 10 products by revenue.
- Revenue by product category.

### 6. Correlation Analysis
- Correlation matrix.
- Numerical variable heatmap.

### 7. Advanced Business Analysis
- City-wise revenue comparison.
- Discount versus revenue analysis.
- Sales channel performance.
- Monthly revenue heatmap.

All visualizations were created using Matplotlib and Seaborn.


## Key Findings

The analysis focuses on identifying:

- Best-performing product categories.
- Top-selling products.
- Monthly and quarterly sales patterns.
- Customer purchasing behaviour.
- Revenue contribution by sales channel.
- City-wise sales performance.
- Relationships between numerical variables.

## Business Recommendations

Based on the analysis, the following recommendations can help improve retail business performance:

### 1. Inventory Management
Maintain sufficient stock of high-demand products to reduce stockouts.

### 2. Customer Segmentation
Create targeted marketing campaigns based on customer age groups and purchasing behaviour.

### 3. Product Strategy
Focus on products and categories that generate higher revenue.

### 4. Sales Channel Optimization
Compare online and in-store performance to identify opportunities for improving sales.

### 5. Discount Optimization
Evaluate discount strategies to improve revenue while maintaining profitability.

### 6. Regional Sales Strategy
Develop targeted promotions for cities with lower sales performance.

**Note:** Specific findings and recommendations should be finalized using the actual results from the completed analysis.

## How to Run This Project

Follow these steps to run the project:

### Step 1: Clone the Repository

```bash
git clone https://github.com/shashankkhavekar/OIBSIP.git
```

### Step 2: Open the Project Folder

```bash
cd OIBSIP/DataAnalytics-L1-EDARetailSales
```

### Step 3: Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Step 4: Open Jupyter Notebook

```bash
jupyter notebook
```

### Step 5: Run the Notebook

Open `OASIS_Retail_Sales_EDA.ipynb` and execute the cells from top to bottom.

### Alternative: Google Colab

1. Download the notebook from GitHub.
2. Open Google Colab.
3. Upload the notebook.
4. Upload the required CSV dataset when prompted.
5. Run all notebook cells.

## Author

**Shashank Khavekar**

Aspiring Data Analyst | B.Tech – Artificial Intelligence and Data Science

- **GitHub:** https://github.com/shashankkhavekar
- **LinkedIn:** https://linkedin.com/in/shashankkhavekar

## Internship Information

- **Organization:** OASIS INFOBYTE
- **Internship Track:** Data Analytics
- **Task:** Task 1 – EDA on Retail Sales Data
- **Project Type:** Exploratory Data Analysis

---

## Acknowledgement

I would like to thank OASIS INFOBYTE for providing this internship opportunity to improve my practical knowledge and data analytics skills.

