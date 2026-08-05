# 🏦 Credit Risk Prediction

> End-to-end Data Science project for predicting credit default risk using Python and Scikit-Learn.

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

Credit risk assessment is one of the most critical challenges in the financial industry. Every day, banks and financial institutions must decide whether to approve or reject thousands of credit applications, balancing the risk of customer default against potential business opportunities.

This project presents a complete Data Science workflow for estimating the probability of customer default using Machine Learning techniques.

Several classification algorithms are implemented and compared, evaluating not only their predictive performance but also the financial impact associated with classification errors.

Beyond model development, the project emphasizes clean code, reproducible experiments, modular design, and technical documentation, following best practices commonly used in professional Data Science projects.

---

# 🏦 Business Problem

Financial institutions process thousands of credit applications every day.

Granting credit to customers with a high probability of default may lead to significant financial losses, while rejecting creditworthy applicants may reduce business opportunities.

Accurate predictive models can support credit risk analysts by improving decision-making and helping financial institutions optimize their lending strategies.

This project develops and compares several Machine Learning models to estimate the probability of default before a loan is approved.

---

# 🎯 Objectives

## General Objective

Develop a Machine Learning model capable of predicting customer default risk using demographic and financial information.

## Specific Objectives

- Understand the business problem.
- Explore and understand the dataset.
- Perform Exploratory Data Analysis (EDA).
- Clean and preprocess the data.
- Apply feature engineering techniques when appropriate.
- Compare different Machine Learning algorithms.
- Optimize model hyperparameters.
- Evaluate models using both statistical and business metrics.
- Select the model that provides the best trade-off between predictive performance and financial impact.
- Interpret the obtained results.

---

# 📊 Dataset

**Dataset**

Default of Credit Card Clients

**Main characteristics**

- Approximately 30,000 observations.
- Financial and demographic variables.
- Binary target variable:
  - Default
  - No Default

---

# 🔄 Methodology

The project follows the **CRISP-DM (Cross Industry Standard Process for Data Mining)** methodology, one of the most widely adopted standards in Data Science projects.

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
├── README_EN.md
├── requirements.txt
└── LICENSE
```

---

# 🛠 Technologies

### Programming Language

- Python

### Libraries

- Pandas
- NumPy
- Scikit-Learn
- Matplotlib

### Development Tools

- Git
- GitHub
- Jupyter Notebook
- Visual Studio Code

---

# 🤖 Machine Learning Models

The following algorithms are evaluated throughout the project:

| Model | Purpose |
|--------|---------|
| Logistic Regression | Baseline interpretable model |
| Ridge / Lasso | Regularized linear models |
| Decision Tree | Rule-based classification |
| Random Forest | Ensemble learning |
| Random Forest + SMOTE | Handling class imbalance |
| Gradient Boosting | High-performance ensemble model |

---

# 📈 Evaluation Metrics

Models are compared using the following metrics:

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
Data Collection
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
Hyperparameter Optimization
        │
        ▼
Model Evaluation
        │
        ▼
Business Conclusions
```

---

# ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/credit-risk-prediction.git
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

---

# 🗺️ Roadmap

- [x] Repository creation
- [x] Project structure
- [x] Initial documentation
- [ ] Exploratory Data Analysis
- [ ] Data preprocessing
- [ ] Feature engineering
- [ ] Model training
- [ ] Hyperparameter optimization
- [ ] Model comparison
- [ ] Model interpretation
- [ ] Final documentation

---

# 👩‍💻 Author

**Adriana Jover González**

- Graduate in Mathematics
- Master's Degree in Data Science and Computational Mathematics
- University of Almería

---

# 📄 License

This project is distributed under the **MIT License**.
