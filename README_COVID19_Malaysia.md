
# 🦠 COVID-19: Analyzing Trends and Government Interventions in Malaysia

![Malaysia COVID-19](https://upload.wikimedia.org/wikipedia/commons/thumb/6/6e/Flag_of_Malaysia.svg/320px-Flag_of_Malaysia.svg.png)

[![Python](https://img.shields.io/badge/Python-3.10-blue.svg)](https://www.python.org/downloads/release/python-3100/)  
[![Pandas](https://img.shields.io/badge/Library-pandas-informational)](https://pandas.pydata.org/)  
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)  
[![Jupyter](https://img.shields.io/badge/Notebook-Jupyter-orange)](https://jupyter.org)

---

## 📊 Overview and Introduction

This data science project analyzes COVID-19 trends and public health interventions in **Malaysia** from 2020 to 2022. The project uses publicly available data from [Google COVID-19 Open Data](https://health.google.com/covid-19/open-data/raw-data?loc=MY) and leverages Python to perform data cleaning, transformation, and descriptive analysis.

The focus is to:
- Understand the spread of COVID-19 over time.
- Analyze the impact of government policies like lockdowns, school closures, and vaccination campaigns.

---

## 📁 Dataset Overview

Key data sources and features:

- 🧬 **COVID-19 Statistics**: New cases, deaths, tests, and vaccinations.
- 🏛 **Government Responses**: Policies such as lockdowns, facial covering mandates, and travel restrictions.
- 📈 **Derived Metrics**: Positive Test % and Case Fatality %

---

## 🎯 Objectives

- Examine temporal trends in COVID-19 statistics.
- Visualize and interpret government interventions.
- Identify correlations between policy changes and pandemic dynamics.
- Provide actionable insights for public health response and future preparedness.

---

## 🧹 Data Cleaning & Preparation

Steps taken:
- ✔ Removed irrelevant and duplicate data
- ✔ Handled missing values (using 0 or row removal)
- ✔ Converted categorical policy variables for analysis
- ✔ Created new indicators like:
  - Positive Test % = New Confirmed / New Tested
  - Case Fatality % = New Deceased / New Confirmed

---

## 📈 Analysis & Visualizations

Visual insights include:

### 📌 Government Policy Timeline

> ![Placeholder for policy timeline plot](https://via.placeholder.com/700x300?text=Policy+Timeline+Plot)

Visualizes when policies (e.g., school closures, lockdowns) were implemented or lifted.

---

### 📌 Trends in Confirmed, Recovered, Tested

> ![Placeholder for trend plot](https://via.placeholder.com/700x300?text=Confirmed+vs+Recovered+Trend)

Two major waves correspond to **Delta** (mid-2021) and **Omicron** (early 2022). Recoveries lag behind confirmed cases by a few days.

---

### 📌 Case Fatality vs. Vaccination & Stringency

> ![Placeholder for normalized trend plot](https://via.placeholder.com/700x300?text=Stringency+%26+Fatality+Trend)

As vaccination rates rise, case fatality percentage falls — showing the vaccine’s role in reducing mortality.

---

## 🧩 Key Challenges

- ⚙️ High dimensional dataset (165 variables)
- 🧪 Handling missing data from changing policies
- 🔄 Converting binary/dummy policy values into descriptive categories
- 🎨 Managing visualization complexity for clarity

---

## ✅ Conclusion

- **Vaccination rollout** and **stringent policies** were effective in reducing fatality rates.
- **Positive test rate** dropped after mass testing and policy tightening.
- The **Stringency Index** correlates with containment success in key waves.
- This project underscores the value of **data-driven public health policy**.

---

## 🧠 Tools & Libraries Used

| Tool            | Purpose                       |
|-----------------|-------------------------------|
| `pandas`        | Data manipulation              |
| `numpy`         | Numerical operations           |
| `matplotlib`    | Visualization                  |
| `seaborn`       | Advanced plots                 |
| `jupyter`       | Notebook environment           |

---

## 🧑‍💻 Author

**Azrul Zulhilmi Bin Ahmad Rosli**  
📘 STQD 6014 Data Science — Semester 1, 2024/2025  
👩‍🏫 Supervisor: Dr. Nurul Afiqah Burhanuddin

---

## 📚 References

- [Google COVID-19 Open Data](https://health.google.com/covid-19/open-data/raw-data?loc=MY)
- Free Malaysia Today (FMT), Ministry of Health Malaysia
- VanderPlas, J. (2016). *Python Data Science Handbook*
- McKinney, W. (2012). *Python for Data Analysis*
