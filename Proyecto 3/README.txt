Proyecto 3: Stitching
Se desea realizar la reconstrucción de una escena del crimen a partir de la unión de varias fotografías
(Stitching) con el fin de reproducir los hechos. Las fotografías han sido tomadas desde diferentes
perspectivas con el fin de abarcar la mayor cantidad de información visual de la escena.
La unión de las fotografías (Stitching) se debe realizar mediante el algoritmo desarrollado en “Automatic
Panoramic Image Stitching using Invariant Features”, y la unión (Stitching) debe ser una por una a la
escena reconstruida, esto quiere decir que, al unir las 2 primeras fotografías se obtendría la escena del
crimen inicial, y de allí se deben ir uniendo una por una las demás fotografías (no se puede realizar la
unión de todas las fotografías al mismo tiempo). Para la visualización del paso a paso de la unión de cada
fotografía (Stitching) a la escena del crimen se debe realizar mediante el detector y descriptor SIFT
(visualizando la magnitud y la dirección de cada gradiente), el emparejamiento de características BruteForce (visualizando los puntos de interés emparejados) y la obtención de los parámetros de movimiento
entre planos (matriz de transformación de perspectiva) utilizando la estimación de homografía con
Random Sample Consensus(RANSAC). Se evaluará el paso a paso de la unión de cada una de las fotografías
(Stitching) a la escena del crimen y el correcto uso de los algoritmos para realizar cada una de las uniones.
Entregable
- Realizar una presentación con sustentación oral de máximo 15 minutos explicando el paso a paso
(diagrama de flujo o de bloques) y análisis del resultado de cada etapa implementada en la
imagen.
- Realizar un reporte escrito explicando el paso a paso (diagrama de flujo o de bloques) y análisis
del resultado de cada etapa implementada en la imagen.
- Adjunte en un comprimido la presentación, el reporte escrito y el código usado para las
modificaciones.
