# Evaluación de redes profundas convolucionales para la segmentación semántica de imágenes aéreas

Se presenta una implementación en PyTorch de una red totalmente convolucional para la segmentación semántica de imágenes aéreas, utilizando la arquitectura SegNet, donde se busca evaluar el desempeño de esta red neuronal basada en una estructura simétrica de codificador–decodificador, la primera parte (codificador) comprime la información de la imagen, mientras que la segunda parte (decodificador) la reconstruye para producir el mapa segmentado.
Para ello se utiliza el conjunto de datos **ISPRS Vaihingen**: ortofotos **IRRG** (9 cm ). 

Link de descarga: [
https://www.isprs.org/resources/datasets/benchmarks/UrbanSemLab/Default.aspx]
Clases (ISPRS):  

