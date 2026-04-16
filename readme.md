# 🇪🇸 Español / 🇬🇧 English

---

## 🇪🇸 Trabajo de Fin de Grado: Machine Unlearning - El Arte de Olvidar en la Era de la Inteligencia Artificial

Este repositorio contiene el código desarrollado como parte del Trabajo de Fin de Grado (TFG) titulado *"Machine Unlearning: el arte de olvidar en la era de la Inteligencia Artificial"*, realizado por Pablo Noriega Vázquez. El proyecto se centra en la exploración de técnicas de *machine unlearning* aplicadas a modelos de regresión de edad.

### Descripción General

El código está dividido en dos notebooks diferentes, los cuales deben ser ejecutados en Google Colab. Para garantizar una ejecución eficiente, se recomienda cambiar el entorno de ejecución a GPU.

### Dependencias

Todas las dependencias necesarias se descargan automáticamente de un Google Drive proporcionado. Esto incluye los conjuntos de datos, las imágenes procesadas y la ResNet original utilizada para entrenar el modelo.

La base de datos utilizada es un subset de imágenes que pertenecen a la base de datos UTK-FACES, disponible en:  
https://susanqq.github.io/UTKFace/

Para más información sobre el procesado de datos, consultar el apartado 4.2 de la memoria.

### Contenido del Repositorio

- **Training_models.ipynb**  
  Contiene el código para entrenar los modelos. Debido al tamaño de los modelos y datasets, se incluye el entrenamiento de un modelo base y su posterior *fine-tuning* para olvidar el grupo de edad de 20 a 28 años.  
  Se proporcionan los *forget sets* y datasets modificados para aplicar técnicas de *machine unlearning*.  
  Las imágenes ya procesadas se incluyen para facilitar la ejecución.

- **CheckResults.ipynb**  
  Evalúa las predicciones de los modelos, calculando métricas de *utility* y *forgetting*.  
  Incluye ejemplos de predicciones para análisis.

### Nombres de los Notebooks

- **Training_models.ipynb** → Entrenamiento de modelos  
- **CheckResults.ipynb** → Evaluación de resultados  

### Memoria del Trabajo

El repositorio incluye la memoria completa del TFG, donde se detalla la metodología, experimentos y resultados obtenidos.

Para ejecutar correctamente los notebooks:
- Usar **Google Colab**
- Activar **GPU**

---

**Pablo Noriega Vázquez**  
Trabajo de Fin de Grado (TFG) – Universidad de Barcelona  

---

## 🇬🇧 Bachelor's Thesis: Machine Unlearning – The Art of Forgetting in the Age of Artificial Intelligence

This repository contains the code developed as part of the Bachelor's Thesis titled *"Machine Unlearning: the art of forgetting in the age of Artificial Intelligence"*, carried out by Pablo Noriega Vázquez. The project focuses on exploring *machine unlearning* techniques applied to age regression models.

### Overview

The code is divided into two notebooks, which must be executed in Google Colab. For efficient execution, it is recommended to switch the runtime to GPU.

### Dependencies

All required dependencies are automatically downloaded from a provided Google Drive. This includes datasets, processed images, and the original ResNet used for training.

The dataset used is a subset of the UTK-Faces dataset:  
https://susanqq.github.io/UTKFace/

For more details about data preprocessing, refer to section 4.2 of the thesis document.

### Repository Contents

- **Training_models.ipynb**  
  Contains the code for training models. Due to dataset and model size, it includes training a base model and performing *fine-tuning* to forget the 20–28 age group.  
  *Forget sets* and modified datasets are provided to apply *machine unlearning* techniques.  
  Preprocessed images are included for convenience.

- **CheckResults.ipynb**  
  Evaluates model predictions by computing *utility* and *forgetting* metrics.  
  Includes sample predictions for testing and analysis.

### Notebook Names

- **Training_models.ipynb** → Model training  
- **CheckResults.ipynb** → Prediction evaluation  

### Thesis Document

The repository also includes the full Bachelor's Thesis, detailing methodology, experiments, and results.

To ensure proper execution:
- Use **Google Colab**
- Enable **GPU runtime**

---

**Pablo Noriega Vázquez**  
Bachelor's Thesis – University of Barcelona
