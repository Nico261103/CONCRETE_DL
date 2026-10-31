# CONCRETE_DL
Avance de la aplicación de Transfer Learning para la detección de patologías encontradas en imágenes superficiales de concreto.
## Secuencia lógica:
- Entrenar una red nueronal convulacional (CNN) propia con la finalidad de compararla con la red neuronal residual RESNET50 y su aplicación ImageNet que está pre entrenada para la detección de cierta geometrías inicialmente, pudiendo modificar capas posteriores e ir observando la salida de probabilidad en cada patch/división de las imágenes propuestas de entrada para el entrenamiento. Finalmente se utiliza GradCamp para obtener mapas de calor conforme a la probabilidad y ubicación de la posible anomalía en la superficie, lo que nos da interpretabilidad visual de los resultados, tal cual lo haría un humano al querer reconocer lo que está observando. 
## Datasets
- Se tomaron datos de una librería existente de imágenes para el entrenamiento, la cual tenía 20000 imágenes pero solo tomamos algunas con la finalidad de seguir teniendo un primer entrenamiento y ver su comportamiento frente a datos heterogéneos respecto a sus características.
## Limitaciones
- Por ahora se dispuso de 200 imágenes, lo cual podría indicarnos un accuracy de 100%, sin embargo, sabemos que frente a una cantidad masiva de datos, al igual que los humanos, a mayor experiencia y tiempo en algo, mejor capacidad de detección y solución de problemas, es por ello que el modelo puede mejorarse aún más ya que el índice de confiabilidad obtenido fue de 88.43% como mínimo, valor que de igual manera supera a la CNN que se estuvo entrenando previamente.
## Conclusiones
- No pretendemos decir que no se pueda entrenar la red neuronal de detección y clasificación desde cero, lo que intentamos reproducir es que se puede hacer uso de transferencia de aprendizaje para facilitar el trabajo de la red y usar redes neuronales residuales como parte de la innovación que nació hace años atrás tomando en cuenta operaciones básicas del cálculo matemático. 
