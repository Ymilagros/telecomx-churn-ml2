# telecomx-churn-ml2
Modelado predictivo de churn en TelecomX: preparación de datos, entrenamiento de modelos, métricas e insights estratégicos.

# 📊 TelecomX - Predicción de Cancelación de Clientes (Churn)

Este proyecto forma parte del **Desafío Telecom X**, cuyo objetivo es desarrollar un pipeline de Machine Learning capaz de predecir qué clientes tienen mayor probabilidad de cancelar sus servicios (**churn**).  

La solución está implementada en **Python** utilizando librerías de análisis de datos y Machine Learning, con un enfoque en la preparación de datos, entrenamiento de modelos, evaluación y extracción de insights estratégicos.

---

## 🎯 Objetivo

- Predecir la cancelación de clientes (**churn**) en base a variables relevantes.  
- Identificar los principales factores que influyen en la decisión de cancelación.  
- Proveer una herramienta que permita a la empresa **anticiparse a las bajas** y aplicar estrategias de retención.
  
---

## 🛠️ Tecnologías utilizadas

- **Python 3**
- **Pandas / Numpy** → Preprocesamiento y manipulación de datos  
- **Matplotlib / Seaborn** → Análisis exploratorio y visualización  
- **Scikit-learn** → Modelado predictivo (Regresión Logística, Random Forest, etc.)  

---

## 📑 Proceso de desarrollo

1. **Preparación de datos**
   - Selección de columnas relevantes.  
   - Estandarización de valores.  
   - Clasificación de variables en **categóricas y numéricas**.  
   - Codificación de variables categóricas con `OneHotEncoder`.  
   - Normalización de variables numéricas con `StandardScaler`.  

2. **División de datos**
   - Conjunto de entrenamiento: 70%  
   - Conjunto de prueba: 30%  

3. **Entrenamiento de modelos**
   - Regresión Logística.  
   - Random Forest.  

4. **Evaluación**
   - Métricas: Accuracy, Precision, Recall, F1-Score, AUC-ROC.  
   - Comparación de modelos.  

5. **Interpretación de resultados**
   - Importancia de variables en el Random Forest.  
   - Factores críticos de cancelación identificados.  

---

## 📊 Insights principales

- Clientes con **contratos mensuales** tienen mayor riesgo de churn.  
- **Altos cargos mensuales** influyen directamente en la cancelación.  
- La **ausencia de servicios adicionales** aumenta la probabilidad de baja.  
- **Clientes antiguos** tienen menor probabilidad de churn (fidelización).  

---

## 🚀 Ejecución del proyecto

### 🔗 Abrir en Google Colab

Haz clic en el siguiente botón para abrir el proyecto directamente en Colab:  

[![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Ymilagros/telecomx-churn-ml2/blob/views/random_forest_churn.ipynb)

---

### 🖥️ Ejecución local

1. Clonar el repositorio:

```bash
git clone https://github.com/Ymilagros/telecomx-churn-ml2.git
cd telecomx-churn-ml2



## 👩‍💻 Autor  

Proyecto desarrollado por Milagros Gil
📌 Creado en Google Colab y versionado en GitHub.  


