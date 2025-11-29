# Lab2_Clasificaci-n
Laboratorio 2 ML — Clasificación con SVM y Random Forest / Classification with SVM and Random Forest

## Descripción / Description

Este proyecto es la **Actividad de Clasificación** del curso de Aprendizaje Automático. El objetivo es **implementar y comparar** los clasificadores **Máquinas de Vectores de Soporte (SVM)** y **Random Forest** sobre el *dataset* **Covertype** de la UCI, el cual se utiliza para **predecir el tipo de cubierta forestal** (Forest Cover Type) basándose en **variables cartográficas**.

El *notebook* contiene espacios que deben ser **completados con el código y las respuestas solicitadas** para avanzar a través del preprocesamiento, entrenamiento y evaluación de los modelos.

**Dataset Referencia:** [https://archive.ics.uci.edu/dataset/31/covertype](https://archive.ics.uci.edu/dataset/31/covertype)

Este proyecto trata la **Actividad de Clasificación** del curso de Aprendizaje Automático, con el objetivo de implementar y comparar dos modelos de clasificación supervisada: **Máquinas de Vectores de Soporte (SVM)** y **Random Forest**.

El notebook guía a través de los pasos necesarios para el tratamiento de datos, el entrenamiento, y la evaluación de ambos clasificadores para un problema determinado.

---

## Objetivos / Objectives

- Poner en práctica la creación de modelos basados en máquinas de vector de soporte y random forest.
- Comprender el tratamiento de datos que hay que realizar para los modelos de clasificación.
- Entender y aplicar los algoritmos de **Random Forest** y **Support Vector Machine (SVM)** a un problema de clasificación.
- Evaluar y analizar los resultados de los clasificadores.
- Investigar la aplicación de los modelos de clasificación a problemas reales.

---

## Resultados de los Modelos / Model Results

*(Esta sección debe llenarse tras la ejecución y análisis del notebook. Se han incluido las métricas estándar de clasificación, en contraste con las métricas de regresión del Laboratorio 1.)*

| Métrica / Metric | Modelo Random Forest | Modelo SVM |
|------------------|----------------------|------------|
| **Accuracy**     | *[0.80]*             | *[0.90]*   |
| **Precision**    | *[0.81]*             | *[0.87]*   |
| **Recall**       | *[0.65]*             | *[0.85]*   |
| **F1-Score**     | *[0.80]*             | *[0.90]*   |

📈 **Interpretación:**
Se debe comparar el rendimiento de ambos modelos (Random Forest y SVM) basándose en las métricas de clasificación obtenidas. El análisis debe enfocarse en qué modelo ofrece el mejor equilibrio entre **Precision** y **Recall** para el problema en cuestión.

---

## Librerías utilizadas / Used Libraries

Las librerías principales utilizadas en este proyecto son:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `IPython.display` (para Markdown y visualización en Colab)

---

## Ejecución del proyecto / How to Run the Project

El proyecto se puede ejecutar de dos maneras, manteniendo la estructura de `README.md` de ejemplo:

### Opción 1: Ejecutar en Google Colab / Run on Google Colab

1.  Abrir el archivo `Lab2_Clasificacion.ipynb` en Google Colab.
2.  Asegurarse de que el entorno de ejecución (Runtime) esté configurado correctamente (Python 3).
3.  Ejecutar las celdas secuencialmente, completando los espacios de código requeridos para la actividad.

### Opción 2: Ejecutar localmente / Run Locally

1.  Clonar este repositorio o descargar el archivo `Lab2_Clasificacion.ipynb`.
2.  Asegurarse de tener todas las librerías listadas instaladas en su entorno Python (se recomienda usar un entorno virtual).
    ```bash
    pip install pandas numpy scikit-learn matplotlib seaborn
    ```
3.  Abrir el notebook en Jupyter Notebook o JupyterLab y ejecutar las celdas.
