# Habit Tracker Data Analysis

## 📌 Overview

This project analyzes habit tracking data to understand how consistently users follow their habits, identify behavior patterns, and evaluate engagement over time.

The goal is to explore how users interact with their habits and where consistency drops.

---

## 📂 Data Description

The project is based on multiple related datasets:

* **users.csv** → Contains user-level information
* **habits.csv** → Defines different habits assigned to users
* **habit_logs.csv** → Tracks daily completion status of habits
* **Project1.db** → SQLite database storing structured data

---

## 🔍 Key Questions Explored

* How consistent are users in completing their habits?
* Which habits are followed regularly vs ignored?
* Do users drop off over time?
* What patterns exist in habit completion frequency?

---

## ⚙️ Work Done

### 🧹 Data Preparation

* Loaded multiple datasets
* Merged and structured data
* Handled missing / inconsistent values

### 📊 Analysis

* Calculated habit completion rates
* Analyzed user consistency
* Studied frequency and trends of habit tracking
* Compared behavior across users

### 📈 Visualization

* Used Matplotlib / Seaborn to visualize:

  * Habit completion trends
  * User activity patterns
  * Frequency distributions

---

## 🛠️ Tools Used

* Python
* Pandas
* Matplotlib
* Seaborn
* SQLite
* Jupyter Notebook

---

## 📁 Project Structure

```
data/
database/
notebook/
```

---

## ▶️ How to Run

1. Clone the repository
2. Open the notebook in `notebook/`
3. Run all cells to reproduce the analysis

---

## 📌 Insights (High-Level)

* Some users show consistent habit tracking, while others drop off quickly
* Certain habits have higher completion rates than others
* Engagement tends to decrease over time for many users

---

## 🚀 Future Improvements

* Build a model to predict habit consistency
* Create a dashboard (Power BI / Streamlit)
* Add user segmentation for deeper insights

---

This project focuses on building strong data analysis fundamentals as a step toward Machine Learning.
