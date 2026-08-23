# customer_behavior_analysis
Data analytics project showcasing customer behavior analysis using python and sql


# 📊 Customer Behavior Analysis

An end-to-end **Data Analytics project** analyzing customer shopping behavior using **Python, SQL, and Power BI**. The project covers the complete analytics workflow — from raw data cleaning and exploratory analysis to SQL-based business analysis, dashboard development, reporting, and presentation.

The goal is to transform raw customer transaction data into **actionable business insights** around purchasing patterns, customer segments, product performance, discounts, subscriptions, and revenue.

---

## 🔎 Overview

This project demonstrates a practical data analytics workflow:

**Raw Dataset → Python EDA & Cleaning → SQL Analysis → Power BI Dashboard → Business Report → Presentation**

The analysis focuses on answering business-oriented questions such as:

* Which customer segments generate the most revenue?
* Which products and categories perform best?
* How does customer subscription status affect purchasing behavior?
* Which customers are repeat or loyal buyers?
* How do discounts influence purchasing behavior?
* Which demographic groups contribute most to sales?
* Which shipping methods are associated with higher spending?

---

## 📂 Dataset

The project uses a **Customer Shopping Behavior** dataset containing customer demographics, purchase information, and shopping behavior.

### Key Data Fields

| Category              | Examples                                        |
| --------------------- | ----------------------------------------------- |
| Customer Demographics | Age, Gender, Location                           |
| Purchase Details      | Item Purchased, Category, Purchase Amount       |
| Shopping Behavior     | Previous Purchases, Frequency, Discount Applied |
| Customer Information  | Subscription Status                             |
| Product Information   | Season, Size, Color                             |
| Customer Feedback     | Review Rating                                   |
| Delivery              | Shipping Type                                   |

The dataset is stored in:

```text
customer_shopping_behavior.csv
```

---

## 🛠️ Tools & Technologies

### Programming & Analysis

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Jupyter Notebook**

### Database & SQL

* **PostgreSQL / MySQL / SQL Server**
* SQL
* SQL-based business analysis

### Visualization & Reporting

* **Microsoft Power BI**
* **Gamma**
* PDF reporting

### Version Control

* **Git**
* **GitHub**

---

## 🔄 Project Workflow

```text
                Raw Dataset
                     │
                     ▼
             Data Loading (Python)
                     │
                     ▼
          Data Cleaning & Validation
                     │
                     ▼
            Exploratory Data Analysis
                     │
                     ▼
             Feature Engineering
                     │
                     ▼
              SQL Database
                     │
                     ▼
             Business SQL Queries
                     │
                     ▼
             Power BI Dashboard
                     │
                     ▼
             Business Report
                     │
                     ▼
            Gamma Presentation
```

---

# 1️⃣ Data Loading & Cleaning

The dataset was loaded into Python using **Pandas** and inspected for data quality issues.

### Data preparation included:

* Loading the raw CSV dataset
* Understanding dataset structure
* Checking data types
* Identifying missing values
* Detecting inconsistent values
* Standardizing column names
* Validating numerical and categorical fields
* Handling missing data
* Creating derived features
* Preparing the cleaned dataset for SQL analysis

The main analysis notebook is:

```text
customer_shopping_behavior (1).ipynb
```

---

# 2️⃣ Exploratory Data Analysis (EDA)

EDA was performed to understand customer behavior and identify patterns before performing deeper SQL analysis.

### Areas explored:

* Customer demographics
* Purchase amount distribution
* Product and category performance
* Customer spending behavior
* Subscription behavior
* Discount usage
* Review ratings
* Shipping preferences
* Repeat purchasing behavior
* Customer segmentation
* Age-group purchasing patterns

Visualizations were created using **Matplotlib and Seaborn**.

---

# 3️⃣ SQL Business Analysis

After cleaning and preparing the dataset, SQL was used to answer business questions and perform structured analysis.

The SQL queries are available in:

```text
customer_behavior_sql_queries.sql
```

### Example business questions

* Revenue by gender
* Revenue by subscription status
* Top-performing products
* Top-rated products
* Average purchase amount by shipping type
* Discount-dependent products
* Customer segmentation
* Repeat customer analysis
* Revenue by age group
* Category-level sales performance

SQL was used to demonstrate practical analytics concepts including:

* `SELECT`
* `WHERE`
* `GROUP BY`
* `ORDER BY`
* `CASE`
* Aggregate functions
* Subqueries
* Customer segmentation logic

---

# 4️⃣ Power BI Dashboard

The cleaned and analyzed data was used to build an interactive **Power BI dashboard**.

### Dashboard focuses on:

* 📌 Revenue KPIs
* 👥 Customer segmentation
* 🛍️ Product and category performance
* 💰 Purchase behavior
* 🎯 Subscription analysis
* ⭐ Customer ratings
* 🚚 Shipping behavior
* 📊 Demographic analysis

### Interactive Analysis

The dashboard enables users to explore the data using filters such as:

* Gender
* Category
* Subscription Status
* Shipping Type
* Customer Segment
* Age Group

> **Dashboard Preview**

Add your Power BI dashboard screenshot here:

```markdown
![Power BI Dashboard](images/dashboard.png)
```

---

# 5️⃣ Business Report

A detailed report was created to document the analysis and communicate the findings in a business-friendly format.

The report covers:

1. Business problem
2. Dataset description
3. Data preparation
4. Exploratory analysis
5. SQL analysis
6. Dashboard findings
7. Key insights
8. Business recommendations

Available report:

```text
Customer Shopping Behavior Analysis.pdf
```

---

# 6️⃣ Presentation

A presentation was created using **Gamma** to communicate the project findings to a non-technical audience.

The presentation summarizes:

* Business problem
* Analytical approach
* Customer behavior patterns
* Key findings
* Dashboard insights
* Business recommendations

---

# 📈 Results & Key Insights

The analysis provides insights into:

### Customer Behavior

Customer purchasing patterns vary across demographic groups, product categories, subscription status, and purchase frequency.

### Customer Segmentation

Customers can be grouped based on their purchasing history to identify new, returning, and loyal customers.

### Product Performance

The analysis identifies high-performing products and categories that contribute significantly to overall sales.

### Subscription Behavior

Subscriber and non-subscriber purchasing behavior can be compared to evaluate whether subscription programs are associated with differences in customer spending.

### Discount Behavior

Discount usage can be analyzed to identify products and customer groups that are more dependent on promotional offers.

### Revenue Analysis

Revenue can be broken down across demographic groups, customer segments, categories, and age groups to identify important revenue drivers.

---

# 💡 Business Recommendations

Based on the analysis, businesses can consider:

* Targeting high-value customer segments with personalized campaigns
* Developing retention strategies for loyal customers
* Optimizing discount strategies
* Promoting high-performing products
* Evaluating subscription conversion opportunities
* Using demographic insights for targeted marketing
* Improving product and inventory planning based on demand patterns

---

# 📁 Project Structure

```text
customer_behavior_analysis/
│
├── customer_shopping_behavior.csv
│
├── customer_shopping_behavior (1).ipynb
│
├── customer_behavior_sql_queries.sql
│
├── Business Problem Document.pdf
│
├── Customer Shopping Behavior Analysis.pdf
│
├── PowerBI/
│   └── customer_behavior_dashboard.pbix
│
├── Presentation/
│   └── customer_behavior_analysis.pptx
│
├── images/
│   └── dashboard.png
│
└── README.md
```

---

# 🚀 How to Run

## 1. Clone the Repository

```bash
git clone https://github.com/iimv23/customer_behavior_analysis.git

cd customer_behavior_analysis
```

## 2. Install Python Dependencies

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

## 3. Run the Python Analysis

Open the notebook using Jupyter:

```bash
jupyter notebook
```

Then open:

```text
customer_shopping_behavior (1).ipynb
```

Run the notebook sequentially to reproduce the data cleaning and EDA.

---

## 4. Run the SQL Analysis

Set up a database using **PostgreSQL, MySQL, or SQL Server**.

Load the cleaned customer dataset into a database table and execute:

```text
customer_behavior_sql_queries.sql
```

The SQL script contains business-oriented queries used to analyze customer behavior and purchasing patterns.

---

## 5. Open the Power BI Dashboard

Open:

```text
customer_behavior_dashboard.pbix
```

If required, update the database connection settings and refresh the dataset.

---

## 6. Review the Report & Presentation

The repository also contains the final business report and presentation used to communicate the findings.

---

# 🎯 Skills Demonstrated

This project demonstrates practical experience in:

* Data Cleaning
* Exploratory Data Analysis
* Data Validation
* Feature Engineering
* Python for Data Analytics
* SQL
* PostgreSQL / MySQL / SQL Server
* Business Intelligence
* Power BI
* Data Visualization
* Customer Segmentation
* Business Analysis
* Insight Generation
* Data Storytelling
* Business Reporting

---

# 📌 Project Deliverables

| Deliverable        | Description                               |
| ------------------ | ----------------------------------------- |
| Python Notebook    | Data loading, cleaning and EDA            |
| SQL Script         | Business questions and analytical queries |
| Power BI Dashboard | Interactive visualization and KPIs        |
| Business Report    | Detailed analysis and recommendations     |
| Gamma Presentation | Executive-level project summary           |

---

## 👨‍💻 Author

**Prasanth Ayitapu**

Data Scientist / Data Analytics

[GitHub](https://github.com/iimv23)

---

## ⭐ Project Objective

The objective of this project is to demonstrate how **Python, SQL, and Power BI can be combined into an end-to-end analytics workflow** to transform raw customer transaction data into actionable business insights.
