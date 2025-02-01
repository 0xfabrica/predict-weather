# Predicción del Clima: Proyecto de Análisis de Datos Meteorológicos

## Descripción del Proyecto
Este proyecto tiene como objetivo analizar datos meteorológicos y desarrollar un modelo de clasificación que prediga las condiciones climáticas basándose en datos históricos.

Se han utilizado técnicas de **análisis exploratorio de datos (EDA)** y modelos de **aprendizaje automático**, con el fin de comprender patrones climáticos y mejorar la capacidad predictiva del modelo.

## Datos Utilizados
El dataset utilizado, **weather_data.csv**, contiene información detallada sobre variables meteorológicas, entre ellas:

- **Fecha**: Fecha de la predicción (YYYY-MM-DD).
- **Temperatura (°C)**: Temperatura máxima, mínima y promedio del día.
- **Precipitación (mm)**: Cantidad total de lluvia o nieve.
- **Velocidad del Viento (km/h)**: Velocidad sostenida y ráfagas.
- **Condiciones Meteorológicas**: Soleado, nublado, lluvioso, etc.
- **Humedad (%)**: Humedad relativa promedio.
- **Presión Atmosférica (hPa)**: Presión a nivel del mar y tendencia de la presión.
- **Radiación Solar (W/m²)**: Intensidad de la radiación solar.

## Tecnologías Utilizadas
El proyecto fue desarrollado en **Python** y hace uso de las siguientes librerías:

- `pandas` para manipulación de datos.
- `numpy` para operaciones numéricas.
- `matplotlib` y `seaborn` para visualización de datos.
- `scikit-learn` para entrenamiento y evaluación de modelos de aprendizaje automático.

## Pasos del Análisis
1. **Carga y limpieza de datos**: Eliminación de columnas innecesarias y tratamiento de valores nulos.
2. **Exploración de datos**:
   - Histogramas y distribuciones.
   - Análisis de correlaciones entre variables.
   - Generación de pairplots para visualizar relaciones entre variables.
3. **Entrenamiento del Modelo**:
   - Se empleó un **Random Forest Classifier** para predecir la condición meteorológica.
   - División en datos de entrenamiento y prueba (70%-30%).
   - Normalización de variables con `StandardScaler`.
4. **Evaluación del Modelo**:
   - Cálculo de la matriz de confusión.
   - Reporte de clasificación (`classification_report`).
   - Importancia de las variables en la predicción.
   - Precisión del modelo 0.91

## Visualizaciones Clave
- Distribución de la temperatura y su relación con la humedad.
- Tendencias en la presión atmosférica.
- Evolución de la radiación solar a lo largo del tiempo.
- Matriz de correlación entre variables climáticas.

## Resultados y Conclusiones
- El modelo **Random Forest** obtuvo una buena capacidad predictiva para clasificar condiciones climáticas.
- Las variables más influyentes en la predicción fueron la temperatura, la humedad relativa y la presión atmosférica.
- Se identificó una correlación inversa entre la temperatura y la humedad.
- La radiación solar y la presión atmosférica muestran patrones cíclicos.

## Instalación y Uso
Si deseas replicar el análisis, sigue estos pasos:

1. Clona el repositorio:
   ```sh
   git clone https://github.com/0xfabrica/predict-weather.git
   ```
2. Instala las dependencias:
   ```sh
   pip install -r requirements.txt
   ```
3. Ejecuta el script principal:
   ```sh
   python predict_weather.py
   ```

## Contacto y Feedback
Este proyecto forma parte de mi **ruta de aprendizaje en ciencia de datos** y está disponible en mi **GitHub público**. Estoy abierto a **críticas y sugerencias** para mejorar el análisis y la implementación del modelo.

Si tienes alguna idea o sugerencia, no dudes en abrir un issue o contactarme.

**¡Gracias por tu interés y felices análisis!** 🚀

