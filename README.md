# Python
# 🐍 Data Technician Workbook – Week 6

![Python Logo](https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg)

This repository contains my completed **Week 6 Workbook** as part of the Data Technician course. The week focused heavily on **Python programming**, **Pandas**, and **exploratory data analysis (EDA)** using GDP per capita data.

---

## 🗂️ Workbook Overview

This workbook is centered on using Python for data exploration, cleaning, visualization, and analysis — covering skills needed for real-world data technician roles.

---

## 📆 Task Highlights by Day

### 🔹 Day 2: Task 1 – Python FizzBuzz
Implemented a classic coding challenge using Python:

```python
for i in range(1, 101):
    if i % 15 == 0:
        print("fizzbuzz")
    elif i % 3 == 0:
        print("fizz")
    elif i % 5 == 0:
        print("buzz")
    else:
        print(i)
🔹 Day 3: Task 1 – Student CSV Analysis with Pandas
🧪 Exercise 1: Loading and Exploring Data
Loaded data with pd.read_csv()

Used .head(), .info(), and .describe() for initial exploration

🧪 Exercise 2: Indexing & Slicing
Selected columns: 'name', 'mark'

Sliced first 3 rows

Filtered rows by class (e.g., df[df['class'] == 'Four'])

🧪 Exercise 3: Data Manipulation
Added a passed column using a boolean condition

Renamed columns (e.g., mark ➝ score)

Dropped the new column to practice column removal

🔹 Day 4: GDP per Capita Data Analysis
📊 Task 1: Basic Exploration
Read 'GDP (nominal) per Capita.csv' into Pandas

Displayed first 10 and last 5 rows

Selected specific columns (Country/Territory, UN_Region)

📈 Task 2: Exploratory Data Analysis (EDA)
Performed visualizations using Matplotlib and Seaborn:

✅ Histograms to compare IMF_Estimate, UN_Estimate, and WorldBank_Estimate

✅ Correlation Heatmap to show relationships between numerical features

✅ Bar Plot for average IMF estimate by UN region

✅ Scatter Plot for UN region vs UN GDP estimate

✅ Box Plot of IMF estimates to detect outliers

💾 Datasets and Google Colab links embedded in workbook

🧰 Tools & Skills Practiced
Python: Loops, conditionals, functions

Pandas: Data loading, indexing, filtering, manipulating

Matplotlib & Seaborn: Histograms, scatter plots, box plots, heatmaps

EDA Techniques: Summary statistics, data visualization, correlation analysis


