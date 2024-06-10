### Trabajo de Fin de Grado: Machine Unlearning - El Arte de Olvidar en la Era de la Inteligencia Artificial

Este repositorio contiene el código desarrollado como parte del Trabajo de Fin de Grado (TFG) titulado "Machine Unlearning: el arte de olvidar en la era de la Inteligencia Artificial", realizado por Pablo Noriega Vázquez. El proyecto se centra en la exploración de técnicas de "machine unlearning" aplicadas a modelos de regresión de edad.

### Descripción General

El código está dividido en dos notebooks diferentes, los cuales deben ser ejecutados en Google Colab. Para garantizar una ejecución eficiente, se recomienda cambiar el entorno de ejecución a GPU.

### Dependencias

Todas las dependencias necesarias se descargan automáticamente de un Google Drive proporcionado. Esto incluye los conjuntos de datos, las imágenes procesadas y la ResNet original utilizada para entrenar el modelo. La base de datos utilizada es un subset de imágenes que pertenecen a la base de datos UTK-FACES, disponible en: https://susanqq.github.io/UTKFace/. Para más información sobre el procesado de datos que se realiza, consultar el apartado 4.2 de la memoria. 

### Contenido del Repositorio

- **Training_models.ipynb**: Este notebook contiene el código para entrenar los modelos. Dado el peso de los modelos y los conjuntos de datos, se incluye únicamente el código para entrenar un modelo original y luego realizar fine-tuning para olvidar el grupo de 20 a 28 años. También se proporcionan los "forget sets" y los conjuntos de datos modificados para ello, lo que permite la aplicación de las técnicas de "machine unlearning". Las imágenes ya procesadas se incluyen para facilitar la ejecución del código.

- **CheckResults.ipynb**: En este notebook se evalúan las predicciones de los modelos. Se calcula el "utility" y el "forgetting" para cada modelo. También se incluyen ejemplos de predicciones de cada modelo para su prueba y análisis.

### Nombres de los Notebooks

- **Training_models.ipynb**: Notebook para entrenar los modelos.
- **CheckResults.ipynb**: Notebook para evaluar las predicciones de los modelos.

### Memoria del Trabajo

Además de los notebooks, este repositorio incluye la memoria completa del Trabajo de Fin de Grado. La memoria proporciona una descripción detallada del proyecto, la metodología utilizada, los experimentos realizados y los resultados obtenidos.

Para garantizar la ejecución exitosa de los notebooks, asegúrese de ejecutarlos en Google Colab y cambiar el entorno de ejecución a GPU. 

---
Pablo Noriega Vázquez, Trabajo de Fin de Grado (TFG) - Universidad de Barcelona
