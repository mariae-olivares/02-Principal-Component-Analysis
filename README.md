# 02-Principal-Component-Analysis

El [dataset](transfusion.data) que seleccioné para esta tarea fue *Blood Transfusion Service Center*, por Yeh (2008) y recuperado del [UC Irvine Machine Learning Repository](https://archive.ics.uci.edu/). Este dataset corresponde a un problema de clasificación dentro del área de negocios y marketing, específicamente en el contexto de campañas del área de salud.

Los datos fueron recolectados con el propósito de evaluar el modelo RFMTC, una adaptación del modelo RFM utilizado en marketing, con el objetivo de analizar el historial de donaciones y predecir el comportamiento de los donantes ante campañas de donación que se realizan cada tres meses.

El dataset contiene información de 748 donantes (datos), seleccionados de manera random, y cuenta con 4 variables predictoras:

- R -> Recency (integer): cantidad de meses desde la última donación.
- F -> Frequency (integer): número total de donaciones realizadas.
- M -> Monetary (integer): volumen total de sangre donada (en centímetros cúbicos).
- T -> Time (integer): cantidad de meses desde la primera donación.


La variable a -> objetivo (binaria) representa si el donante participó en la campaña de donación de sangre de marzo de 2007. Está clasifica de la siguiente manera:

- 1 = donó
- 0 = no donó

En el archivo [assignment_PCA.ipynb](assignment_PCA.ipynb) se encuentra el desarrollo del PCA.
