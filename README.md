# 🇮🇳 EV Charging Infrastructure Intelligence — India

## 📌 Project Overview

EV adoption is increasing rapidly in India, making the availability and distribution of public charging infrastructure an important area of analysis.

This project analyzes public EV charging infrastructure data to understand the distribution of charging records across states, Charging Point Operators (CPOs), charger technologies, and Government/Private ownership.

The project combines **Python-based data cleaning and exploratory data analysis** with an interactive **Power BI dashboard**.

---

## 🎯 Objectives

- Analyze the distribution of EV charging infrastructure across states
- Identify major Charging Point Operators (CPOs)
- Compare Government and Private charging infrastructure
- Analyze charger technology distribution
- Identify concentration patterns in the charging network
- Create an interactive Power BI dashboard
- Generate insights that can support further EV infrastructure analysis

---

## 🗂️ Dataset

The dataset contains public EV charging infrastructure records with the following information:

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

The project uses a selected sheet from the source dataset.

---

## 🧹 Data Cleaning

Data preprocessing was performed using **Python and Pandas**.

### Cleaning steps

- Removed exact duplicate records
- Standardized state names
- Standardized charger-type naming
- Fixed formatting issues in CPO names
- Handled missing City/Village values
- Validated numerical columns
- Preserved duplicate coordinates because multiple charger records can legitimately exist at the same location

### Dataset Summary

| Stage | Records |
|---|---:|
| Raw selected dataset | 6,971 |
| Exact duplicates removed | 1,637 |
| Final cleaned dataset | 5,334 |

---

## 📊 Exploratory Data Analysis

The cleaned dataset was analyzed to understand:

- State-wise charging infrastructure distribution
- Government vs Private distribution
- CPO concentration
- Charger technology distribution
- Geographic concentration of charging records

### Key Findings

- The **top 5 states** account for approximately **89.87%** of the cleaned dataset.
- **Government records** account for approximately **57.06%**.
- **Private records** account for approximately **42.94%**.
- The **top 5 CPOs** account for approximately **81.33%** of the cleaned dataset.
- The **top 3 charger categories** account for approximately **68.80%**.

---

## 📈 Power BI Dashboard

The project includes an interactive Power BI dashboard containing:

### Key Performance Indicators

- Charging Records
- States Covered
- CPOs
- Charger Types

### Visual Analysis

- Top 10 States by Charging Records
- Government vs Private distribution
- Top 10 CPOs by Charging Records
- Charger Technology Distribution

### Interactive Filters

- State
- Government / Private

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Data processing and analysis |
| Pandas | Data cleaning and manipulation |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Exploratory visualization |
| Power BI | Interactive dashboard |
| GitHub | Project documentation and version control |

---
