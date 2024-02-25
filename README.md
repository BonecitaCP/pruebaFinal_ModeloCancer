# pruebaFinal_ModeloCancer
#Modelos utilizados
- Regresión lineal
- Random Forest
- XGBClassifier

#Proceso
- Generar archivo base, el código se encuentra en el archivo generarBase.ipynb.
- Se generar tre archivos uno por modelo
- Revisión de caalidad de datos en cada archivo
- División del modelo de entrenamiento VS Test, en cada archivo se crearon dos para no afectar los datos de los modelos al aplicar la reducción de dimencionalidad.
- Se genera la matriz de confusión y se validan el exito de la predicción.

#Resultados
El análisis de resultados se encuentra en el INFORME MODELOS DE ENTRENAMIENTO.pdf

#Modelo mayormente exitoso 
El modelo con mayor nivel de éxito en la predicción fue XGBClassifier debido a la similutud con el modelo de árboles supero el nivel de predicción de Random Forest debido a que también se calcula mediante los residuales.

