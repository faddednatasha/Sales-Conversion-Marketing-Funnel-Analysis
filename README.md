# Sales-Conversion-Marketing-Funnel-Analysis
---
This project focuses on Conversion Rate Optimization (CRO) by analyzing the journey of a prospect from initial contact to final sale. By leveraging a combination of Python for deep-dive analytics and SQL for structured querying, this repository provides a blueprint for identifying "leaks" in a sales funnel.

---

## 🎯 Business Objective
The goal of this project is to identify where potential customers drop off in the sales process and provide data-driven recommendations to increase the overall **Conversion Rate (CVR)**.

### 🎯 Key Questions Addressed:
* **Friction Points:** Which stage of the funnel has the highest churn?
* **Segmentation:** Do specific demographics (Age, Education, Income) convert at significantly higher rates?
* **ROI:** Which marketing channels provide the highest quality leads?

---
## 📌 Highlights

- 🔄 End‑to‑end workflow: **clean → analyze → visualize → recommend**
- 📉 Funnel metrics: stage‑wise **conversion & drop‑off rates**
- 🧪 Statistical checks: correlation, significance tests, uplift hints
- 🧾 SQL recipes for fast insight queries
- 📊 Polished visuals for stakeholders

---

## 🗂️ Project Structure

```
├── Data_exploration_cleaning.ipynb            # Ingest, clean, feature prep
├── Exploratory_statistical_analysis.ipynb     # EDA, stats, correlations
├── Visualization.ipynb                        # Funnel, cohorts, segments
├── sql_tasks.sql                              # Reusable SQL insights
├── cleaned_marketing_data.csv                 # Cleaned/processed data
└── MARKETING_DATA.xls                         # Raw source (example)
```

## 🛠️ Data Pipeline & Workflow

1.  **Data Cleaning (`Data_exploration_cleaning.ipynb`)**
    * Handled missing values and outliers in `MARKETING_DATA.xls`.
    * Feature engineering: Created "Days to Convert" and "Lead Score" metrics.
    * Exported `cleaned_marketing_data.csv` for downstream analysis.

2.  **Statistical Analysis (`Exploratory_statistical_analysis.ipynb`)**
    * Performed Correlation Matrix analysis to find drivers of conversion.
    * Conducted T-Tests/ANOVA to check if income levels significantly impact purchase behavior.

3.  **Advanced Visualization (`Visualization.ipynb`)**
    * Built **Funnel Charts** to visualize the leakages at each stage.
    * Created Cohort Analysis and Segmented Bar Charts for stakeholder reporting.

4.  **Database Integration (`Sql_task.sql`)**
    * Written optimized queries for rapid KPI extraction (e.g., Monthly Conversion Trends).

---

## 🧰 Tech Stack

- **Python**: pandas, numpy, scipy, scikit‑learn (light), matplotlib, seaborn, plotly
- **SQL**: ad‑hoc analysis via `SQL Tasks.sql`
- **Jupyter Notebooks** for narrative analytics

> Optional extensions: **Power BI / Tableau**, **Streamlit/Dash** for interactive reporting.

---

Run in order:
1) `Data_exploration_cleaning.ipynb`  
2) `Exploratory_statistical_analysis.ipynb`  
3) `Visualization.ipynb`  
4) (Optional) Execute `sql_tasks.sql` in your SQL client.

---

## 🧪 Typical Analyses Included

- **Data Quality**: missing values, outliers, type fixes, feature engineering
- **EDA**: distributions, bivariate analysis, correlation heatmaps
- **Funnel Views**: Awareness → Interest → Consideration → Action
- **Segmentation**: channel, country, age, education, income
- **Stats**: proportion tests, confidence intervals, effect‑size indicators
- **Visuals**: funnel charts, bar/line charts, box plots, cohort views

---

## 📌 Reproducibility

- Notebooks are **ordered** for stepwise execution.
- Use a **seed** for stochastic steps where applicable.
- Keep raw vs cleaned data in **separate folders**.
- Document any **manual transformations** in the cleaning notebook.

---

## 🚀 How to Use
1. Clone the repository.
2. Install dependencies: `pip install pandas matplotlib seaborn plotly scipy`.
3. Run the notebooks in the numbered order: **Cleaning → Stats → Visualization**.
---
