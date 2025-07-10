# 🧠 Terrorism Data Analysis & Prediction

This repository explores global terrorism patterns through **visual analytics** and applies **machine learning** to predict the likelihood of an attack being successful. The project is split into two key components:

---


## 🤖 Part 1: Terrorism Success Prediction (Jupyter Notebook)

📁 **File**: `Terrorism Success Prediction.ipynb`  
🔍 **Tool**: Python (pandas, scikit-learn)

### 🔹 Objective
Build a supervised learning model to predict whether a terrorist attack will be **successful or not**, based on features like:

- **Country**
- **Attack Type**
- **Target Type**
- **Weapon Type**
- **Region**
- **Multiple attackers**
- **Property damage**
- **Hostage situation**

### 🧠 Model Pipeline
- Data Cleaning & Preprocessing
- Feature Encoding (Numerical + Categorical)
- Train/Test Split
- Model Evaluation using:
  - Accuracy
  - F1 Score
  - Precision, Recall
  - ROC AUC

### ✅ Algorithms Used
- Random Forest Classifier  
- Logistic Regression
- -CatBoost
- GradientBoosting Classifier
- ADA Boost   
- DecisionTree Classifier

---

## 📊 Part 2: Terrorism Patterns (Tableau)

📁 **File**: `Terrorism Patterns.twb`  
🔍 **Tool**: Tableau Desktop

### 🔹 Overview
This Tableau dashboard explores historical patterns in terrorism using the Global Terrorism Database (GTD). It allows users to interactively explore trends by:

- **Country** and **Region**
- **Attack Type**
- **Target Type**
- **Weapon Type**
- **Year**
- **Success Rate**

### 🧩 Key Features
- Top 10 countries by attack volume
- Success vs. failure trends over time
- Weapon and target distribution
- Drill-downs into attack types by region

---

## 📁 Project Structure

├── Terrorism Patterns.twb # Tableau dashboard
├── Terrorism Success Prediction.ipynb # ML pipeline for success prediction
├── README.md # This file

# 📦 Dependencies

- Python 3.x
- pandas
- scikit-learn
- matplotlib / seaborn
- Tableau Desktop (for `.twb` file)

---

## 🚀 Getting Started

1. Open `Terrorism Patterns.twb` in Tableau Desktop to explore the dashboard.
2. Open `Terrorism Success Prediction.ipynb` in Jupyter or VS Code.
3. Run all cells to preprocess the data and evaluate model performance.

---

## 📚 Data Source

Global Terrorism Database (GTD)  
📎 [https://www.start.umd.edu/gtd](https://www.start.umd.edu/gtd)

---
