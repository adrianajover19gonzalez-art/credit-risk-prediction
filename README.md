# 🏦 Credit Risk Prediction

> End-to-end Machine Learning project for predicting credit default risk using Python and Scikit-learn.

![Python](https://img.shields.io/badge/Python-3.12-blue)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-Latest-orange)
![Status](https://img.shields.io/badge/Status-In%20Development-yellow)
![License](https://img.shields.io/badge/License-MIT-green)

---

# 📑 Table of Contents

- [Project Overview](#-project-overview)
- [Business Problem](#-business-problem)
- [Objectives](#-objectives)
- [Dataset](#-dataset)
- [Methodology](#-methodology)
- [Repository Structure](#-repository-structure)
- [Technologies](#-technologies)
- [Machine Learning Models](#-machine-learning-models)
- [Evaluation Metrics](#-evaluation-metrics)
- [Project Workflow](#-project-workflow)
- [Installation](#-installation)
- [Roadmap](#-roadmap)
- [Author](#-author)
- [License](#-license)

---

# 📖 Project Overview

Credit risk assessment is one of the most important challenges in the financial industry. Financial institutions must decide every day whether to approve or reject thousands of credit applications. An incorrect decision may lead to significant financial losses or missed business opportunities.

This project develops a complete Machine Learning pipeline to estimate the probability of customer default using demographic and financial information.

The objective is not only to build predictive models, but also to demonstrate professional Data Science practices, including reproducible workflows, modular code, model comparison and technical documentation.

---

# 🏦 Business Problem

Granting credit to high-risk customers may generate substantial financial losses, while rejecting creditworthy applicants may reduce business opportunities.

The objective of this project is to support credit risk analysts by providing predictive models capable of estimating the probability of default before a loan is approved.

Several Machine Learning algorithms are compared in order to identify the model offering the best balance between predictive performance, interpretability and financial impact.

---

# 🎯 Objectives

## General Objective

Develop a Machine Learning model capable of predicting customer default risk.

## Specific Objectives

- Understand the business problem.
- Explore and understand the dataset.
- Clean and preprocess the data.
- Perform feature engineering.
- Compare multiple Machine Learning algorithms.
- Optimize model hyperparameters.
- Evaluate models using statistical and business metrics.
- Select the best-performing model.
- Interpret the results from a business perspective.

---

# 📊 Dataset

**Dataset:** Default of Credit Card Clients

Main characteristics:

- Around 30,000 observations.
- Financial and demographic variables.
- Binary target variable:
  - Default
  - No Default

---

# 🔄 Methodology

The project follows the **CRISP-DM** methodology.

```text
Business Understanding
        │
        ▼
Data Understanding
        │
        ▼
Data Preparation
        │
        ▼
Exploratory Data Analysis
        │
        ▼
Feature Engineering
        │
        ▼
Model Training
        │
        ▼
Model Evaluation
        │
        ▼
Business Conclusions
```

---

# 📂 Repository Structure

```text
credit-risk-prediction/

├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   ├── 01_EDA.ipynb
│   ├── 02_Preprocessing.ipynb
│   ├── 03_Feature_Engineering.ipynb
│   ├── 04_Modeling.ipynb
│   └── 05_Evaluation.ipynb
│
├── src/
│   ├── preprocessing.py
│   ├── models.py
│   ├── metrics.py
│   ├── visualization.py
│   └── utils.py
│
├── images/
├── results/
│
├── README.md
├── requirements.txt
└── LICENSE
```

---

# 🛠 Technologies

Programming Languages

- Python

Libraries

- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn
- XGBoost (future version)

Development Tools

- Git
- GitHub
- Jupyter Notebook
- Visual Studio Code

---

# 🤖 Machine Learning Models

The following algorithms will be evaluated:

| Model | Purpose |
|--------|----------|
| Logistic Regression | Baseline interpretable model |
| Ridge / Lasso | Regularized linear models |
| Decision Tree | Rule-based classification |
| Random Forest | Ensemble learning |
| Random Forest + SMOTE | Imbalanced classification |
| Gradient Boosting | High-performance ensemble model |

---

# 📈 Evaluation Metrics

The models will be compared using:

- Accuracy
- Balanced Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC
- Brier Score
- Financial Cost Function

---

# 🔄 Project Workflow

```text
Business Problem
      │
      ▼
Dataset
      │
      ▼
Exploratory Data Analysis
      │
      ▼
Data Preprocessing
      │
      ▼
Feature Engineering
      │
      ▼
Model Training
      │
      ▼
Hyperparameter Tuning
      │
      ▼
Model Evaluation
      │
      ▼
Business Conclusions
```

---

# ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/yourusername/credit-risk-prediction.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

# 🗺️ Roadmap

- [x] Repository creation
- [x] Project structure
- [ ] Exploratory Data Analysis
- [ ] Data preprocessing
- [ ] Feature engineering
- [ ] Model training
- [ ] Hyperparameter tuning
- [ ] Model evaluation
- [ ] Documentation
- [ ] Final report

---

# 👩‍💻 Author

**Adriana Jover González**

- Graduate in Mathematics
- Master's Degree in Data Science and Computational Mathematics
- University of Almería

---

# 📄 License

This project is distributed under the MIT License.
