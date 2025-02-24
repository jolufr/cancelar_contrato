# Predicción de Cancelaciones de Clientes

## Descripción del Proyecto

# Predicción de Cancelaciones de Clientes

En este proyecto se desarrolló un modelo predictivo con el propósito de predecir la probabilidad de cancelación de clientes a partir de la columna **EndDate**, en la cual los clientes activos están identificados con el valor "No". Se busca, además, identificar las características clave que influyen en la cancelación para implementar estrategias efectivas de retención.

El proceso incluyó la revisión y limpieza de los datos para asegurar la integridad de la información, seguido de un análisis exploratorio que permitió evaluar el balance de clases y la relevancia de las variables relacionadas con servicios, planes y demografía. Se aplicaron técnicas de transformación y codificación de variables, así como la creación de nuevas características que enriquecen el conjunto de datos. Posteriormente, se entrenaron diversos modelos de Machine Learning —entre ellos Regresión Logística, Random Forest y métodos de boosting— evaluando su desempeño principalmente con la métrica **AUC-ROC** y complementariamente con la exactitud.

Los resultados obtenidos en este proyecto permitirán identificar a los clientes con mayor riesgo de cancelar sus servicios, facilitando la implementación de campañas específicas y estrategias de retención. Con la adopción de este modelo predictivo, se espera mejorar la satisfacción del cliente y optimizar la gestión operativa, reduciendo significativamente la tasa de cancelación.


## Librerías Usadas

### Procesamiento de Datos
- `pandas`
- `numpy`
- `IPython.display`
- `tqdm`

### Visualización
- `matplotlib.pyplot`
- `seaborn`
- `collections.Counter`

### Modelado Predictivo
- `imblearn.over_sampling.SMOTE`
- `sklearn.model_selection.train_test_split`
- `sklearn.ensemble.RandomForestClassifier`
- `xgboost.XGBClassifier`
- `lightgbm.LGBMClassifier`
- `sklearn.neural_network.MLPClassifier`
- `sklearn.metrics.accuracy_score`
- `sklearn.metrics.roc_auc_score`
- `sklearn.metrics.roc_curve`
- `sklearn.metrics.log_loss`
- `shap`

---

## Cómo Ejecutar el Proyecto

1. **Clona el Repositorio:**
   ```bash
   git clone https://github.com/usuario/proyecto-cancelacion-clientes.git
   cd proyecto-cancelacion-clientes
