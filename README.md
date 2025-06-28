# 🕵️‍♂️ Corruption Data Analysis – Bribes in India

An end-to-end Exploratory Data Analysis (EDA) project investigating bribery patterns across Indian cities, departments, and time. This analysis reveals how, when, and where bribes are most commonly reported — using pandas, seaborn, and matplotlib.

---

## 📌 Overview

- 🔍 Explored patterns of bribery across locations, departments, and time.
- 📈 Used data visualization to uncover trends and anomalies.
- 🛠 Cleaned and transformed messy data (null values, outliers, string splits).
- ⏳ Time series analysis to see bribe patterns across days/months/years.

---

## 📂 Dataset Summary

- **Source:** `corruption/data.csv`
- **Shape:** ~30,000 rows, 5+ columns
- **Key Columns:**
  - `Date`, `Amount(INR)`, `Department`, `Location`

---

## 🧪 Tools & Libraries

- `pandas` for data manipulation
- `seaborn` and `matplotlib` for plotting
- Jupyter Notebook

---

## 📊 Key Insights

| Insight | Summary |
|--------|---------|
| 💸 **Most bribes** | Paid in **Bangalore**, Karnataka |
| 🚦 **Top Department** | **Traffic** had the most reported bribery cases |
| 📆 **Day of Week** | **Sundays** had the lowest bribe reports |
| 🧽 **Data Cleaning** | Filled missing departments, removed outliers |
| 📅 **Years of Interest** | **2016** and **2019** had highest bribe cases |

---

## 🔍 Visualizations

### 1. Distribution of Bribe Amounts
<img src="images/bribe_amounts.png" width="600"/>

### 2. Top 10 Cities by Bribe Count
<img src="images/top_cities.png" width="600"/>

### 3. Department-wise Bribe Distribution
<img src="images/departments.png" width="600"/>

### 4. Bribes by Day of the Week
<img src="images/days.png" width="600"/>

---

## 📆 Time Series Features Extracted

- Day of Month
- Day of Week
- Month
- Year
- Week of Year

---

## 🧼 Data Cleaning Steps

- Replaced missing departments with `"Others"`
- Removed extreme outliers beyond 90th percentile in `Amount(INR)`
- Split `Location` into `City` and `Province`

---

## 🧠 Conclusion

- **Bangalore** leads in reported bribes.
- **Traffic Department** consistently appears in top cases.
- Bribes are reported **less on Sundays**, indicating weekly patterns.
- **Corruption peaked in 2016 and 2019** — possibly linked to reporting surges.

---



