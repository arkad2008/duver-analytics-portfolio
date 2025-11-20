# Model Fitness – Churn Prediction & Segmentation (2025)

## 📌 Overview
This project analyzes customer behavior from a fitness chain to **predict churn probability** and identify clients who are likely to cancel their membership in the next month.  
The goal is to support the business in improving retention using data-driven insights and machine learning models.

---

## 🎯 Objectives

### **Main Objective**
Build a machine learning model capable of predicting customer churn with high accuracy.

### **Specific Objectives**
- Conduct an exploratory data analysis (EDA) to identify behavioral patterns.
- Compare characteristics of churned vs. retained users.
- Build customer segments and typical user profiles.
- Train and evaluate predictive models using multiple algorithms.
- Provide actionable recommendations to reduce churn.

---

## 📂 Dataset
The project uses the dataset provided by TripleTen’s Sprint 13 module.

It includes:
- Customer tenure  
- Monthly visits  
- Participation in group classes  
- Activity level  
- Personal spending  
- Contract details  
- Target variable: **churn**

---

## 🔧 Tools & Technologies
- **Python:** pandas, numpy, seaborn, matplotlib  
- **Machine Learning:** scikit-learn  
- **Environment:** Jupyter Notebook  
- **Version Control:** Git & GitHub

---

## 📊 Methodology

### **1. Data Loading & Understanding**
- Inspection of structure and variable types  
- Handling of missing values  
- Descriptive statistics  

### **2. Exploratory Data Analysis (EDA)**
- Distribution analysis  
- Comparison between churned and active customers  
- Correlation matrix  
- Identification of most relevant predictors  

### **3. Modeling**
- Train/test split  
- Algorithms tested:  
  - Logistic Regression  
  - Random Forest  
  - Additional models included in the notebook  
- Selection based on performance metrics (ROC-AUC, F1, etc.)

### **4. Evaluation & Interpretation**
- ROC-AUC curve  
- Accuracy, Precision, Recall, F1-Score  
- Feature importance visualization  

---

## 📈 Key Findings
- **Customer tenure**, **attendance frequency**, and **activity level** are highly correlated with churn likelihood.
- New clients with low engagement have the highest probability of canceling.  
- The selected model demonstrates strong predictive performance, making it suitable for early intervention programs.

---

## 📝 Conclusions
The project confirms that churn can be predicted reliably using customer behavior variables.  
This enables the company to:

- Identify at-risk customers early  
- Improve retention strategies  
- Personalize offers and communication  
- Optimize business decisions through analytics




___________

VERSIÓN EN ESPAÑOL


# 🏋️‍♂️ Predicción de Cancelación de Clientes — Model Fitness 

## 📌 Descripción General
Este proyecto analiza el comportamiento de los clientes de una cadena de gimnasios para **predecir la probabilidad de cancelación (churn)** y construir un sistema que permita identificar a usuarios en riesgo antes de que abandonen el servicio.

La empresa busca aumentar la retención y optimizar su estrategia basada en datos mediante un modelo predictivo y un análisis detallado de los perfiles de clientes.

---

## 🎯 Objetivos del Proyecto

### **Objetivo principal**
Desarrollar un modelo de machine learning capaz de predecir la probabilidad de que un cliente abandone el gimnasio durante el mes siguiente.

### **Objetivos específicos**
- Realizar un análisis exploratorio profundo (EDA) para identificar patrones de comportamiento.
- Comparar las características entre clientes que se quedan y los que se van.
- Construir retratos de usuarios típicos (segmentación).
- Evaluar modelos predictivos y seleccionar el mejor.
- Generar recomendaciones accionables para mejorar la retención.

---

## 📂 Dataset
El notebook utiliza los datasets suministrados por el proyecto Sprint 13 de TripleTen.

Incluyen información sobre:
- Frecuencia de uso
- Participación en clases grupales
- Antigüedad como cliente
- Gastos personales
- Nivel de actividad
- Datos contractuales
- Etiqueta objetivo: **cancelación**

---

## 🔧 Tecnologías Utilizadas
- **Python:** pandas, numpy, seaborn, matplotlib  
- **Machine Learning:** Scikit-learn  
- **Jupyter Notebook**  
- **GitHub**

---

## 📊 Metodología

### **1. Carga y exploración inicial**
- Revisión de estructura del dataset  
- Tipos de variables  
- Valores faltantes  
- Estadísticas descriptivas

### **2. Análisis Exploratorio (EDA)**
- Comparación entre clientes que cancelaron vs. los que permanecieron  
- Distribuciones, histogramas y boxplots  
- Matriz de correlación  
- Identificación de variables predictoras más relevantes

### **3. Modelado**
- División train/test  
- Entrenamiento de varios algoritmos:  
  - Regresión logística  
  - Random Forest  
  - Otros modelos evaluados según el notebook  
- Selección del mejor modelo basado en métricas

### **4. Resultados y evaluación**
- Curvas ROC-AUC  
- Accuracy, Precision, Recall, F1-Score  
- Interpretación de importancia de características

---

## 📈 Hallazgos Principales
- Ciertas variables como **frecuencia de asistencia**, **tiempo como cliente**, **nivel de actividad** y **uso de servicios adicionales** son claves para predecir abandono.  
- Los clientes con menor tiempo de afiliación y menor interacción con el gimnasio tienen mayor probabilidad de cancelación.  
- El modelo seleccionado alcanza un desempeño sólido que permite priorizar intervenciones tempranas.

---

## 📝 Conclusiones
El análisis demuestra que es posible **predecir la cancelación de clientes con alta precisión** a partir de sus patrones de uso.  
El estudio permite:

- Identificar segmentos de clientes en riesgo  
- Desarrollar estrategias proactivas de retención  
- Optimizar la oferta de servicios  
- Alinear decisiones del negocio con datos reales

---


