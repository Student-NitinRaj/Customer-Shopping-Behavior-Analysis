# Customer-Shopping-Behavior-Analysis

# 📊 Data Analytics Project

A complete **end-to-end Data Analytics project** covering data loading, exploratory data analysis, data cleaning, SQL analysis, Power BI visualization, and business reporting.

## 📌 Overview

This project demonstrates a practical data analytics workflow, starting from a raw dataset and transforming it into **actionable business insights**.

The project includes:

* Loading and analyzing data using Python
* Exploratory Data Analysis (EDA)
* Data cleaning and preprocessing
* SQL-based data analysis
* Interactive Power BI dashboard
* Analytical report
* Project presentation created using Gamma

---

## 📂 Dataset

The project uses a structured dataset containing business-related records.

### Dataset Workflow

```text
Raw Dataset
     ↓
Python Data Loading
     ↓
Data Cleaning
     ↓
Exploratory Data Analysis
     ↓
SQL Analysis
     ↓
Power BI Dashboard
     ↓
Business Insights & Report
     ↓
Final Presentation
```

---

## 🛠️ Tools & Technologies

| Tool                                | Purpose                      |
| ----------------------------------- | ---------------------------- |
| **Python**                          | Data loading, cleaning & EDA |
| **Pandas**                          | Data manipulation            |
| **NumPy**                           | Numerical analysis           |
| **Matplotlib / Seaborn**            | Data visualization           |
| **PostgreSQL / MySQL / SQL Server** | SQL analysis                 |
| **Power BI**                        | Interactive dashboard        |
| **Gamma**                           | Project presentation         |
| **Excel / CSV**                     | Dataset handling             |

---

## 🔍 Project Steps

### 1. Data Loading

The dataset is imported into Python using Pandas.

```python
import pandas as pd

df = pd.read_csv("dataset.csv")

print(df.head())
print(df.shape)
```

### 2. Exploratory Data Analysis

EDA was performed to understand:

* Dataset structure
* Data types
* Missing values
* Duplicate records
* Numerical statistics
* Categorical variables
* Important patterns and trends

Example:

```python
df.info()
df.describe()
df.isnull().sum()
df.duplicated().sum()
```

### 3. Data Cleaning

The dataset was prepared for analysis by:

* Handling missing values
* Removing duplicates
* Correcting data types
* Cleaning inconsistent values
* Renaming columns where required
* Handling outliers where appropriate

### 4. SQL Analysis

SQL queries were used to answer business questions and extract useful insights.

The project can be executed using:

* PostgreSQL
* MySQL
* SQL Server

Example:

```sql
SELECT
    category,
    COUNT(*) AS total_records
FROM dataset
GROUP BY category
ORDER BY total_records DESC;
```

SQL analysis includes operations such as:

* `SELECT`
* `WHERE`
* `GROUP BY`
* `ORDER BY`
* `JOIN`
* `CASE`
* Aggregate functions
* Subqueries
* Window functions

---

## 📊 Power BI Dashboard

An interactive **Power BI dashboard** was created to present the key findings visually.

### Dashboard Includes

* KPI cards
* Trend analysis
* Category-wise analysis
* Interactive filters/slicers
* Charts and graphs
* Comparative analysis
* Business performance indicators

### Dashboard Preview

> Add your Power BI dashboard screenshot here.

```markdown
![Power BI Dashboard](images/dashboard.png)
```

---

## 📈 Key Results & Insights

The analysis helped identify important:

* Trends and patterns
* High- and low-performing categories
* Business performance indicators
* Customer or product-level insights
* Opportunities for improvement
* Data-driven recommendations

> **Note:** Replace this section with the actual insights obtained from your dataset.

---

## 📄 Project Report

A detailed report was created to document:

1. Business Problem
2. Dataset Description
3. Data Cleaning
4. Exploratory Data Analysis
5. SQL Analysis
6. Power BI Dashboard
7. Key Findings
8. Business Recommendations
9. Conclusion

---

## 🎞️ Project Presentation

A professional presentation was created using **Gamma** to communicate the project workflow, analysis, dashboard, findings, and recommendations.

The presentation covers:

* Project Objective
* Dataset
* Methodology
* Analysis
* Dashboard
* Key Insights
* Recommendations
* Conclusion

---

## 🚀 How to Run

### Step 1 — Clone the Repository

```bash
git clone https://github.com/your-username/your-repository.git
cd your-repository
```

### Step 2 — Install Python Libraries

```bash
pip install pandas numpy matplotlib seaborn
```

### Step 3 — Add Dataset

Place the dataset inside the appropriate project folder.

Example:

```text
project/
│
├── data/
│   └── dataset.csv
│
├── notebooks/
│   └── analysis.ipynb
│
├── sql/
│   └── analysis.sql
│
├── powerbi/
│   └── dashboard.pbix
│
├── report/
│   └── project_report.pdf
│
├── presentation/
│   └── project_presentation.pdf
│
└── README.md
```

### Step 4 — Run the Python Analysis

Open the Jupyter Notebook:

```bash
jupyter notebook
```

Run the analysis notebook step by step.

### Step 5 — Run SQL Queries

Import the cleaned dataset into your preferred database:

* PostgreSQL
* MySQL
* SQL Server

Then execute the SQL scripts from the `sql` folder.

### Step 6 — Open Power BI Dashboard

Open:

```text
powerbi/dashboard.pbix
```

Refresh the data if required.

---

## 💡 Business Value

This project demonstrates how raw data can be transformed into meaningful business insights using a complete analytics workflow:

**Data → Cleaning → Analysis → SQL → Visualization → Insights → Business Decisions**

---

## 👨‍💻 Skills Demonstrated

* Data Analysis
* Exploratory Data Analysis
* Data Cleaning
* Python
* Pandas & NumPy
* SQL
* PostgreSQL / MySQL / SQL Server
* Power BI
* Data Visualization
* Business Intelligence
* Reporting
* Presentation & Storytelling

---

## 📬 Contact

**Nitin Raj**
Data Analyst | Business Analyst | Data Science

* GitHub: `https://github.com/Student-NitinRaj`
* LinkedIn: `https://www.linkedin.com/in/nitin-raj-ai-tech`

---

## ⭐ Project

If you find this project useful, consider giving the repository a **star ⭐** and exploring the other projects in the repository.
