# 🇮🇳 EV Charging Infrastructure Intelligence — India

## 📌 Project Overview

This project analyzes India's EV public charging infrastructure to understand the distribution of charging records across states, Charging Point Operators (CPOs), charger technologies, and government/private ownership.

The project combines Python-based data cleaning and exploratory data analysis with an interactive Power BI dashboard.

---

## 🎯 Objectives

- Analyze the distribution of EV charging infrastructure across states
- Identify major Charging Point Operators (CPOs)
- Compare Government and Private charging infrastructure
- Analyze different charger technologies
- Identify concentration patterns in India's EV charging infrastructure
- Build an interactive Power BI dashboard for business-style analysis

---

## 🗂️ Dataset

The dataset contains public EV charging infrastructure records with information including:

- CPO Name
- Government / Private
- State
- District
- City / Village
- Location
- Latitude
- Longitude
- Charger Type
- Charger Rating
- Connector Rating
- Number of Connectors

The analysis uses a selected sheet from the source dataset.

---

## 🧹 Data Cleaning

Data preprocessing was performed using Python and Pandas.

Major cleaning steps included:

- Removed exact duplicate records
- Standardized state names
- Standardized charger-type naming
- Fixed formatting issues in CPO names
- Handled missing City/Village values
- Validated numerical columns
- Preserved duplicate coordinates where they represented legitimate multiple charger records

### Dataset Size

| Stage | Records |
|---|---:|
| Raw selected dataset | 6,971 |
| Exact duplicates removed | 1,637 |
| Final cleaned dataset | 5,334 |

---

## 📊 Exploratory Data Analysis

Key findings from the cleaned dataset:

- The top 5 states account for approximately **89.87%** of the dataset.
- Government records account for approximately **57.06%**.
- Private records account for approximately **42.94%**.
- The top 5 CPOs account for approximately **81.33%** of the dataset.
- The top 3 charger categories account for approximately **68.80%** of the dataset.

---

## 📈 Power BI Dashboard

The interactive dashboard provides:

- Total charging records
- States covered
- Number of CPOs
- Charger technology count
- Top 10 states by charging records
- Government vs Private distribution
- Top 10 CPOs
- Charger technology distribution
- State filtering
- Government / Private filtering

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Power BI
- Jupyter Notebook
- Git & GitHub

---

## 📁 Project Structure

```text
EV Charging Intelligence India/
│
├── Raw/
│
├── Processed/
│   └── EV_Cleaned_Data.csv
│
├── PowerBI/
│   └── EV_Charging_Intelligence_India.pbix
│
├── notebooks/
│   └── EV_Charging_Analysis.ipynb
│
└── README.md