# Predicción de Cancelaciones de Clientes

## Descripción del Proyecto

En este proyecto se desarrolló un modelo predictivo con el propósito de predecir la cantidad de pedidos de taxis para la próxima hora y así optimizar la disponibilidad de conductores durante las horas pico. Se busca maximizar la eficiencia operativa y mejorar la satisfacción del cliente al anticipar la demanda de taxis en los aeropuertos.

El proceso incluyó la recopilación y análisis de datos históricos de pedidos, asegurando la integridad de la información. Se exploraron tendencias, estacionalidad y ruido en los datos, lo que permitió identificar patrones clave en la demanda. Se implementaron varios modelos de Machine Learning, incluyendo **RandomForestClassifier, XGBClassifier, LGBMClassifier y MLPClassifier**, evaluados con la métrica **AUC-ROC** para medir su rendimiento.

Los resultados indicaron que el modelo basado en **LinearRegression** ofreció el mejor desempeño, logrando un **RMSE de 8.91**, el más bajo entre todas las pruebas realizadas. Además, su tiempo de entrenamiento y predicción fue significativamente menor en comparación con los modelos no lineales. Con este modelo, se podrá prever con mayor precisión la demanda de taxis y tomar decisiones estratégicas para optimizar la asignación de vehículos, maximizando así la eficiencia operativa y la rentabilidad del servicio.


#### Criterios de Evaluación

- **AUC-ROC < 0.75:** 0 SP
- **0.75 ≤ AUC-ROC < 0.81:** 4 SP
- **0.81 ≤ AUC-ROC < 0.85:** 4.5 SP
- **0.85 ≤ AUC-ROC < 0.87:** 5 SP
- **0.87 ≤ AUC-ROC < 0.88:** 5.5 SP
- **AUC-ROC ≥ 0.88:** 6 SP

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
