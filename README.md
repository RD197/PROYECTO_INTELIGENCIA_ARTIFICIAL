# PROYECTO_INTELIGENCIA_ARTIFICIAL
PROYECTO FINAL INTELIGENCIA

# Proyecto de Red Neuronal para Identificación de Imágenes

Este proyecto desarrolla una red neuronal artificial sin uso de librerias especializadas capaz de identificar imágenes, entrenada específicamente para una imagen de 600x800 píxeles. La red neuronal se entrena utilizando el algoritmo de retropropagación (backpropagation).

## Características

- **Captura de imágenes**: La aplicación captura 10 imágenes utilizando la cámara web y las guarda como `captura1.jpg`, `captura2.jpg`, ..., `captura10.jpg`.
- **Entrenamiento de la red neuronal**: La red neuronal se entrena para reconocer una imagen específica, con una resolución de 600x800 píxeles.
- **Backpropagation**: La red utiliza el algoritmo de retropropagación para ajustar los pesos durante el entrenamiento.
- **Reconocimiento de imágenes**: Una vez entrenada, la red neuronal puede identificar la imagen que se utilizó para entrenarla y otras imágenes.

## Requisitos

Este proyecto requiere las siguientes librerías de Python:
- **opencv-python**: Para capturar video e imágenes desde la cámara.
- **pillow**: Para manipular las imágenes en formato PIL.
- **matplotlib**: Para visualizar las imágenes capturadas.
- **numpy**: Para trabajar con matrices y realizar operaciones matemáticas.
- **tkinter**: Para crear la interfaz gráfica.

### Cómo instalar las librerías necesarias

Para instalar las librerías necesarias, puedes usar el archivo `install_libraries.sh` incluido en este repositorio.

1. **Usar el script de instalación (recomendado)**

   Descarga o clona este repositorio y ejecuta el siguiente comando para instalar todas las dependencias:

   ```bash
   chmod +x install_libraries.sh
   ./install_libraries.sh
