# OpenCV Face Detection and Capture

Este proyecto contiene una serie de scripts de Python que utilizan OpenCV para la detección y captura de rostros, tanto desde imágenes estáticas como en tiempo real a través de video.

## Estructura del Proyecto

- `src/deteccion_rostros.py`: Script para detectar rostros en una imagen estática.
- `src/deteccion_rostros_video.py`: Detecta rostros en tiempo real usando la cámara web.
- `src/capturandoRostrosVideo.py`: Captura y guarda rostros detectados desde el video de la cámara.
- `src/capturandoRostrosEnImagen.py`: Identifica y extrae rostros de una sola imagen.
- `src/capturandoRostrosDesdeBancoDeimagenes.py`: Procesa una carpeta de imágenes para extraer y guardar los rostros encontrados.
- `haarcascade_frontalface_default.xml`: Archivo de configuración del clasificador Haar Cascade para la detección de rostros.
- `imagenes/`: Carpeta que contiene imágenes de ejemplo para procesar.

## Requisitos

El proyecto requiere Python 3.8 o superior y las siguientes librerías:
- `opencv-python`
- `numpy`

## Instalación

Puedes instalar todas las dependencias necesarias utilizando el archivo `pyproject.toml` incluido:

```bash
pip install .
```

## Uso

Para ejecutar cualquiera de los scripts, simplemente utiliza el comando `python`:

```bash
python src/deteccion_rostros_video.py
```

> **Nota:** Algunos scripts de captura guardarán los rostros detectados en una carpeta llamada `Rostros encontrados`.
