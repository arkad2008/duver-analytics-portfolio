# Call Center – Wait Times & Operational KPIs (2025)

## 📌 Overview
This project analyzes the performance of operators at **CallMeMaybe**, a virtual telephony service.  
The goal is to identify patterns, evaluate operational efficiency, and determine how operator behavior impacts customer satisfaction and case resolution.

The analysis integrates multiple datasets to build a comprehensive performance evaluation framework.

---

## 🎯 Objectives

### **Main Objective**
Assess operator effectiveness and determine improvement opportunities based on quantitative KPIs.

### **Specific Objectives**
- Conduct in-depth exploratory analysis of call behavior.
- Identify high- and low-performing operators.
- Measure response time, call duration, and resolution rates.
- Analyze customer feedback and performance trends.
- Merge and enrich multiple datasets.
- Provide actionable recommendations for service optimization.

---

## 📂 Dataset

### **Clients**
- Client ID  
- Registration date  
- Acquisition channel  

### **Operators**
- Operator ID  
- Hiring date  
- Experience level  

### **Calls**
- Duration  
- Type (inbound/outbound)  
- Customer rating  
- Assigned operator  

### **Feedback**
- Score  
- Case type  
- Outcome  

These datasets were consolidated for a complete operational analysis.

---

## 🔧 Tools & Technologies
- **Python:** pandas, numpy, seaborn, matplotlib  
- **Jupyter Notebook**  
- **Git & GitHub**

---

## 🔍 Data Preparation
Steps included:

- Dataset structure inspection  
- Missing-value handling  
- Date format normalization  
- Categorical standardization  
- Duplicate removal  
- Feature engineering:  
  - Average call duration  
  - Calls per operator  
  - Resolution rate  
  - Performance composite score  

---

## 📊 Exploratory Data Analysis (EDA)
Included:

- Incoming vs outgoing call patterns  
- Operator workload distribution  
- Call duration variability  
- Relationship between feedback and operator behavior  
- Time-based patterns and congestion periods  

Visualizations used:

- Bar charts  
- Histograms  
- Heatmaps  
- Boxplots  

---

## 📈 Key Findings
- Significant **performance gaps** exist between operators.  
- Long call durations do not always lead to better resolution.  
- Internal calls represent ~11% of total but offer valuable insights.  
- Specific time intervals show heavy call congestion.  
- Feedback scores strongly correlate with first-call resolution.

---

## 📝 Conclusions
The analysis enables:

- Identifying top performers for benchmarking  
- Detecting operators needing coaching or process reinforcement  
- Improving shift allocation based on call peaks  
- Enhancing both customer satisfaction and service efficiency  

---

## 🚀 Next Steps
- Develop a real-time operator performance dashboard  
- Add advanced QoS metrics  
- Implement predictiv


____________________________


VERSIÓN EN ESPAÑOL

# 📞 Análisis de Eficacia de Operadores — CallMeMaybe

## 📌 Descripción General
Este proyecto analiza el rendimiento de los operadores del servicio de telefonía virtual **CallMeMaybe**, con el objetivo de identificar patrones, indicadores de desempeño y oportunidades de mejora en la gestión de llamadas entrantes y salientes.

El análisis combina diversas fuentes de datos —clientes, operadores, historial de llamadas y retroalimentación— para construir una visión integral del servicio y proponer intervenciones basadas en datos.

---

## 🎯 Objetivos

### **Objetivo Principal**
Evaluar la eficacia operativa de los operadores y su impacto en la satisfacción del cliente y la resolución de casos.

### **Objetivos Específicos**
- Realizar un análisis exploratorio profundo (EDA) del comportamiento de llamadas.
- Identificar operadores con alto y bajo rendimiento.
- Evaluar tiempos de respuesta, duración de llamadas y tasas de resolución.
- Analizar patrones de retroalimentación (feedback/desempeño).
- Integrar múltiples datasets y crear variables derivadas.
- Generar recomendaciones accionables enfocadas en productividad y calidad.

---

## 📂 Dataset
Los datos incluyen:

### **Clientes (`clients_raw`)**
- ID del cliente  
- Fecha de registro  
- Canal de adquisición  

### **Operadores (`operators_raw`)**
- ID del operador  
- Fecha de ingreso  
- Nivel de experiencia  

### **Llamadas (`calls_raw`)**
- Duración  
- Tipo (inbound/outbound)  
- Calificación del cliente  
- Operador asignado  

### **Feedback**
- Puntuación recibida  
- Tipo de caso  
- Resultado  

Los datasets fueron unificados para un análisis completo del desempeño.

---

## 🔧 Tecnologías Utilizadas
- **Python:** pandas, numpy, seaborn, matplotlib  
- **Jupyter Notebook**  
- **Git & GitHub**

---

## 🔍 Preparación de Datos
Pasos realizados:

- Importación y revisión inicial de dimensiones  
- Tratamiento de valores nulos  
- Unificación de formatos de fecha  
- Estandarización de categorías  
- Eliminación de duplicados  
- Creación de nuevas variables:  
  - Tiempo promedio de llamada  
  - Cantidad de llamadas por operador  
  - Tasa de resolución  
  - Score compuesto de desempeño  

---

## 📊 Análisis Exploratorio (EDA)
Incluyó:

- Tendencias en volúmenes de llamadas  
- Distribución entre llamadas internas vs externas  
- Comparación de performance por operador  
- Duraciones promedio por tipo de llamada  
- Relación entre feedback y efectividad  
- Patrones de congestión en horarios específicos  

Se emplearon visualizaciones como:

- Histogramas  
- Gráficos de barras  
- Heatmaps  
- Boxplots  

---

## 📈 Hallazgos Clave
- Existe una **alta variabilidad** en el rendimiento entre operadores.  
- Algunos operadores presentan tiempos muy altos de llamada sin mejora en resolución.  
- La tasa de llamadas internas (~11%) es baja, pero aporta contexto valioso.  
- Se observan picos de llamadas en franjas horarias muy específicas, lo cual puede afectar los KPIs.  
- La retroalimentación de clientes correlaciona fuertemente con la resolución en la primera llamada.

---

## 📝 Conclusiones
El estudio permite identificar:

- Operadores con desempeño sobresaliente que pueden servir como referencia.  
- Operadores con necesidad de capacitación en resolución y eficiencia.  
- Horarios críticos que requieren redistribución del personal.  
- Estrategias para mejorar tiempos de atención y satisfacción del cliente.

---

## 🚀 Próximos Pasos
- Implementar un dashboard operativo para monitoreo en tiempo real.  
- Introducir métricas avanzadas de calidad de servicio (QoS).  
- Aplicar modelos predictivos para anticipar picos de llamadas.  
- Desarrollar programas de entrenamiento basados en desempeño histórico.  

---
