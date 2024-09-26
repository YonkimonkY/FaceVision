# FaceVision


Este proyecto fue desarrollado como parte de la asignatura final de **Visión por Computador**. Su objetivo es crear una interfaz de usuario en Python que utilice la biblioteca OpenCV para el análisis de imágenes capturadas en tiempo real a través de una cámara. La aplicación es capaz de detectar y predecir el género, la edad aproximada y la emoción de las personas, utilizando técnicas avanzadas de visión por computadora y aprendizaje automático.

## Características Principales

- **Detección en Tiempo Real**: La aplicación puede capturar y procesar imágenes en tiempo real, proporcionando resultados inmediatos sobre el género, la edad y la emoción de las personas detectadas.
  
- **Predicción de Género, Edad y Emociones**: Utiliza modelos preentrenados para clasificar el género y la edad, además de un detector de emociones que identifica la emoción predominante de cada rostro.

- **Interfaz Gráfica de Usuario (GUI)**: Implementada con la biblioteca Tkinter, la interfaz es intuitiva y fácil de usar, permitiendo a los usuarios interactuar con la aplicación de manera eficiente.

## Tecnologías Utilizadas

- **Python**: Lenguaje de programación utilizado para desarrollar la aplicación.
- **OpenCV**: Biblioteca de visión por computadora que permite la captura de imágenes y la detección de rostros.
- **FER (Facial Expression Recognition)**: Utilizada para detectar emociones en los rostros.
- **Tkinter**: Framework para crear la interfaz gráfica de usuario.
- **Modelos DNN**: Modelos preentrenados para la detección de edad y género, cargados mediante OpenCV.

## Instalación

Para ejecutar este proyecto, asegúrate de tener instaladas las siguientes bibliotecas en tu entorno de Python:

bash
`pip install opencv-python opencv-python-headless fer Pillow`

## Archivos de Modelo Requeridos

Además, necesitarás descargar los siguientes archivos de modelo y guardarlos en el directorio del proyecto:

- `deploy_age.prototxt` y `age_net.caffemodel` para la detección de edad.
- `deploy_gender.prototxt` y `gender_net.caffemodel` para la detección de género.

## Cómo Ejecutar la Aplicación

1. Asegúrate de tener la cámara web conectada a tu computadora.
2. Ejecuta el archivo de Python que contiene el código del proyecto.
3. La interfaz se abrirá y comenzará a capturar imágenes desde la cámara.
4. Acércate a la cámara y observa cómo se muestran los resultados de la detección en la pantalla.

## Uso

Una vez que la aplicación esté en funcionamiento, podrás ver en tiempo real:

- Un rectángulo verde alrededor de cada rostro detectado.
- La edad aproximada del rostro en la parte superior.
- El género del individuo debajo de la edad.
- La emoción predominante junto con su probabilidad en forma de barra de progreso.

## Conclusión

Este proyecto es una excelente demostración de cómo las técnicas de visión por computadora pueden aplicarse para el análisis de rostros y emociones en tiempo real. Además, permite explorar el potencial de los modelos de aprendizaje automático en la clasificación de características humanas.

