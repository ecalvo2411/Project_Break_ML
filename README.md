# Project Break Machine Learning

## Objetivo del PB:
- Identificar los principales factores de riesgo de Stroke
- Crear un modelo de Machine Learning para predicir las probabilidades de sufrir Stroke.

## Características Dataset:
- Acceso público.
- Cuenta con 5110 entradas.
- Publicado en [Kaggle](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset)

## Solución de objetivos:
- La solución principal se dará mediante un EDA donde buscaremos las principales relaciones entre los distintos factores de riesgo y la probabilidad de sufrir Stroke.
- Luego procederemos a incluir estos datos ya analizados en los modelos empleados para encontrar las probabilidas de sufrir Stroke.

## Estructura del Repositorio:

```python
├── src/                # El directorio source que contiene el resto de carpetas
│   ├── data/           # Dataset utilizado 
│   ├── img/            # Imágenes utilizadas en el proyecto
│   ├── models/         # Modelos guardados en formato pickle o joblib
│   ├── notebooks/      # Notebooks de desarrollo y pruebas
├── main.ipynb          # Notebook final
├── Presentacion.pdf    # Documento soporte de la exposición en vídeo
├── README.md           # Fichero README resumen del proyecto
```
## Tecnologías Utilizadas:
- Python 
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Análisis Exploratorio de Datos (EDA)
- Regresión Logística

## Instrucciones de Reproducción:

- Primero Cargamos el dataset con sus respectivas entradas de datos. Ejecutamos los distintos análisis univariante, bivariante y multivariante. Luego procedemos a ejecutar los distintos modelos de procesado de datos con los modelos supervisados, ya que nosotros ingresaremos los datos a analizar. 


## Resultados de los Objetivos:

## Autores:
- - Este proyecto ha sido desarrollado por el equipo de tres integrantes:
    -   👤 Iván Gómez – [@betaivan-10](https://github.com/BetaIvan-10)
    - 	👤 Eric Calvo – [@ecalvo2411](https://github.com/ecalvo2411)
    -	👤 Marcos Martinez– [@mmsbi02](https://github.com/mmsbi02)

## Conclusiones 

Tras comparar ambos modelos, la regresión logística resulta ser el modelo más adecuado para este proyecto. Aunque el modelo alternativo puede obtener buenas métricas globales, la regresión logística ofrece una mayor capacidad para detectar los casos reales de ictus y además es más interpretable, lo cual es especialmente importante en aplicaciones médicas. Por ello, se considera el modelo más apropiado para un sistema de predicción de riesgo de ictus.




