# Exámen Final

# 1. Importación de librerías necesarias
 -     Importa las librerías necesarias, como TensorFlow, Keras, NumPy, etc., para construir y entrenar el modelo CNN.
# 2. Creación de set de entrenamiento
 -     Recopila un conjunto de imágenes de diferentes tipos de carnes.
 -     Divide las imágenes en un conjunto de entrenamiento y un conjunto de pruebas (test set).
 -     Etiqueta cada imagen con la clase correspondiente (por ejemplo, pollo, cerdo, ternera, etc.).
# 3. Usamos el modelo CNN 
-     Define y construye un modelo de red neuronal convolucional (CNN) utilizando Keras.
-     Configura la arquitectura de la red, incluyendo capas convolucionales, de agrupación y totalmente conectadas.
-     Añade una capa de salida con la cantidad de neuronas igual al número de clases de carne.
# 4. Entrenamos el modelo CNN
-     Compila el modelo, especificando la función de pérdida y el algoritmo de optimización.
-     Ajusta el modelo utilizando el conjunto de entrenamiento.
-     Durante el entrenamiento, el modelo ajustará los pesos de las conexiones entre las neuronas para minimizar la pérdida y mejorar la precisión en la clasificación de las imágenes.
# 5. Predicción para Test
-     Utiliza el modelo entrenado para realizar predicciones sobre las imágenes del conjunto de pruebas.
-     Calcula la precisión y otras métricas de evaluación para medir el rendimiento del modelo.
# 6. Predicción para training
-     También puedes utilizar el modelo entrenado para realizar predicciones sobre las imágenes del conjunto de entrenamiento.
-     Esto puede ayudarte a evaluar si el modelo está sobreajustado (overfitting) o generaliza bien.
