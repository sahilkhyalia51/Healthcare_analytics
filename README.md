# 🏥 Healthcare Analytics

An end-to-end healthcare analytics project that transforms raw healthcare data into actionable business insights using **Python, MySQL, and Power BI**. The project focuses on hospital performance, patient admissions, billing analysis, insurance claims, and operational KPIs.

---

# 📊 Dashboard

> **Dashboard Preview**

<p align="center">
  <img src="dashboard/dashboard.png" width="900">
</p>

---

# 📁 Dataset

| Attribute | Details |
|-----------|---------|
| **Source** | Synthetic Healthcare Dataset ([Kaggle](https://www.kaggle.com/datasets/prasad22/healthcare-dataset)) |
| **Records** | 55,500 |
| **Original Features** | 15 |
| **Final Features** | 16 (after feature engineering) |
| **File Format** | CSV |
| **Data Type** | Synthetic (No real patient information) |

### Dataset Features

- Patient Demographics
- Hospital & Doctor Information
- Medical Conditions
- Admission & Discharge Details
- Insurance Providers
- Billing Amount
- Medications
- Laboratory Test Results

### Feature Engineering

Added one analytical feature:

- **Length of Stay** = Discharge Date − Admission Date

---

# 📈 Business Questions Answered

- Which hospitals generate the highest revenue?
- Which hospitals treat the highest number of patients?
- Which medical conditions generate the highest billing?
- Which insurance providers contribute the highest claim amounts?
- Which doctors handle the largest patient volume?
- Which admission type generates the highest revenue?
- Which hospitals have the highest average billing per patient?
- Which medical conditions require the longest hospital stay?
- Which medications are prescribed most frequently for each medical condition?
- Among hospitals with at least 100 patients, which hospitals have the highest average billing and patient stay?

---

# ⚙️ Tech Stack

- 🐍 Python (Pandas)
- 🗄️ MySQL
- 🔗 SQLAlchemy
- 📊 Power BI
- 📓 Jupyter Notebook
- 🌿 Git & GitHub

---

# 📂 Repository Structure

```
Healthcare_analytics
│
├── data/                  # Raw and cleaned datasets
├── notebooks/             # Data cleaning & feature engineering
├── sql/                   # Business SQL queries
├── dashboard/             # Power BI dashboard (.pbix)
└── README.md
```
