DATASET FINAL RESULTANTE

El dataset final utilizado para el entrenamiento del modelo mantiene las mismas imágenes del dataset original Fruits-360. La limpieza y preparación se realizan en el código, no generando nuevos archivos de imagen.

Las principales transformaciones son:
- Redimensionado de las imágenes a 224 x 224 píxeles.
- Normalización mediante la función preprocess_input de MobileNetV3
  (tensorflow.keras.applications.mobilenet_v3.preprocess_input).
- División en subconjuntos de entrenamiento, validación y prueba a partir de las carpetas Training y Test.

Estas transformaciones se implementan en el notebook `code/TF_grupo4_CNN.ipynb` en la sección de preprocesamiento.
