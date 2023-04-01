# Kaggle_competition
---

# [Datos](data/train.csv)

|**Datso**| **Significado**|
| **id** | solo para archivos de envío de prueba y muestra, id para identificación de muestra de predicción.|
|**price**| precio en USD.|
|**carat**| peso del diamante.|
|**cut**| calidad del corte (Regular, Buena, Muy buena, Premium, Ideal).|
|**color**| color diamante.|
|**clarity**| una medida de cuán claro es el diamante.|
|**x**| longitud en mm.|
|**y**| ancho en mm.|
|**z**| profundidad en mm.|
|**depth**| porcentaje de profundidad total = z / media (x, y) = 2 * z / (x + y) (43--79).|
|**table**| ancho de la parte superior del diamante en relación con el punto más ancho (43--95).|

---
# [Análisis exploratorios](notebooks/1.1%20Exploraci%C3%B3n.ipynb)

**Selección de variables predictoras:**

Durante la exploración de los datos y su relevancia respecto a la variable respuesta, es decir, el valor a predecir, se ha observado que algunos datos están altamente relacionados con otras variables predictoras (datos necesarios para predecir la variable respuesta), los que nos indica que pueden ser dos forma de exponer un mismo valor. Cuando se hace un modelo de predicción el número de valores puede determinar la calidad de la predicción y en algunos casos es bueno tener muchos valores, pero en este caso al ser un valor con alta relación con otras de nuestros datos puede provocar una peor predicción. De esta manera se decidió excluir de algunos de los modelos los siguientes valores: `depth` y `table`.

**Gestión de Outliers:**

---
# [Mejor modelo](notebooks/2.4%20Modelo_4.ipynb)



---
# [Predicción](notebooks/1.1%20Exploraci%C3%B3n.ipynb)

