# Predicción de Cancelaciones de Clientes

## Descripción del Proyecto




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
