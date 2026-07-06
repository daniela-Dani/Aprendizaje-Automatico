# Comparación entre LDA y QDA utilizando el Wine Dataset

## Descripción

Este proyecto implementa y compara dos algoritmos de clasificación supervisada:

- Linear Discriminant Analysis (LDA)
- Quadratic Discriminant Analysis (QDA)

El objetivo es analizar las diferencias entre ambos modelos utilizando el Wine Dataset, evaluando su desempeño mediante métricas de clasificación, matrices de confusión y fronteras de decisión.

---

## Objetivos

- Explorar el Wine Dataset.
- Implementar el modelo LDA.
- Implementar el modelo QDA.
- Comparar el desempeño de ambos modelos.
- Analizar las fronteras de decisión generadas por cada algoritmo.
- Interpretar los resultados obtenidos.

---

## Dataset utilizado

Se utilizó el **Wine Dataset**, disponible de forma nativa en la biblioteca **Scikit-Learn**.

Características del conjunto de datos:

- 178 observaciones.
- 13 variables predictoras.
- 3 clases de vino.

El dataset no necesita descargarse manualmente, ya que se carga directamente mediante:

```python
from sklearn.datasets import load_wine

wine = load_wine()
```

---

## Tecnologías utilizadas

- Python 3
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Scikit-Learn

---

## Archivos del repositorio

- `LDA_QDA_Wine.ipynb` → Notebook desarrollado en Google Colab.
- `Informe_LDA_QDA.pdf` → Informe técnico del proyecto.
- `README.md` → Descripción del proyecto e instrucciones de ejecución.

---

## Cómo ejecutar el proyecto

1. Clonar el repositorio:

```bash
git clone https://github.com/TU-USUARIO/TU-REPOSITORIO.git
```

2. Abrir el archivo `LDA_QDA_Wine.ipynb` en Google Colab o Jupyter Notebook.

3. Instalar las dependencias (si es necesario):

```bash
pip install pandas numpy matplotlib scikit-learn
```

4. Ejecutar todas las celdas del notebook en el orden en que aparecen.

El Wine Dataset se cargará automáticamente desde Scikit-Learn.

---

## Modelos implementados

En este proyecto se implementaron los siguientes modelos de clasificación:

- Linear Discriminant Analysis (LDA)
- Quadratic Discriminant Analysis (QDA)

Ambos modelos fueron evaluados mediante:

- Accuracy
- Precision
- Recall
- F1-score
- Matriz de confusión

Finalmente, se compararon las fronteras de decisión utilizando dos variables del Wine Dataset.

---

## Principales hallazgos

- Ambos modelos lograron clasificar correctamente las observaciones del Wine Dataset con un alto desempeño.
- LDA construye fronteras de decisión lineales al asumir que todas las clases comparten la misma matriz de covarianza.
- QDA genera fronteras cuadráticas al permitir que cada clase tenga una matriz de covarianza diferente.
- Las métricas de evaluación facilitaron la comparación objetiva entre ambos algoritmos.
- La elección entre LDA y QDA depende del comportamiento del conjunto de datos y del cumplimiento de sus supuestos estadísticos.

---

## Autor

**Daniela Pincay**

Ingeniería en Ciencias de Datos e Inteligencia Artificial

Universidad de Guayaquil
