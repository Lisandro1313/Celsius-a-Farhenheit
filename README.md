# Celsius-a-Farhenheit
El código en cuestión utiliza TensorFlow para crear un modelo de aprendizaje automático que realiza una conversión de temperatura de Celsius a Fahrenheit.

## Instrucciones de uso
Asegúrate de tener instalada la biblioteca de TensorFlow.
Ejecuta el código en tu entorno de Python.
Descripción del código
El código comienza importando las bibliotecas necesarias, incluyendo TensorFlow y NumPy. Luego, se definen dos arrays NumPy, celsius y fahrenheit, que contienen las temperaturas de entrada y salida correspondientes.

A continuación, se define un modelo de aprendizaje automático utilizando la API secuencial de Keras. El modelo consiste en una única capa densa con una unidad de salida, y se compila utilizando el optimizador Adam y la función de pérdida de error cuadrático medio.

Después de definir el modelo, se inicia el entrenamiento mediante el método fit(), utilizando los arrays de temperatura de entrada y salida. Se imprimen mensajes para indicar el inicio y finalización del entrenamiento.

Posteriormente, se utiliza la biblioteca Matplotlib para trazar el historial de la pérdida durante el entrenamiento. Se genera un gráfico que muestra la magnitud de la pérdida en función del número de épocas.

A continuación, se realiza una predicción utilizando el modelo entrenado. Se pasa el valor 100.0 a través del modelo y se imprime el resultado en Fahrenheit.

Finalmente, se imprimen las variables internas del modelo, que en este caso son los pesos y sesgos de la capa única utilizada. Estos valores representan los parámetros aprendidos durante el entrenamiento.
