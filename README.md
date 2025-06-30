# Titanic Dataset Analysis

This project analyzes the **Titanic passenger dataset** to understand factors that influenced survival rates. It demonstrates practical data preprocessing and visualization using **pandas**, **matplotlib**, and **seaborn** in Python.

---

## 📊 What This Project Does

* Loads and cleans the Titanic dataset
* Handles missing values smartly (filling, dropping, or encoding)
* Converts categorical variables to numerical formats
* Visualizes survival insights with clean, readable plots

---

## 🗂️ Key Steps

### ✅ Data Preprocessing

* **Read CSV:** Load data with `pd.read_csv()`
* **Missing Data:** Identify nulls with `df.isnull().sum()`
* **Fill Nulls:** Fill missing ages with median age
* **Drop Columns:** Remove unhelpful columns like `Cabin`
* **Drop Rows:** Remove rows missing `Embarked` info
* **Encode Categorical:** Convert `Sex` to numeric; one-hot encode `Embarked`

---

### 📈 Data Visualization

* **Matplotlib:** Customize plot size, titles, labels, and axes
* **Seaborn:** Use clean whitegrid style for readability
* **Bar Plots:** Show survival rates by gender, class, and more

---

## 🛠️ Libraries Used

* **pandas**
* **matplotlib**
* **seaborn**

---

## 🚀 How to Run

1. Clone this repo

   ```bash
   git clone https://github.com/yourusername/titanic-dataset-analysis.git
   cd titanic-dataset-analysis
   ```
2. Install dependencies

   ```bash
   pip install pandas matplotlib seaborn
   ```
3. Run the notebook or Python script

---

## 📌 Insights

The code and visualizations help answer questions like:

* Did gender affect survival chances?
* Did passenger class matter?
* How does port of embarkation relate to survival?

---

## 📄 Report

For a detailed explanation of the code and functions used, check [`Report.pdf`](./Report.pdf).

---

## ⚓ License

Feel free to fork, adapt, and improve — just cite this repo if you reuse parts of it.

---
