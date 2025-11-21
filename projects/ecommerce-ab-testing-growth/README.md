# E-commerce – A/B Testing & Growth Prioritization (2025)

## 📌 Overview
This project covers two essential processes in data-driven product optimization:

1. **Hypothesis prioritization** using the **ICE** and **RICE** frameworks  
2. **Execution and analysis of an A/B test** focused on user conversion

The goal is to identify the most impactful initiatives and evaluate whether proposed changes truly improve user behavior.

---

## 🎯 Objectives

### **Main Objective**
Prioritize growth hypotheses and measure the statistical impact of an A/B test on key business metrics.

### **Specific Objectives**
- Load and prepare datasets for prioritization and experimentation.
- Apply ICE and RICE frameworks to rank hypotheses.
- Analyze conversion metrics in test and control groups.
- Run statistical significance tests.
- Provide actionable product recommendations.

---

## 📂 Dataset

### **Hypotheses Data**
Includes:
- Impact  
- Confidence  
- Effort  
- Reach (for RICE scoring)  

### **A/B Test Data**
Contains:
- User ID  
- Assigned group (A or B)  
- Date  
- Events (orders, views, clicks)  
- Conversion indicators  

These datasets allow for both prioritization and experimental evaluation.

---

## 🔧 Tools & Technologies
- **Python:** pandas, numpy, scipy, seaborn, matplotlib  
- **Jupyter Notebook**  
- **Git & GitHub**

---

## 🧩 Part 1 — Hypothesis Prioritization

### **ICE Framework**
Scores initiatives based on:
- Impact  
- Confidence  
- Effort  

Formula:

ICE = (Impact × Confidence) / Effort


### **RICE Framework**
Adds **Reach** to the equation:

RICE = (Reach × Impact × Confidence) / Effort


### Key Insights
- ICE surfaces ideas with quick potential wins.  
- RICE shifts priority toward hypotheses with broader exposure.  
- This demonstrates how scope can dramatically influence decision-making.

---

## 🧪 Part 2 — A/B Test Analysis

### Methodology
- Verify random split between groups  
- Compute conversion rates  
- Compare absolute and relative differences  
- Visualize distributions  
- Conduct statistical significance test (z-test for proportions)

### Results
- Differences in conversion were identified across groups.  
- Statistical tests determined whether changes were significant or random.  
- Confidence intervals and effect size provided additional context.

---

## 📈 Conclusions
- ICE and RICE provide structured, data-informed prioritization.
- The A/B test produced actionable evidence on the proposed change.
- Recommendations were issued based on statistical outcomes.

---

## 🚀 Next Steps
- Build automated experiment dashboards.  
- Standardize ICE/RICE scoring for product teams.  
- Design additional experiments for follow-up validation.

______________________

VERSIÓN EN ESPAÑOL


## 📌 Descripción General
Este proyecto aborda dos etapas fundamentales en la optimización de productos digitales:

1. **Priorización de hipótesis** utilizando los frameworks **ICE** y **RICE**
2. **Ejecución y análisis de una prueba A/B** basada en métricas de conversión

El objetivo final es identificar qué iniciativas tienen mayor potencial de impacto y evaluar, con rigor estadístico, si los cambios propuestos generan mejoras significativas en el comportamiento de los usuarios.

---

## 🎯 Objetivos

### **Objetivo Principal**
Evaluar y priorizar hipótesis de crecimiento y medir el impacto real de una prueba A/B en métricas clave de negocio.

### **Objetivos Específicos**
- Cargar y preparar datasets para análisis de hipótesis y experimentos.
- Aplicar los frameworks **ICE** y **RICE** para priorizar iniciativas.
- Analizar métricas de conversión en grupos de prueba y control.
- Realizar pruebas estadísticas para determinar significancia.
- Extraer conclusiones accionables para el equipo de producto.

---

## 📂 Conjunto de Datos

### **Hypotheses Dataset**
Contiene las hipótesis propuestas por el equipo, con valores para:
- **Impact**
- **Confidence**
- **Effort**
- **Reach** (para el caso del RICE)

### **A/B Test Dataset**
Incluye las acciones de los usuarios:
- ID de usuario  
- Grupo asignado (A o B)  
- Fecha  
- Eventos (orders, views, clicks, etc.)  
- Conversión  

Estos datasets permiten evaluar tanto la priorización como el desempeño del experimento.

---

## 🔧 Tecnologías Utilizadas
- **Python:** pandas, numpy, scipy, matplotlib, seaborn  
- **Jupyter Notebook**  
- **Git & GitHub**

---

## 🧩 Parte 1 — Priorización de Hipótesis

### **Framework ICE**
Puntaje basado en:
- Impacto  
- Confianza  
- Esfuerzo  

Se calcula como:

ICE = (Impact × Confidence) / Effort


### **Framework RICE**
Amplía el ICE añadiendo **Reach (alcance)**:


### Resultados Principales
- El framework ICE resaltó hipótesis de alto impacto inmediato.  
- El framework RICE cambió el orden al incorporar el alcance, priorizando hipótesis con exposición masiva.  
- Este análisis demostró cómo la adición del alcance puede alterar drásticamente la priorización estratégica.

---

## 🧪 Parte 2 — Prueba A/B

### Análisis realizado
- División correcta entre grupos A y B  
- Cálculo de tasas de conversión  
- Comparación absoluta y relativa  
- Visualización de distribuciones  
- Prueba estadística (z-test de proporciones)

### Hallazgos
- Se detectaron diferencias en conversión entre los grupos.  
- El análisis estadístico determinó si estas diferencias son **significativas** o atribuibles al azar.  
- Se evaluó el intervalo de confianza y el tamaño del efecto.

---

## 📈 Conclusiones Clave
- La priorización con ICE y RICE permite tomar decisiones más informadas según contexto y alcance.
- La prueba A/B aportó evidencia cuantitativa sobre el impacto del cambio propuesto.
- Basado en los resultados estadísticos, se definieron acciones recomendadas para el producto.

---

## 🚀 Próximos Pasos
- Implementar dashboards de seguimiento de experimentos.  
- Automatizar el cálculo de métricas ICE/RICE.  
- Desarrollar experimentos adicionales basados en los resultados obtenidos.

---


