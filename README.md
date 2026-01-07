# taxi-demand-time-series
Time series forecasting for airport taxi demand using Python

# Modelo de Series de Tiempo para la Predicción de Demanda Horaria de Taxis en Aeropuertos

## Descripción
Proyecto de ciencia de datos orientado a la predicción de la demanda horaria de taxis en aeropuertos, utilizando técnicas de análisis de series de tiempo. El objetivo es apoyar la planificación operativa y la asignación eficiente de recursos durante periodos de alta demanda.

## Objetivo
Desarrollar un modelo predictivo basado en series de tiempo que permita estimar la demanda futura de taxis, considerando patrones temporales como estacionalidad, tendencias y variaciones horarias.

## Datos
El proyecto utiliza datos históricos agregados de demanda de taxis con resolución temporal horaria.

Los datos fueron proporcionados en el contexto de un proyecto académico y no contienen información personal identificable.

## Metodología
Se realizó un análisis exploratorio enfocado en la identificación de patrones temporales, incluyendo:
- Tendencias
- Estacionalidad
- Ciclos diarios y semanales

Posteriormente, se aplicó ingeniería de características temporales y validación temporal para el entrenamiento y evaluación de modelos predictivos.

Se evitó el uso de validaciones aleatorias para preservar la naturaleza temporal de los datos y garantizar una evaluación realista del desempeño del modelo.

## Resultados
Los modelos desarrollados permitieron capturar adecuadamente los patrones temporales de la demanda, obteniendo predicciones consistentes para horizontes de corto plazo.

El proyecto demuestra la importancia de aplicar esquemas de validación adecuados en problemas de series de tiempo para evitar fugas de información y sobreestimación del desempeño.

## Tecnologías
- Python
- pandas
- scikit-learn
- Análisis de series de tiempo
- Ingeniería de características temporales

## Reproducibilidad
Para reproducir el análisis:
1. Clonar el repositorio.
2. Crear un entorno virtual.
3. Instalar dependencias desde `requirements.txt`.
4. Ejecutar el notebook ubicado en la carpeta `notebooks/`.
