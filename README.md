# Customer Shopping Behavior Analysis

## 📌 Project Overview

This project presents an end-to-end data analytics workflow focused on analyzing customer shopping behavior using transactional data. The objective is to uncover insights related to customer demographics, purchasing patterns, product performance, subscription behavior, discounts, and revenue trends.

The workflow combines Python for data cleaning and preparation, PostgreSQL for data storage and SQL analysis, and Power BI for interactive dashboard creation and business reporting.

---

## 🎯 Objectives

- Analyze customer purchasing behavior and spending patterns.
- Identify high-performing products and categories.
- Evaluate the impact of discounts and subscriptions.
- Segment customers based on purchase history.
- Create interactive dashboards for business decision-making.
- Generate actionable business recommendations.

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|----------|
| Python | Data Cleaning, Transformation, and Analysis |
| Pandas | Data Manipulation |
| PostgreSQL | Database Storage and SQL Analysis |
| SQL | Business Querying and Analysis |
| Power BI | Data Visualization and Dashboarding |
| Jupyter Notebook | Development Environment |
| PowerPoint | Presentation of Findings |

---

## 📂 Project Structure

```text
Customer-Shopping-Behavior-Analysis/
│
├── customer_shopping_behavior.xlsx
├── customer_shopping_behavior_analysis.ipynb
├── customer_shopping_behavior_sql_analysis.sql
├── Customer_Shopping_Behavior_Dashboard.pbix
├── Customer_Shopping_Behavior_Analysis_Presentation.pptx
├── Customer_Shopping_Behavior_Analysis.pdf
└── README.md
```

---

## 📊 Dataset Information

The dataset contains customer shopping transaction records with demographic, behavioral, and purchase-related information.

### Key Attributes

- Age
- Gender
- Location
- Subscription Status
- Item Purchased
- Category
- Purchase Amount
- Season
- Size
- Color
- Discount Applied
- Previous Purchases
- Frequency of Purchases
- Review Rating
- Shipping Type

### Dataset Statistics

| Metric | Value |
|----------|----------|
| Records | 3,900 |
| Features | 18 |

---

## 🔍 Workflow

### 1. Data Preparation using Python

The dataset was analyzed and cleaned using Python.

#### Activities Performed

- Loaded and explored the dataset.
- Identified missing values.
- Imputed missing values in the Review Rating column.
- Standardized column names using snake_case.
- Performed feature engineering.
- Validated data consistency.
- Removed redundant columns.

#### Feature Engineering

- Created `age_group`
- Created `purchase_frequency_days`

---

### 2. Database Integration

After preprocessing, the cleaned dataset was loaded into PostgreSQL for structured analysis.

#### Steps

1. Establish PostgreSQL database connection.
2. Create required database table.
3. Load cleaned dataset into PostgreSQL.
4. Validate successful data insertion.

---

### 3. SQL Analysis

Business-focused SQL queries were executed in PostgreSQL to answer key analytical questions.

#### Analysis Performed

- Revenue by Gender
- High-Spending Discount Users
- Top 5 Products by Rating
- Shipping Type Comparison
- Subscribers vs Non-Subscribers
- Discount-Dependent Products
- Customer Segmentation
- Top 3 Products per Category
- Repeat Buyers and Subscription Analysis
- Revenue by Age Group

---

### 4. Power BI Dashboard [Dashboard_Link](https://app.fabric.microsoft.com/view?r=eyJrIjoiM2E5ZDgwYWMtMjA0MS00YjhlLTgwOWItYWE1ZDViYWVlMTU2IiwidCI6IjY3OWY5YTYyLTIwODQtNGI0Yy1iNzk2LWI1NGFkZTM5ZmUxYiJ9)

An interactive Power BI dashboard was created to visualize the results of the analysis.

#### Dashboard Highlights

- Revenue Analysis
- Customer Demographics
- Product Performance
- Customer Segmentation
- Subscription Insights
- Discount Analysis

  ![Image alt](https://github.com/GaganBP/Customer_behaviour_analysis/blob/5f5e9382999967ec909c0988996bc073c3dd068d/customer%20dashboard.png)

---

### 5. Business Recommendations

Based on the analysis, the following recommendations were proposed:

- Promote subscription programs through exclusive benefits.
- Implement loyalty programs for repeat customers.
- Optimize discount strategies to improve profitability.
- Highlight top-rated and high-performing products.
- Focus marketing efforts on high-revenue customer segments.

---

## 📈 Key Insights

- Customer purchasing behavior varies across demographic groups.
- Certain products show strong dependency on discounts.
- Loyal customers contribute significantly to overall transactions.
- Subscription status influences purchasing patterns.
- Product ratings can help identify high-potential products for promotion.

---

## 🚀 How to Use

### Run Python Analysis

Open and execute:

```bash
customer_shopping_behavior_analysis.ipynb
```

### Run SQL Analysis

Execute:

```sql
customer_shopping_behavior_sql_analysis.sql
```

within PostgreSQL.

### Open Dashboard

Open:

```text
Customer_Shopping_Behavior_Dashboard.pbix
```

using Power BI Desktop.

### Review Presentation

Open:

```text
Customer_Shopping_Behavior_Analysis_Presentation.pptx
```

for a summary of findings and recommendations.

---

## 📄 Deliverables

- Cleaned and analyzed dataset
- Python analysis notebook
- PostgreSQL SQL analysis script
- Power BI dashboard
- Project presentation
- Project report

---

## 👨‍💻 Author

**Gagan B P**

Data Analytics Project
