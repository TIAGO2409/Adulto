# 🎓 Proyecto Final - Programación PRG-2025-1

Este repositorio contiene el desarrollo del trabajo final del curso **Programación PRG-2025-1**, donde se aplican herramientas de programación y ciencia de datos para resolver un problema de clasificación.

---

## 🧠 ¿De qué trata el proyecto?

El objetivo fue predecir si una persona gana más o menos de **$50,000 al año**, utilizando datos reales del censo de Estados Unidos. Esto se logró aplicando limpieza de datos, codificación, entrenamiento de modelos y análisis de resultados.

---

## 📊 Dataset utilizado

- **Nombre:** Adult Dataset
- **Fuente:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/adult)
- **Instancias:** ~49,000 personas
- **Atributos:** 14 + variable objetivo (`income`)
- **Variable objetivo:** `income` (0 = ≤50K, 1 = >50K)

---

## ⚙️ Pasos del proyecto

1. **Exploración de datos:** Conocer el contenido del dataset, columnas, tipos de datos y valores faltantes.
2. **Preprocesamiento:** Eliminar filas con datos nulos, codificar valores categóricos y escalar columnas numéricas.
3. **Entrenamiento de modelos:**
   - **Random Forest** (modelo 1): Precisión ~85%
   - **SVM (Support Vector Machine)** (modelo 2): Precisión ~84%
4. **Comparación de modelos:** Se midió qué tan parecidas eran las predicciones usando **Cohen's Kappa** (resultado: ~0.71).
5. **Conclusiones y recomendaciones** documentadas en un informe final.
