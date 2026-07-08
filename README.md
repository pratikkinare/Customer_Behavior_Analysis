# 📊 Data Analytics Project

## Overview
This project demonstrates an end-to-end data analytics workflow — from raw data to business insights. It covers data loading and cleaning in Python, exploratory data analysis (EDA), SQL-based querying using MySQL Server, an interactive Power BI dashboard, and a final presentation summarizing key findings and recommendations.

The goal of this project is to showcase practical, real-world analytics skills: taking messy data, cleaning and analyzing it, storing/querying it in a relational database, and communicating results in a clear, visual, and business-friendly format.

## Dataset
- **Format:** CSV
- **Size:** 3900 rows and 18 columns 
- **Description:** •	Customer demographics (Age, Gender, Location, Subscription Status)
•	Purchase details (Item Purchased, Category, Purchase Amount, Season, Size, Color)
•	Shopping behavior (Discount Applied, Promo Code Used, Previous Purchases, Frequency of Purchases, Review Rating, Shipping Type)
•	Missing Data : 37 values in Review Rating column


## Tools & Technologies
| Category | Tool |
|---|---|
| Programming | Python (Pandas, NumPy, Matplotlib/Seaborn) |
| Database | MySQL Server |
| Visualization | Power BI |
| Presentation | Gamma |
| Documentation | Markdown / Word |

## Project Steps

### 1. Data Loading
- Imported the raw dataset into Python using Pandas.
- Performed an initial inspection (data types, shape, missing values).

### 2. Data Cleaning
- Handled missing and duplicate values.
- Standardized column names and data formats.
- Fixed inconsistent entries (e.g., typos, date formats, categorical values).

### 3. Exploratory Data Analysis (EDA)
- Analyzed distributions, trends, and correlations using summary statistics and visualizations.
- Identified key patterns and outliers relevant to the business question.

### 4. SQL Analysis (MySQL Server)
- Loaded the cleaned dataset into a MySQL database.
- Wrote SQL queries to extract, aggregate, and validate insights (e.g., joins, group by, window functions).
- Cross-verified findings from Python EDA using SQL queries.

### 5. Power BI Dashboard
- Connected Power BI to the cleaned dataset/MySQL database.
- Built interactive visuals (KPIs, trend charts, filters/slicers) to explore the data.
- Designed the dashboard for clarity and quick decision-making.

### 6. Reporting
- Compiled key findings, methodology, and recommendations into a written report.

### 7. Presentation
- Created a summary presentation using **Gamma**, highlighting the problem, approach, and key insights for a non-technical audience.

## Dashboard
The Power BI dashboard includes:
- **KPI Summary Cards** — high-level metrics at a glance
- **Trend Analysis** — performance over time
- **Category Breakdown** — comparison across segments/groups
- **Interactive Filters** — dynamic exploration by date, category, region, etc.

📎 *<img width="1118" height="631" alt="13  Power BI Dashboard" src="https://github.com/user-attachments/assets/07399a50-0d52-45e1-b8c7-b3872c896cab" />


## Results
- [Insight 1 — e.g., "Sales grew by X% in Q3, driven primarily by..."]
- [Insight 2 — e.g., "Customer churn was highest in..."]
- [Insight 3 — e.g., "Top-performing category/region was..."]
- [Recommendation based on findings]

## How to Run

### Prerequisites
- Python 3.x
- MySQL Server
- Power BI Desktop

### Steps
1. **Clone the repository**
   ```bash
   git clone <repository-link>
   cd <repository-folder>
   ```
2. **Install Python dependencies**
   ```bash
   pip install pandas numpy matplotlib seaborn mysql-connector-python
   ```
3. **Run the data cleaning & EDA script**
   ```bash
   python eda_cleaning.py
   ```
4. **Set up the MySQL database**
   - Create a database in MySQL Server.
   - Import the cleaned dataset using the provided `.sql` script or MySQL Workbench.
   - Run the queries in `queries.sql` to reproduce the analysis.
5. **Open the Power BI file**
   - Open `dashboard.pbix` in Power BI Desktop.
   - Refresh the data connection if needed.
6. **View the report and presentation**
   - Report: `report.pdf` / `report.docx`
   - Presentation: `presentation_link` (created using Gamma)

## Project Structure
```
├── data/
│   ├── raw_data.csv
│   └── cleaned_data.csv
├── notebooks/
│   └── eda_cleaning.ipynb
├── sql/
│   └── queries.sql
├── dashboard/
│   └── dashboard.pbix
├── report/
│   └── report.pdf
├── presentation/
│   └── presentation_link.txt
└── README.md
```

## Author
**Pratik Kinare**
📧 pratikkinare007@gmail.com | 🔗 https://www.linkedin.com/in/pratik-kinare007/ | 💻 https://github.com/pratikkinare # Customer_Behavior_Analysis
Customer Shopping Behavior Analysis — Python &amp; SQL project analyzing 3,900 retail transactions to uncover spending patterns, customer segments, and subscription trends, visualized in an interactive Power BI dashboard.
