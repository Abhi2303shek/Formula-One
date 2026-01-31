# 🏎️ Formula One (F1) Data Analysis (1950–2022)

## 📌 Project Overview
This project performs an end-to-end **exploratory data analysis (EDA)** on historical **(F1)** data spanning **1950 to 2022**.  
The analysis focuses on **driver performance, constructor dominance, era-wise trends, and championship patterns** using Python.

The objective is to uncover **long-term performance insights** and understand how dominance and competition in Formula One have evolved across decades.

Original Dataset Link -- https://www.kaggle.com/datasets/mustafatomak/formula-1-dataset-1950-2021
---

## 🎯 Objectives
- Analyse the historical performance of drivers and constructors
- Identify dominant eras in Formula One history
- Compare driver consistency vs peak performance
- Study championship trends over time
- Derive insights from long-term motorsport data
- What matters more, the driver or the Constructor?

---

## 🗂 Dataset Description
The analysis utilises multiple interrelated datasets spanning Formula One's history.

### Key Entities:
- **Drivers** – career statistics, wins, podiums
- **Constructors** – team performance and championships
- **Races** – season-wise and race-level results

### Time Coverage:
- Seasons: **1950 – 2022**
- Granularity:
  - Season-level summaries
  - Race-level performance data

📌 The dataset structure enables **relational and time-series analysis**.

---

## 🛠 Tools & Technologies
- **Python**
  - Pandas
  - NumPy
- **Visualization**
  - PowerBI
- **Jupyter Notebook**

---

## 🔍 Data Understanding & Exploration
- Dataset relationships and joins
- Row and column analysis across tables
- Understanding historical data consistency
- Inspection of missing and legacy values

---

## 🔧 Data Cleaning & Preparation
Key steps performed:

- Standardised driver and constructor names
- Handled missing or legacy-era records
- Filtered incomplete seasons where required
- Ensured consistent data types across datasets
- Merged datasets for unified analysis

---

## 🧠 Feature Engineering
- Aggregated wins, podiums, and points
- Created era-based groupings (decades)
- Calculated championship conversion metrics
- Derived consistency indicators across seasons

---

## 📊 Exploratory Data Analysis

### 🔹 Driver Performance Analysis
- Career wins and podiums
- Championship counts
- Longevity vs success comparison

### 🔹 Constructor Performance Analysis
- Team dominance across eras
- Constructor championships over time
- Competitive cycles and transitions

### 🔹 Era-wise Trends
- Dominant teams per decade
- Changes in competition intensity
- Shifts in championship concentration

### 🔹 Championship Patterns
- Repeat champions vs one-time winners
- Era-based dominance trends
- Performance distribution across teams

---

## 📈 Key Insights
- Formula One history is marked by **distinct eras of dominance**
- A small number of constructors account for a majority of championships
- Driver longevity does not always correlate with championship success
- Competitive balance varies significantly across decades

---

## 📁 Project Structure
📦 formula-one-data-analysis
┣ 📂 data
┃ ┣ drivers.csv
┃ ┣ constructor.csv
┃ ┣ race.csv
┣ 📂 notebooks
┃ ┗ constructor.ipynb
┃ ┗ driver.ipynb
┃ ┗ race.ipynb
┣ 📄 README.md
┣ 📄 requirements.txt
┗ 📄 .gitignore
