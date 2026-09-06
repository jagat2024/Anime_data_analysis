# Anime_data_analysis

Library	Use
pandas	                  DataFrame, CSV reading, filtering, sorting
numpy	                    Numerical operations
matplotlib	              Graphs/charts
python-dateutil	          relativedelta fordate relate operation


# 🎌 Anime Data Analysis

> 📊 A beginner-friendly data analysis project exploring anime data using **Python, Pandas, NumPy & Matplotlib**.

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-013243?logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

---

## 🎯 Project Overview

This project analyzes an **Anime dataset** using Python and Pandas to discover useful patterns and insights.

The project focuses on **data cleaning, filtering, sorting, date manipulation, feature creation, and basic data visualization**.

The goal was to practice real-world **Data Analysis workflows** using a CSV dataset.

---

## 🛠️ Technologies Used

* 🐍 **Python**
* 🐼 **Pandas**
* 🔢 **NumPy**
* 📈 **Matplotlib(Will use to improve this )**
* 📄 **CSV Dataset**
* 📓 **Jupyter Notebook**

---

## 🔍 Analysis Performed

Some of the analysis performed in this project:

* ✅ Loaded and explored the Anime CSV dataset
* ✅ Checked dataset structure and information
* ✅ Handled missing / invalid values
* ✅ Filtered anime using conditions
* ✅ Sorted anime by episode count
* ✅ Found the **top 5 anime by episode count**
* ✅ Found the **longest-running anime**
* ✅ Created a `Months` feature from date ranges
* ✅ Performed date calculations using `datetime` and `relativedelta`
* ✅ Selected and analyzed multiple DataFrame columns
* ✅ Created visualizations from the dataset

---

## 📊 Example Analysis

### 🏆 Top 5 Anime by Episode Count

```python
top5 = df.sort_values("Episodes", ascending=False).head(5)

print(top5[["Title", "Episodes"]])
```

This sorts anime from **highest to lowest episode count** and selects the first five records.

---

### ⏳ Anime Duration in Months

A custom function was used to convert date ranges into the total number of months:

```python
df["Months"] = df["Time Stamp"].apply(calculate_total_months)
```

This created a new feature called **`Months`**, which can be used for further analysis.

---

## 📁 Project Structure

```text
anime-data-analysis/
│
├── 📂 data/
│   └── anime.csv
│
├── 📂 notebooks/
│   └── anime_analysis.ipynb
│
├── 📄 README.md
├── 📄 requirements.txt
└── 📄 .gitignore
```

---

## 🚀 How to Run

### 1️⃣ Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/anime-data-analysis.git
```

### 2️⃣ Open the project

```bash
cd anime-data-analysis
```

### 3️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Run the notebook

Open:

```text
notebooks/anime_analysis.ipynb
```

using **Jupyter Notebook** or **VS Code**.

---

## 📈 Key Skills Demonstrated

This project demonstrates practical knowledge of:

```text
Python
   ↓
Pandas
   ↓
Data Cleaning
   ↓
Data Filtering
   ↓
Data Transformation
   ↓
Feature Engineering
   ↓
Data Analysis
   ↓
Visualization
```

---

## 💡 What I Learned

Through this project, I practiced:

* Working with real CSV datasets
* Creating and manipulating Pandas DataFrames
* Using `sort_values()`, `head()`, `max()`, and `apply()`
* Filtering data using Boolean conditions
* Working with dates and date ranges
* Creating new calculated columns
* Extracting meaningful insights from data

---

## 🔮 Future Improvements

Possible improvements for this project:

* 📊 Add more advanced visualizations
* 🎭 Analyze anime genres
* ⭐ Explore rating distributions
* 📅 Analyze anime releases by year
* 🔎 Build an interactive dashboard
* 🤖 Add a recommendation system using Machine Learning

---

## 👨‍💻 Author

**Jagat Prasanna Shaw**

🎯 Engineering Student | Aspiring AI/ML Engineer

[GitHub](https://github.com/jagat2024) • [LinkedIn](https://www.linkedin.com/in/jagat-prasanna-shaw-806b36314?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)

---

## ⭐ Support

If you found this project useful, consider giving the repository a ⭐!

> 🚀 **Learn → Build → Analyze → Ship → Improve**
