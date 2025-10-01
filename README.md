# Evaluación de redes profundas convolucionales para la segmentación semántica de imágenes aéreas

Se presenta una implementación en PyTorch de una red totalmente convolucional para la segmentación semántica de imágenes aéreas, utilizando la arquitectura SegNet, donde se busca evaluar el desempeño de esta red neuronal basada en una estructura simétrica de codificador–decodificador, la primera parte (codificador) comprime la información de la imagen, mientras que la segunda parte (decodificador) la reconstruye para producir el mapa segmentado.

## 📁 Conjunto de datos

**ISPRS Vaihingen**: ortofotos **IRRG** (9 cm GSD)

Clases (ISPRS):  
🛣️ **Carreteras**
🏠 **Edificios**
🌱 **Vegetación baja**
🌳 **Árboles**
🚗 **Carros**
❓ **Desorden**

Link de descarga: [https://www.isprs.org/resources/datasets/benchmarks/UrbanSemLab/Default.aspx]

## 💻 Notebook

Notebook Jupyter con el código fuente del proyecto, que inclye la carga de datos, preprocesamiento, entrenamiento SegNet, evaluación y generación de resultados.

## ⚙️ Utilidades

Este notebook requiere algunas bibliotecas útiles, como `torch`, `scikit-image`, `numpy` y `matplotlib`. Las cuales se instalalan por medio de pip install -r requirements.txt.

Se adjunta archivo de texto que contiene la lista de librerías necesarias junto con sus versiones compatibles, optimizadas para Python 3.10.0.

## 🧠 Modelo

Se adjunta el archivo .pt del modelo SegNet entrenado sobre el dataset ISPRS Vaihingen, listo para inferencia y evaluación.

## 📝 Documentos

Se incluye un reporte en formato de artículo que describe la implementación, entrenamiento y evaluación de la arquitectura SegNet.

## 🗺️ Resultados 

Se incluyen cuatro mosaicos resultantes del proceso de inferencia realizado con el modelo entrenado sobre la arquitectura SegNet.


## 🙌 Créditos

- Código basado en **SegNet** y cuadernos de **DeepNetsForEO**.
  [https://github.com/nshaud/DeepNetsForEO/tree/master]
- Implementación de la linea base presentada en:
  ["Más allá de RGB: teledetección urbana de muy alta resolución con redes profundas multimodales "](https://hal.archives-ouvertes.fr/hal-01636145),
  *Nicolas Audebert*, *Bertrand Le Saux* y *Sébastien Lefèvre*, ISPRS Journal, 2018.
  



