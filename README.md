# 🔮 Predicción de Cancelaciones de Clientes

## 🔍 Introducción
Este proyecto desarrolla un modelo predictivo para estimar la probabilidad de cancelación de clientes.

## 🎯 Objetivo
Predecir la probabilidad de cancelación de clientes y detectar factores determinantes en la retención.  

## 🛠️ Tecnologías Utilizadas
- **Procesamiento de Datos**: pandas, numpy, IPython.display, tqdm  
- **Visualización**: matplotlib, seaborn, collections.Counter  
- **Modelado Predictivo**:  
  - **Manejo de desequilibrio**: imblearn.over_sampling.SMOTE  
  - **Modelos utilizados**:  
    - Regresión Logística  
    - Random Forest  
    - XGBoost  
    - LightGBM  
    - MLPClassifier  
  - **Evaluación de Modelos**:  
    - AUC-ROC  
    - Accuracy  
    - Log Loss  
    - SHAP para interpretabilidad  

## 📈 Pasos Clave (Metodología)
### 1️⃣ Preparación y Análisis Exploratorio de Datos (EDA)
- Revisión y limpieza de los datos para asegurar integridad.  
- Análisis de balance de clases y relevancia de variables (servicios, planes, demografía).  
- Creación de nuevas características para mejorar la representación del problema.  

### 2️⃣ Modelado Predictivo
- Aplicación de técnicas de transformación y codificación de variables.  
- Entrenamiento de modelos de Machine Learning con validación cruzada.  
- Evaluación del desempeño usando AUC-ROC, exactitud y otras métricas clave.  

## 📊 Resultados
El modelo desarrollado permite:  
- Identificar clientes con alto riesgo de cancelación.  
- Diseñar estrategias de retención basadas en insights clave.  
- Optimizar la gestión operativa y mejorar la satisfacción del cliente.  

## 🚀 Cómo Ejecutarlo
```bash
clonar este repositorio.
