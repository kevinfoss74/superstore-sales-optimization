# 🚀 Predictive Sales Optimization & Operational Classification

**UTN Data Science / Data Analytics Capstone Project**  
**Author:** Kevin Foss  

---

## 📌 Project Overview
End-to-end data science pipeline developed to solve logistical inefficiencies and stock immobilization in retail operations using the **Superstore** dataset. The system integrates data preprocessing, relational database management, and machine learning classification models to optimize dispatch timing, prioritize high-impact transactions, and reduce operational costs.

---

## 🛠️ Tech Stack & Libraries
* **Programming Language:** Python  
* **Machine Learning & Data Processing:** Scikit-Learn, Pandas, NumPy, Matplotlib, Seaborn  
* **Database & Querying:** SQL Server Management Studio (SSMS)  
* **Business Intelligence & Dashboards:** Power BI, Power Query, DAX  

---

## ⚙️ Pipeline Architecture & Methodology

1. **Data Cleaning & Preprocessing (Python & SQL):**
   * Handled missing values, standardized categorical variables, and managed date-time formats.
   * Built relational structures and aggregated tables using **SQL** to structure customer and regional transactions.

2. **Exploratory Data Analysis (EDA) & Feature Engineering:**
   * Analyzed regional sales trends, categorical variables vs. regional performance, and shipping delays.
   * Engineered critical predictive features to feed the classification models.

3. **Machine Learning Modeling:**
   * Developed supervised classification algorithms using **Scikit-Learn** to segment high-impact transactions and predict operational bottlenecks.
   * Evaluated performance metrics (Accuracy, Precision, Recall, F1-Score) to ensure model reliability.

4. **Business Intelligence & Visualization:**
   * Designed executive dashboards in **Power BI** leveraging Power Query and DAX measures.
   * Focused visualizations on clear categorical comparisons and operational KPIs to track shipping costs and dispatch times.

---

## 📈 Key Results & Impact
* **Operational Prioritization:** Successfully segmented transactions to identify high-risk delivery delays.
* **Cost Reduction:** Streamlined dispatch workflows, leading to an estimated reduction in logistical overhead and inventory immobilization times.
* **Decision Making:** Provided stakeholders with an interactive BI framework for rapid tracking of regional sales and shipping performance.

---

## 📂 Repository Structure
```text
├── data/                  # Cleaned datasets and SQL dumps
├── notebooks/             # Jupyter notebooks for EDA and ML modeling
├── powerbi/               # Power BI dashboard files (.pbix)
├── scripts/               # Python modular scripts for pipeline automation
└── README.md
