#  Network Intrusion Detection System (NIDS) using Machine Learning

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![Kaggle](https://img.shields.io/badge/Kaggle-Notebook-20BEFF.svg)](https://www.kaggle.com/code/ahmedhery11/nids-final-project)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

##  Project Overview

This project focuses on designing an intelligent system for detecting network intrusions and attacks using machine learning techniques. The model analyzes network traffic in real-time, identifies anomalous patterns indicating attacks such as DDoS or unauthorized access attempts, enhancing network security and reducing potential threats.

---

##  Key Features

* **Data Preprocessing & Cleaning:** Handling missing values, infinite float values, redundant headers, and noise reduction.
* **Feature Selection & Engineering:** Optimization of network flow features to improve detection performance and lower execution latency.
* **Imbalance Handling:** Balancing class distribution across rare attack signatures to improve minority class detection.
* **Multi-Model Evaluation:** Comparative analysis using multiple machine learning classifiers (e.g., Random Forest, XGBoost, Decision Trees).
* **Comprehensive Performance Metrics:** Evaluated using Precision, Recall, F1-Score, ROC-AUC Curves, and Confusion Matrices.

---

##  Dataset: CICIDS2017

The **CICIDS2017** dataset contains benign traffic and modern common attacks, covering realistic network behavior:

* **Benign Traffic:** Standard operational network sessions.
* **Attacks Covered:** 
  * DoS / DDoS (Slowloris, Hulk, GoldenEye)
  * Port Scan & Network Probing
  * Web Attacks (SQL Injection, Cross-Site Scripting, Brute Force)
  * Infiltration & Botnets

---

##  Tech Stack & Tools

* **Language:** `Python`
* **Data Processing:** `Pandas`, `NumPy`
* **Machine Learning:** `Scikit-Learn`, `XGBoost`
* **Visualization:** `Matplotlib`, `Seaborn`
* **Environment:** Kaggle Notebooks / Jupyter Lab

---

##  How to Run the Project

Since this project was built and executed using Cloud Accelerators, you can run and experiment with the code directly on Kaggle:

### Option 1: Run Online (Recommended)
1. Open the Notebook directly on Kaggle: [NIDS Final Project on Kaggle](https://www.kaggle.com/code/ahmedhery11/nids-final-project).
2. Click on **Copy & Edit** to create your own editable copy.
3. Run the notebook cells sequentially!

### Option 2: Run Locally
1. Clone this repository:
   ```bash
   git clone [https://github.com/MahmoudElbendary/NIDS-Final-Project.git](https://github.com/MahmoudElbendary/NIDS-Final-Project.git)
