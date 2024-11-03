# PoseRecognition-TeachableMachine-

# Reconocimiento de Poses con Teachable Machine 💃

## Descripción del Proyecto

Este proyecto utiliza Teachable Machine para crear un modelo de reconocimiento de poses de ballet. Se han elegido 5 imágenes de 3 poses específicas: **cambré**, **plié** y **arabesque**, además de una categoría llamada **otras poses** para clasificar las poses que no pertenecen a las categorías anteriores.

## Objetivos del Proyecto

- **Clasificar poses de ballet**: Desarrollar un modelo capaz de identificar y diferenciar entre poses de ballet y otras poses.
- **Mejorar la precisión del modelo**: Ajustar el modelo para minimizar errores en la categorización.

## Proceso de Desarrollo

1. **Recolección de Datos**: Se seleccionaron 5 imágenes representativas de las poses de ballet y una categoría adicional.
2. **Entrenamiento del Modelo**: Utilizando Teachable Machine, se entrenó el modelo para reconocer las diferentes poses.
3. **Pruebas de Precisión**: Se realizaron varias pruebas para evaluar el rendimiento del modelo.

## Resultados y Pruebas Realizadas 📊

- **Arabesque**: La primera imagen fue correctamente clasificada.
- **Plié**: La segunda imagen también fue clasificada correctamente.
- **Cambré**: La tercera imagen se clasificó con un 68% de precisión, pero hubo confusión con el "arabesque" (30%).
- **Pose Distinta**: En la cuarta imagen, se determinó correctamente como “otras” con un 89% de certeza, a pesar de la similitud con el "arabesque".
- **Cambré Incorrecto**: La quinta imagen de "cambré" fue clasificada erróneamente como "otras poses".
- **Futbolista**: En una prueba inicial, se determinó incorrectamente que la imagen de una futbolista era un "plié" al 99%.
- **Ajuste del Modelo**: Después de añadir más imágenes a la categoría de "otras poses", el modelo identificó correctamente la imagen de la futbolista como "otras poses" con un 99% de precisión.

## Conclusiones

El modelo ha mostrado un buen rendimiento en la clasificación de poses de ballet, aunque se requiere más entrenamiento para mejorar la diferenciación entre poses similares. Las pruebas resaltan la importancia de tener un conjunto diverso de imágenes para entrenar y validar el modelo, lo que ayuda a reducir errores en la clasificación.

## Contacto 📫

Para cualquier consulta o sugerencia sobre el proyecto, ¡no dudes en ponerte en contacto!
