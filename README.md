# 🚀 Sonar Rock vs Mine Predictor

A machine learning project to classify underwater sonar signals as **Rock** or **Mine** using the classic Sonar dataset.

---

## 📖 Overview

This project uses the Sonar dataset to train a machine learning model capable of distinguishing between rocks and mines based on sonar return signals.  
It demonstrates practical classification, preprocessing, model training, and evaluation techniques using **Python** and **scikit-learn**.

---

## 📊 Dataset

- **Samples:** 208  
- **Features:** 60 numeric attributes representing sonar signal energy  
- **Labels:**
  - `R` → Rock 🪨
  - `M` → Mine 💣

---

## 🛠 Features

- Load and inspect the sonar dataset using **pandas**  
- Explore data with `.head()`, `.describe()`, `.value_counts()`, and `.groupby()`  
- Preprocess data by separating features (`X`) and target (`Y`)  
- Split dataset into training and test sets using `train_test_split`  
- Train a **Logistic Regression** classifier (other classifiers like Random Forest or SVM can also be used)  
- Evaluate model performance using **accuracy score**

---

## 💻 Tech Stack

- Python 3 🐍  
- Pandas 🐼  
- NumPy 🔢  
- Scikit-learn ⚡  
- Jupyter Notebook 📓

---
