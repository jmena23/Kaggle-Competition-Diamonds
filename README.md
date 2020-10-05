# Kaggle-Competition-Diamonds
Quinto proyecto Ironhack - Bootcamp Data Analytics: Kaggle Competition Diamonds

![compro-vendo-oro-plata-madrid-62](https://user-images.githubusercontent.com/61025562/95113143-e4515d80-0739-11eb-8253-09362467298a.jpg)

## Objetivo del proyecto

El objetivo de este proyecto es entrenar uno o varios modelos de regresión para intentar predecir de la manera más ajustada el precio de los diamantes de un dataset dado. Los resultados obtenidos por el modelo se subirán a Kaggle donde competiremos por ser el que mejor ajuste sus predicciones al precio real de los diamantes.

Los datasets y las reglas de la competición las puedes consultar en el siguiente enlace:

https://www.kaggle.com/c/diamonds-datamad0820/


## Metodología

La metodología seguida para realizar el proyecto es la siguiente:

- Análisis del dataset de training para validar datos y adecuarlos a las necesidades del modelo

- Entrenamiento de modelos simultáneamente para decidir, en base a las métricas utilizadas, cuál se adecua mejor a nuestro dataset.

- Testeo con el o los modelos seleccionados.

- Obtención de una predicción ajustada a los valores relaes.

- Subida de los resultados a la competición en Kaggle.

## Organización del proyecto

- Archivo Data Cleaning donde se encuentra la exploración de los datos y su limpieza

- Los 3 .ipynb con los modelos entrenados y sus predicciones

- **Carpeta csv preparado** donde se encuentran los dataset preparados para entrenar los modelos.

- **Carpeta modelos** donde se encuentra la selección de los modelos utilizados según métricas

- **Carpeta resultados** donde se encuentran los diferentes resultados que hemos ido obteniendo de los modelos

- Diapositiva con resumen de los resultados

## Conclusiones

De los 3 modelos seleccionados finalmente se ha trabajado con 2, el ExtraTreeRegressor y el RandomForestRegressor, incidiéndo finalmente en el primero ya que fue el que mejores resultados nos estaba dando. Los resutados los puedes consultar en los jupyter notebboks.

## Enlaces de interés

https://scikit-learn.org/stable/supervised_learning.html#supervised-learning

https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.ExtraTreesRegressor.html

https://pandas.pydata.org/docs/

https://matplotlib.org/3.3.1/contents.html

https://seaborn.pydata.org

