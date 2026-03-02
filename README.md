# Proyecto_Parcial_1
Proyecto final: Evaluación predictiva de precipitaciones pluviales integrando datos de CONAGUA para clima/lluvia, radiación solar y contaminantes para analizar influencias a escala país.

# 🌧️ Predicción de Precipitaciones en Nuevo León

## 📝 Introducción
Este proyecto integra datos de CONAGUA, radiación solar y contaminantes para predecir lluvia en 20 estaciones de Nuevo León. El objetivo es analizar cómo factores ambientales influyen en el clima regional.

## 🛠️ Metodología
- *Datos:* 20 estaciones representativas de NL.
- *Validación:* Split Temporal (80% entrenamiento / 20% prueba) para garantizar predicciones realistas.
- *Modelos:* Regresión Logística, Random Forest, Gradient Boosting y LSTM.

## 📊 Resultados y Conclusión
La radiación solar resultó ser el factor más influyente en la formación de lluvias en el estado. El modelo Random Forest obtuvo el mejor desempeño con un F1-Score de 0.94. Se observó que los contaminantes industriales actúan como núcleos de condensación, mejorando la precisión del modelo en zonas urbanas.
