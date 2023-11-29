<div id="top"></div>

<br />

<div align="center">
  <a href="https://github.com/sayuriGui/inteligencia-artificial.git">
    <img src="https://upload.wikimedia.org/wikipedia/commons/4/47/Logo_del_ITESM.svg" alt="Logo" width="80" height="80">
  </a>
<h3 align="center">Inteligencia artificial avanzada para la ciencia de datos II</h3>
  <p align="center">
        Nombre indefinido
</div>

## Construido con:

<div>
<img width="50px" height="50px" src="https://skillicons.dev/icons?i=py"/>
<img width="50px" height="50px" src="https://skillicons.dev/icons?i=vscode"/>
<img width="50px" height="50px" src="https://skillicons.dev/icons?i=github"/>
<img width="50px" height="50px" src="https://raw.githubusercontent.com/wiki/opencv/opencv/logo/OpenCV_logo_no_text.png"/>
<img width="50px" height="50px" src="https://www.clipartmax.com/png/full/349-3490136_anaconda-icon-anaconda-python-icon.png"/>
<img width="50px" height="50px" src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/2d/Tensorflow_logo.svg/1915px-Tensorflow_logo.svg.png"/>
<img width="50px" height="50px" src="https://pbs.twimg.com/media/GAD809AXoAAhneu?format=png&name=240x240"/>
<img width="80px" height="50px" src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d0/Google_Colaboratory_SVG_Logo.svg/2560px-Google_Colaboratory_SVG_Logo.svg.png"/>
</div>

## Descripción 
Copy paste la intro del reporte.

## Pre-requisito 

- python: ![version](https://img.shields.io/badge/version-3.9.18-red)
- CUDA: ![version](https://img.shields.io/badge/version-11.2-green)
- cuDNN: ![version](https://img.shields.io/badge/version-8.1.0-blue)
- TensorFlow (recommended): ![version](https://img.shields.io/badge/version-2.10-pink)

> **Nota 1:**
> Todo lo anterior a 2.10 no es compatible con la GPU en Windows Native

> **Nota 2:**
> Es necesario que se instalen los drivers de la GPU que usará. Puede hacerlo desde la siguiente [página](https://www.nvidia.com/Download/index.aspx)

## Ejecución
> **Antes de la ejecución:**
> Importante tener el dataset de los videos.

Durante la etapa del [análisis exploratorio](https://github.com/AlexGuzmn/Reto_AI_Period2/tree/main/An%C3%A1lisis_Exploratorio), se generó un conjunto de datos nuevo de máscaras del ventrículo izquierdo para su subdivisión en conjuntos de entrenamiento, prueba y validación. A partir de este punto, se procedió a la implementación del [modelo U-Net](https://github.com/AlexGuzmn/Reto_AI_Period2/tree/main/Modelo_Unet) con el objetivo de automatizar la predicción de las respectivas máscaras.

Posteriormente, se llevó a cabo la obtención de las [landmarks](https://github.com/AlexGuzmn/Reto_AI_Period2/tree/main/Modelo_Landmarks) con la misma intención de subdividirlas en conjuntos de entrenamiento, prueba y validación. Seguido de la aplicación del otro modelo modelo U-Net para predecir el rango probable donde estas landmarks podrían ubicarse.

## Autor/es
- Tania Sayuri Guizado Hernández | A01640092
- Joel Isaias Solano Ocampo  | A01639289
- Ernesto Reynoso Lizárraga  | A01639915
- Andrés Alejandro Guzmán González  | A01633819
