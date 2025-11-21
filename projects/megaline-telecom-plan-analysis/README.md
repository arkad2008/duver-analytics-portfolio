# Megaline – Telecom Plan Analysis (2025)

# 📱 Mobile Plan Revenue Analysis — Sprint 5

## 📌 Overview
This project analyzes user behavior in a telecommunications company to determine which of the two prepaid plans —**Surf** or **Ultimate**— generates higher revenue.

The analysis includes data cleaning, exploratory analysis, income calculation, consumption profiling, and a statistical hypothesis test to validate whether the observed difference is meaningful.

---

## 🎯 Objectives

### **Main Objective**
Identify which prepaid plan generates the highest average revenue per user.

### **Specific Objectives**
- Clean and prepare all datasets (users, calls, messages, internet use).
- Analyze customer consumption patterns.
- Calculate monthly revenue per user by plan.
- Compare average income between Surf and Ultimate.
- Perform a **hypothesis test** to check if the difference is statistically significant.

---

## 📂 Dataset

### **Plans (`df_plans`)**
Each plan contains:
- Included minutes  
- Included messages  
- Included GB  
- Monthly price  
- Overuse costs (per minute, message, GB)

### **Users (`df_users`)**
- User ID  
- Plan  
- City  
- Contract start date  

### **Calls (`df_calls`)**
- Duration  
- Date  
- User  

### **Messages (`df_messages`)**
- Date  
- User  

### **Internet (`df_internet`)**
- GB used  
- Date  
- User  

---

## 🔧 Tools & Technologies
- **Python:** pandas, numpy, seaborn, matplotlib  
- **Jupyter Notebook**  
- **Git & GitHub**

---

## 🧹 Data Preparation
Includes:
- Column name standardization  
- Handling missing and duplicate values  
- Converting date fields  
- Aggregating usage data per user per month  
- Computing revenue components  

---

## 📊 Exploratory Data Analysis
Focus areas:
- User distribution by plan  
- Usage of calls, messages, and internet  
- Average consumption per user  
- Identification of high-overuse groups  

---

## 💰 Revenue Calculation
For each user:
- Base plan revenue  
- Additional revenue from overuse  
- Total monthly revenue  

Finally, ARPU (Average Revenue Per User) is compared between plans.

---

## 🧪 Hypothesis Testing
We test:

- **H0:** No significant difference in mean revenue between Surf and Ultimate  
- **H1:** A significant difference exists  

A **t-test** (or a non-parametric alternative) is applied depending on distributional assumptions.

---

## 📈 Key Findings
- One plan yields clearly higher revenue.  
- Differences stem from both base price and overuse behavior.  
- Users of one plan tend to consume more resources, increasing revenue.  

---

## 📝 Conclusions
The analysis enables the company to:
- Promote the most profitable plan  
- Adjust pricing strategies  
- Design new bundled offerings  
- Better understand user consumption behavior  

---

## 🚀 Next Steps
- Build monthly revenue dashboards  
- Perform user segmentation with clustering  
- Simulate revenue scenarios under different price models  

---



_______________


VERSIÓN EN ESPAÑOL


## 📌 Descripción General
Este proyecto analiza el comportamiento de los usuarios de una empresa de telecomunicaciones para determinar cuál de las dos tarifas de prepago —**Surf** o **Ultimate**— genera más ingresos.

El análisis incluye preparación de datos, exploración, cálculos de ingresos, segmentación del consumo y una prueba estadística para validar si la tarifa que parece más rentable realmente lo es.

---

## 🎯 Objetivos

### **Objetivo Principal**
Identificar cuál de las dos tarifas de prepago genera mayores ingresos promedio por usuario.

### **Objetivos Específicos**
- Limpiar y preparar los datasets de usuarios, llamadas, mensajes e internet.
- Analizar el comportamiento de consumo de los clientes.
- Calcular ingresos mensuales por usuario según la tarifa.
- Comparar ingresos promedio entre Surf y Ultimate.
- Realizar una **prueba de hipótesis** para determinar si la diferencia es significativa.

---

## 📂 Conjunto de Datos

### **Planes (`df_plans`)**
Cada tarifa incluye:
- Minutos incluidos
- Mensajes incluidos
- GB de navegación incluidos
- Precio mensual
- Costos excedentes por minuto, mensaje o GB

### **Usuarios (`df_users`)**
- ID del usuario  
- Plan contratado  
- Ciudad  
- Fecha de inicio  

### **Llamadas (`df_calls`)**
- Duración  
- Fecha  
- Usuario  

### **Mensajes (`df_messages`)**
- Fecha  
- Usuario  

### **Internet (`df_internet`)**
- GB utilizados  
- Fecha  
- Usuario  

---

## 🔧 Tecnologías Utilizadas
- **Python:** pandas, numpy, matplotlib, seaborn  
- **Jupyter Notebook**  
- **Git & GitHub**

---

## 🧹 Preparación de Datos
Tareas realizadas:
- Estandarización de nombres de columnas  
- Eliminación de duplicados y valores faltantes  
- Conversión de fechas  
- Agrupación de datos por usuario y por mes  
- Cálculo de minutos, mensajes y GB consumidos  
- Cálculo de ingresos por usuario

---

## 📊 Análisis Exploratorio (EDA)
Incluye:
- Distribución del número de usuarios por tarifa  
- Análisis de consumo de llamadas, mensajes e internet  
- Gráficos de uso promedio por usuario  
- Identificación de patrones de sobrecostos  

---

## 💰 Cálculo de Ingresos
Para cada usuario se estiman:
- Ingresos base según tarifa  
- Ingresos adicionales por excedentes  
- Ingreso total mensual  

Luego se compara el **ingreso promedio por usuario (ARPU)** entre tarifas.

---

## 🧪 Prueba de Hipótesis
Se contrasta:

- **H0:** No hay diferencia significativa en el ingreso medio entre usuarios de Surf y Ultimate  
- **H1:** Sí existe una diferencia en los ingresos medios  

La prueba se realiza con un **t-test** o test no paramétrico según la distribución observada.

---

## 📈 Hallazgos
- Una de las tarifas presenta ingresos significativamente mayores.  
- La diferencia no solo se explica por el precio base, sino por excedentes generados.  
- Los usuarios de una de las tarifas tienden a consumir más recursos, generando ingresos adicionales.  


---

## 📝 Conclusiones
- El análisis sugiere cuál tarifa es más rentable a nivel agregado.  
- La prueba estadística confirma si la diferencia es robusta.  
- Los resultados permiten a la empresa:
  - Ajustar precios  
  - Rediseñar paquetes  
  - Promover la tarifa más rentable  

---

## 🚀 Próximos Pasos
- Construir dashboard mensual de uso y consumo.  
- Aplicar clustering para definir perfiles de usuario.  
- Simular ingresos con variaciones de precio.  

---
