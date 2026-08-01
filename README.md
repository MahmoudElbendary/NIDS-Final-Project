#  Network Intrusion Detection System (NIDS) using Machine Learning

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
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
* **Environment:** Kaggle / Jupyter Notebook / VS Code

----

##  Authors & Team Members

This project was developed as a Graduation Project at the **Higher Technological Institute (HTI)** by:

*  **Mahmoud Yousef Elbendary** - [GitHub Profile](https://github.com/MahmoudElbendary)
*  **Mahmoud Saber Mohamed**
*  **Hamad Mostafa Hammad**

---

##  How to Run the Project

You can view and analyze the full code and model execution directly in this repository by opening the `nids-final-project.ipynb` file.

To run and experiment with the project locally on your machine:

1. **Clone this repository:**
   ```bash
   git clone [https://github.com/MahmoudElbendary/NIDS-Final-Project.git](https://github.com/MahmoudElbendary/NIDS-Final-Project.git)
