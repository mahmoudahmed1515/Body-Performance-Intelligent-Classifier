
# 🏋️‍♂️ Body Performance Analytics & Intelligent Classification

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Machine Learning](https://img.shields.io/badge/Machine_Learning-FF6F00?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Data Analysis](https://img.shields.io/badge/Data_Analysis-276DC3?style=for-the-badge&logo=pandas&logoColor=white)

## 📋 Project Overview
This project presents a complete analytical workflow for the **Body Performance Analytics** system. We applied a full machine learning lifecycle to a dataset of **13,392 individuals**, aiming to predict physical performance categories (A, B, C, D) based on 11 standardized fitness indicators.

## 🚀 Key Features
* **Comprehensive EDA:** Detailed statistical analysis of 12 features including age, gender, body fat, and physical tests.
* **Multi-Model Benchmarking:** Comparison between KNN, Decision Trees, SVM, and Neural Networks.
* **Data Pipeline:** Robust preprocessing including outlier handling (IQR capping), label encoding, and feature scaling.
* **Optimized Performance:** The **Neural Network** emerged as the top performer with **73% accuracy**.

## 📊 Dataset Insights
- **Size:** 13,392 records.
- **Top Predictors:** `broad_jump_cm` and `sit_ups_counts` were found to be the most influential factors in determining performance class.
- **Core Insights:** Age and Body Fat percentage showed significant negative correlations with top-tier (Class A) performance.

## 🛠️ Tech Stack
- **Languages:** Python
- **Libraries:** Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib.
- **Models Implemented:** - K-Nearest Neighbors (KNN)
  - Decision Tree (Depth optimized)
  - Support Vector Machine (SVM)
  - Neural Networks (MLP Classifier)

## 📈 Results Summary
| Model | Accuracy |
| :--- | :--- |
| **Neural Network** | **73.0%** |
| Decision Tree | 70.2% |
| SVM | 72.1% |
| KNN | 68.5% |

## 📁 Project Structure
- `body_performance_classification_project.ipynb`: The main technical implementation (Notebook).
- `Body_Performance_Analytics_Report.pdf`: Comprehensive analytical report.
- `Presentation.pptx`: Executive summary and visual findings.

## 👥 Team Members
- Mahmoud Ahmed
- Mostafa Shafea
- Ahmed Alaa
- Mostafa Shawkey
- Mostafa Hassan

---
*Developed for the "Introduction to AI and Machine Learning" course, Supervised by Dr. Sherif Morsy (2025-2026).*
