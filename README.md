# 🐧 Penguins Dataset - Exploratory Data Analysis & Visualization

This project focuses on cleaning, preprocessing, and visualizing the **Palmer Penguins Dataset** using Python libraries like **Pandas**, **Seaborn**, and **Matplotlib**. It’s an end-to-end data exploration pipeline that reveals patterns in penguin species, habitat, and biological features.

---

## 📌 Project Overview

- 📊 Loaded and explored the Seaborn’s built-in **penguins** dataset.
- 🧹 Cleaned missing values using **mode** for categorical and **mean** for numerical features.
- 🚫 Verified no duplicates or outliers using **IQR method** and **box plots**.
- 🔍 Performed **univariate**, **bivariate**, and **multivariate** analysis.
- 🧠 Derived meaningful biological insights based on species, gender, and island.
- 📈 Used **heatmaps, KDE plots, histograms, bar charts, count plots**, and **pair plots** for comprehensive EDA.

---

## ⚙️ Tools & Libraries

<p float="left">
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/Numpy-013243?style=for-the-badge&logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/Seaborn-4B8BBE?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Matplotlib-206b99?style=for-the-badge&logo=matplotlib&logoColor=white" />
  <img src="https://img.shields.io/badge/Jupyter-FAF5F2?style=for-the-badge&logo=jupyter&logoColor=orange" />
</p>

---

## 🧼 Data Cleaning

- Converted `species`, `island`, and `sex` to categorical types.
- Imputed missing numerical values with **mean**.
- Imputed missing categorical values (`sex`) with **mode**.
- Checked for and confirmed absence of **duplicates** and **outliers**.

---

## 📊 Visualizations

### ✅ Univariate Analysis:
- KDE plots
- Histograms
- Count plots
- Pie charts

### 🔄 Bivariate Analysis:
- Bar plots comparing numerical and categorical data
- Count plots between categorical variables
- Pair plots to analyse relationships

### 🔁 Multivariate Analysis:
- Correlation heatmaps
- Category-wise group analysis
- Matrix of count plots and bar plots for combined variable comparison

---

## 🔍 Key Observations

- No outliers detected in any of the numerical features.
- Adelie is the most common species; Chinstrap the least.
- Biscoe Island hosts the most penguins but **no Chinstrap** species.
- Dream Island lacks **Gentoo** penguins.
- Male penguins generally have higher body mass, bill depth, and flipper length.
- Gentoo penguins have the **largest body mass and flippers**, but smaller bill depth.

---
