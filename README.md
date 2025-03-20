# breast-cancer-classification-lda-vs-dt

Este proyecto se centra en la clasificación de tumores benignos y malignos utilizando dos modelos de machine learning: Análisis Discriminante Lineal (LDA) y Árbol de Decisión. El objetivo es evaluar el desempeño de ambos modelos para identificar correctamente los tumores malignos y benignos, utilizando un conjunto de datos bien conocido.

Se utilizó el conjunto de datos Breast Cancer de scikit-learn para entrenar y evaluar los modelos. Este conjunto de datos contiene información sobre características de tumores, como el radio, la textura y el área, entre otras. El conjunto de datos está disponible a través de sklearn.datasets y puede cargarse de la siguiente manera:

from sklearn.datasets import load_breast_cancer
data = load_breast_cancer()

Este conjunto de datos tiene 569 muestras de tumores, de las cuales 357 son benignos y 212 son malignos. Los atributos incluyen medidas de propiedades de las células nucleares de los tumores.

El repositorio incluye los siguientes documentos:
- [Reporte en formato ipynb](./LDA_DT_BC.ipynb)
- [Reporte en formato html](./LDA_DT_BC.html)
