# 🧠 Proyecto Final - Programación PRG-2025-1

Este repositorio contiene el desarrollo del trabajo final del curso **Programación PRG-2025-1**, enfocado en la aplicación de técnicas de analítica y ciencia de datos para resolver un problema de clasificación supervisada.

---

## 📌 Problema Predictivo

El objetivo del proyecto es predecir si una persona gana **más de $50,000 al año** en función de características personales y laborales, usando datos del censo de EE.UU. (Adult Dataset).

---

## 📊 Dataset

- **Nombre:** Adult (también conocido como Census Income)
- **Fuente:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/adult)
- **Instancias:** ~48,842
- **Atributos:** 14 + variable objetivo
- **Tipo de problema:** Clasificación binaria (`<=50K` / `>50K`)
- **Tratamiento de datos faltantes:** Filtrado de filas con valores nulos (`?`)

---

## 🧪 Modelos Usados

Se implementaron y evaluaron dos modelos de aprendizaje supervisado:

1. **Random Forest Classifier**
   - Hiperparámetros optimizados con `GridSearchCV`
   - Evaluado con métricas de precisión, recall, F1-score
   - Curva de aprendizaje incluida

2. **Support Vector Machine (SVM)**
   - Comparación de kernel `linear` y `rbf`
   - Optimización con `GridSearchCV`
   - Curva de aprendizaje incluida

---

## 🧼 Preprocesamiento

- Codificación de variables categóricas (`LabelEncoder`)
- Escalamiento de variables numéricas (`StandardScaler`)
- Eliminación de filas con valores nulos
- División en `train` y `test` (80/20)

---

## 📈 Comparación

- Ambos modelos fueron comparados en términos de precisión y desempeño.
- Se utilizó la métrica **Cohen's Kappa** para evaluar la concordancia entre las predicciones.


