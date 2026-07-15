# ecuadorian-cacao-moniliasis
Trabajo Fin de Máster (UNIR): Detección de moniliasis (*Moniliophthora roreri*) en cultivos de cacao ecuatoriano mediante técnicas de visión artificial

Este repositorio contiene el código fuente, los modelos entrenados y los experimentos realizados para el Trabajo Fin de Máster (TFM) titulado:

**"Estudio experimental para identificar la presencia de moniliasis en cultivos de cacao ecuatoriano utilizando técnicas de visión artificial"**

El proyecto aborda la detección temprana de *Moniliophthora roreri*, el hongo causante de la moniliasis, una de las principales amenazas para la producción de cacao fino de aroma en Ecuador. Se implementan dos líneas experimentales:

- **Línea 1:** Pipeline en cascada con YOLO11 (detección de mazorcas) + ResNet50+CBAM (clasificación binaria)
- **Línea 2:** Segmentación precisa con SAM2 + clasificación con ConvNeXt, con explicabilidad mediante Grad-CAM e IoU
