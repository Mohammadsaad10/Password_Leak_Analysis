# 🔐 Password Leak Analysis (PLA)

### Large-Scale Password Analysis using PySpark, Hive, and Pandas

![Python](https://www.vectorlogo.zone/logos/python/python-icon.svg)
![PySpark](https://www.vectorlogo.zone/logos/apache_spark/apache_spark-icon.svg)
![Hive](https://www.vectorlogo.zone/logos/apache_hive/apache_hive-icon.svg)

A scalable analysis project exploring real-world leaked passwords using **PySpark**, **Apache Hive**, and **Pandas**. It performs entropy scoring, pattern detection, password-strength classification, visualization, and optional ML predictions.  
All workflows are executed through **notebooks** (Colab or Jupyter) — no CLI execution required.

---

## 📁 Project Structure

```
Password_Leak_Analysis/
│
├── 1. Hive warehouse/
├── 3. Results (PySpark + Hive and pandas results)/
├── 4. PLA_pyspark_hive.ipynb
├── 5. PLA_pandas.ipynb
└── 6. rockyou.txt (dataset)
```

---

## 📘 Introduction

This project analyzes millions of leaked passwords to uncover statistical patterns, evaluate password strength, detect vulnerabilities, and compute entropy at scale.

---

## 🎯 Objectives

- Analyze large-scale password dumps
- Identify common password patterns
- Compute Shannon entropy
- Detect weaknesses
- Classify passwords
- Generate reasoning for password vulnerability
- Visualize real-world password behavior

---

## 🛠️ Technologies Used

- PySpark
- Apache Hive
- Pandas
- Matplotlib
- Google Colab
- rockyou dataset

This project uses the **RockYou** password dataset available publicly on **Kaggle** for research and educational purposes.

**Note:**

- The dataset is **not included** in this repository due to size and security considerations.
- Users can download the RockYou dataset from Kaggle and place it in main PLA directory before running the analysis.

---

## 🔍 Key Features

### 1. Data Cleaning & Preparation

### 2. Exploratory Data Analysis

### 3. Entropy & Strength Scoring

### 4. Pattern Detection

### 5. Optional ML Classifier

### 6. Visualizations

---

## 📄 Usage

This project is fully notebook-driven:

1. Run `Effective_Password_leak_analysis_Using_PySpark_and_Hive.ipynb`
2. Run `Password_leak_analysis_project using pandas.ipynb`

---

## 📊 Example Output

1.Effective_Password_leak_analysis_Using_PySpark_and_Hive.

evaluate_password("password123") gives,

```
('Vulnerable',
['Length is moderate (8–11 chars) — recommended 12+',
'Low entropy (3.28 bits)',
'Contains only lowercase letters',
'Contains sequential pattern (e.g., abc or 123)',
'Contains keyboard pattern (qwerty, asdf, 12345, etc.)'])
```

2.Password_leak_analysis_project using pandas
```
Enter a password to evaluate: hello

Password: hello
Status: Vulnerable

⚠ Vulnerabilities found:

- Too short (less than 8 characters)
- Very low entropy (1.92 bits)
- Contains only lowercase letters
- Appears in leaked password dataset (rank #60)
```
---

## 🚀 Why PySpark + Hive?

- Handles millions of passwords efficiently
- Hybrid SQL + Python analysis
- Scalable

---

## 📌 Applications

- Cybersecurity
- Incident response
- Password policy evaluation
- Academic research

---

## 👥 Contributors

- Mohammadsaad Shikalgar

---

## 📜 License

MIT
