# 🏦 Credit Risk Prediction

> End-to-end Machine Learning project for predicting credit default risk using Python and Scikit-learn.

🌐 **Language**

- 🇬🇧 English (this document)
- 🇪🇸 [Versión en español](README.md)

---

> Proyecto integral de Machine Learning para la predicción del riesgo de impago utilizando Python y Scikit-Learn.

![Python](https://img.shields.io/badge/Python-3.12-blue)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-Latest-orange)
![Estado](https://img.shields.io/badge/Estado-En%20desarrollo-yellow)
![Licencia](https://img.shields.io/badge/Licencia-MIT-green)

---

# 📑 Índice

- [Descripción del proyecto](#-descripción-del-proyecto)
- [Problema de negocio](#-problema-de-negocio)
- [Objetivos](#-objetivos)
- [Conjunto de datos](#-conjunto-de-datos)
- [Metodología](#-metodología)
- [Estructura del repositorio](#-estructura-del-repositorio)
- [Tecnologías utilizadas](#-tecnologías-utilizadas)
- [Modelos de Machine Learning](#-modelos-de-machine-learning)
- [Métricas de evaluación](#-métricas-de-evaluación)
- [Flujo del proyecto](#-flujo-del-proyecto)
- [Instalación](#-instalación)
- [Hoja de ruta](#-hoja-de-ruta)
- [Autora](#-autora)
- [Licencia](#-licencia)

---

# 📖 Descripción del proyecto

La evaluación del riesgo de crédito constituye uno de los principales desafíos del sector financiero. Cada día, bancos y entidades financieras deben decidir si conceden o no financiación a miles de clientes, asumiendo el riesgo de que algunos de ellos incumplan sus obligaciones de pago.

Este proyecto desarrolla un flujo completo de Ciencia de Datos para construir un modelo capaz de estimar la probabilidad de impago de un cliente utilizando técnicas de Machine Learning.

Para ello se comparan distintos algoritmos de clasificación, evaluando tanto su capacidad predictiva como el impacto financiero asociado a los errores de clasificación.

Además del desarrollo de modelos predictivos, el proyecto pone especial énfasis en la organización del código, la reproducibilidad de los experimentos y la documentación técnica, siguiendo buenas prácticas utilizadas en proyectos profesionales de Ciencia de Datos.

---

# 🏦 Problema de negocio

Las entidades financieras procesan diariamente miles de solicitudes de crédito.

Conceder financiación a clientes con una elevada probabilidad de impago puede generar importantes pérdidas económicas, mientras que rechazar clientes solventes supone desaprovechar oportunidades de negocio.

En este contexto, disponer de modelos predictivos precisos permite apoyar la toma de decisiones en departamentos de riesgos, banca y análisis financiero.

Este proyecto desarrolla diferentes modelos de Machine Learning con el objetivo de estimar la probabilidad de impago antes de conceder un crédito.

---

# 🎯 Objetivos

## Objetivo general

Desarrollar un modelo de Machine Learning capaz de predecir el riesgo de impago de clientes a partir de información financiera y demográfica.

## Objetivos específicos

- Comprender el problema de negocio.
- Analizar el conjunto de datos.
- Realizar un análisis exploratorio (EDA).
- Preparar y transformar los datos.
- Desarrollar variables predictivas cuando sea necesario.
- Comparar diferentes algoritmos de clasificación.
- Optimizar los hiperparámetros de cada modelo.
- Evaluar el rendimiento mediante métricas estadísticas y de negocio.
- Seleccionar el modelo con mejor equilibrio entre rendimiento e impacto financiero.
- Interpretar los resultados obtenidos.

---

# 📊 Conjunto de datos

**Base de datos utilizada**

Default of Credit Card Clients

**Características principales**

- Aproximadamente 30.000 observaciones.
- Variables financieras y demográficas.
- Variable objetivo binaria:
  - Impago
  - No impago

---

# 🔄 Metodología

El proyecto sigue la metodología **CRISP-DM (Cross Industry Standard Process for Data Mining)**, ampliamente utilizada en proyectos de Ciencia de Datos.

```text
Comprensión del negocio
        │
        ▼
Comprensión de los datos
        │
        ▼
Preparación de los datos
        │
        ▼
Análisis Exploratorio (EDA)
        │
        ▼
Ingeniería de variables
        │
        ▼
Entrenamiento de modelos
        │
        ▼
Evaluación
        │
        ▼
Conclusiones de negocio
```

---

# 📂 Estructura del repositorio

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

# 🛠 Tecnologías utilizadas

### Lenguaje

- Python

### Librerías

- Pandas
- NumPy
- Scikit-Learn
- Matplotlib

### Herramientas

- Git
- GitHub
- Jupyter Notebook
- Visual Studio Code

---

# 🤖 Modelos de Machine Learning

Durante el proyecto se compararán los siguientes algoritmos:

| Modelo | Objetivo |
|---------|----------|
| Regresión Logística | Modelo base e interpretable |
| Ridge / Lasso | Regularización |
| Árbol de decisión | Clasificación basada en reglas |
| Random Forest | Modelo ensemble |
| Random Forest + SMOTE | Tratamiento del desbalanceo |
| Gradient Boosting | Modelo de alto rendimiento |

---

# 📈 Métricas de evaluación

Los modelos serán comparados mediante:

- Accuracy
- Balanced Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC
- Brier Score
- Función de coste financiero

---

# 🔄 Flujo del proyecto

```text
Problema de negocio
        │
        ▼
Obtención de datos
        │
        ▼
Análisis Exploratorio
        │
        ▼
Preprocesamiento
        │
        ▼
Ingeniería de variables
        │
        ▼
Entrenamiento de modelos
        │
        ▼
Optimización
        │
        ▼
Evaluación
        │
        ▼
Conclusiones
```

---

# ⚙️ Instalación

Clonar el repositorio

```bash
git clone https://github.com/TU_USUARIO/credit-risk-prediction.git
```

Instalar las dependencias

```bash
pip install -r requirements.txt
```

---

# 🗺️ Hoja de ruta

- [x] Creación del repositorio
- [x] Organización de la estructura del proyecto
- [x] Documentación inicial
- [ ] Análisis exploratorio de los datos
- [ ] Preprocesamiento
- [ ] Ingeniería de variables
- [ ] Entrenamiento de modelos
- [ ] Optimización de hiperparámetros
- [ ] Comparación de modelos
- [ ] Interpretación de resultados
- [ ] Documentación final

---

# 👩‍💻 Autora

**Adriana Jover González**

- Graduada en Matemáticas
- Máster en Ciencia de Datos y Matemática Computacional
- Universidad de Almería

---

# 📄 Licencia

Este proyecto se distribuye bajo la licencia **MIT**.
