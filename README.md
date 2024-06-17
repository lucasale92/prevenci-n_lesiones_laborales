<div align="center">
  <img src="/src/static/logo.jpeg" alt="Logo del proyecto" width="500">
  <h1>Predicción de Rotación de Puestos para la Prevención de Lesiones en Fábricas de Ensamblaje</h1>
</div>

<p align="center">
  <a href="https://politecnico.tdf.gob.ar/">
    <img src="https://img.shields.io/badge/institución-Politécnico%20Malvinas%20Argentinas-blue" alt="Institución">
  </a>
  <a href="https://www.example.com/carrera">
    <img src="https://img.shields.io/badge/carrera-Tecnicatura%20Superior%20en%20Ciencia%20de%20Datos%20e%20Inteligencia%20Artificial-brightgreen" alt="Carrera">
  </a>
  <a href="https://www.example.com/asignatura">
    <img src="https://img.shields.io/badge/asignatura-Aprendizaje%20Automático-orange" alt="Asignatura">
  </a>
  <a href="https://www.example.com/año">
    <img src="https://img.shields.io/badge/año-2024-yellowgreen" alt="Año">
  </a>
</p>
<p align="center">
  <strong>Autor:</strong> Lucas Alejandro Riveros
</p>
<p align="center">
  <strong>Profesor:</strong> Martin Mirabete
</p>
------------


**{{cookiecutter.description}}** *Descripción del Proyecto*

El objetivo principal de este proyecto es aplicar técnicas de Aprendizaje Automático para predecir cuándo un trabajador de una fábrica de ensamblaje debe rotar de un puesto específico para prevenir lesiones. Utilizando datos históricos de lesiones, información demográfica de los trabajadores y detalles de los puestos de trabajo, se desarrollará un modelo predictivo que ayude a identificar el momento óptimo para la rotación, considerando factores como la duración en el puesto, la repetitividad de las tareas y la postura requerida. Este análisis busca proporcionar insights valiosos para mejorar la seguridad y el bienestar de los trabajadores en el entorno de fabricación.
Dataset
El dataset fue proporcionado directamente por la fábrica de ensamblaje, con el consentimiento y la aprobación de la gerencia y los representantes sindicales. Los datos fueron anonimizados para proteger la privacidad de los trabajadores.
Preguntas de Investigación

------------

¿Cuáles son las características más influyentes para predecir el riesgo de lesiones en un puesto específico?

Propósito: Identificar los factores clave que contribuyen al riesgo de lesiones para tomar medidas preventivas.


¿Cuál es el intervalo de tiempo óptimo para la rotación de puestos con el fin de minimizar el riesgo de lesiones?

Propósito: Determinar la frecuencia adecuada de rotación para mantener la seguridad de los trabajadores.


¿Qué nivel de precisión y rendimiento se puede lograr con el modelo de aprendizaje automático propuesto?

Propósito: Evaluar la efectividad del modelo para predecir la necesidad de rotación y prevenir lesiones.


¿Cómo se puede integrar el modelo de predicción en los procesos existentes de las fábricas de ensamblaje?

Propósito: Desarrollar una estrategia para implementar el modelo de manera práctica en el entorno de fabricación.

------------


**Etapas del Proyecto**
1. Metodología Extracción y Preparación de Datos

Extracción de Datos: Los datos se obtuvieron de la fábrica de ensamblaje en formato CSV.
Preprocesamiento: Incluye la limpieza de datos, manejo de valores faltantes y codificación de variables categóricas.

2. Análisis Exploratorio de Datos (EDA)

Visualización de Datos: Utilización de gráficos para entender la distribución de las variables y las relaciones entre ellas.
Estadísticas Descriptivas: Cálculo de medidas de tendencia central, dispersión y correlación.

3. Modelado Predictivo

Selección de Modelos: Elección de algoritmos de aprendizaje automático adecuados, como árboles de decisión, random forests o máquinas de vectores de soporte (SVM).
Entrenamiento y Evaluación de Modelos: División de los datos en conjuntos de entrenamiento y prueba, entrenamiento de los modelos y evaluación de su rendimiento utilizando métricas apropiadas.

4. Optimización y Validación

Ajuste de Hiperparámetros: Optimización de los hiperparámetros de los modelos para mejorar su desempeño.
Validación Cruzada: Uso de técnicas de validación cruzada para asegurar la generalización de los modelos.

5. Interpretación y Comunicación de Resultados

Interpretación de Resultados: Análisis de los resultados obtenidos y extracción de conclusiones relevantes.
Visualización de Resultados: Presentación de los resultados a través de gráficos y tablas claras y comprensibles.
Informe Final: Elaboración de un informe detallado que resuma los hallazgos, las limitaciones y las recomendaciones del proyecto.

**Resultados Esperados**

Modelo Predictivo: Desarrollo de un modelo de aprendizaje automático capaz de predecir con precisión cuándo un trabajador debe rotar de un puesto específico para prevenir lesiones.
Insights Accionables: Identificación de los factores clave que influyen en el riesgo de lesiones y recomendaciones para mejorar la seguridad de los trabajadores.

------------

Project Organization
------------

├── LICENSE
├── Makefile           <- Makefile con comandos como `make data` o `make train`
├── README.md          <- El README principal para los desarrolladores que utilizan este proyecto.
├── data
│   ├── external       <- Datos de terceras fuentes.
│   ├── interim        <- Datos intermedios que han sido transformados.
│   ├── processed      <- Los conjuntos de datos finales y canónicos para el modelado.
│   └── raw            <- Los datos originales e inmutables.
│
├── docs               <- Un proyecto Sphinx por defecto; consulta sphinx-doc.org para más detalles
│
├── models             <- Modelos entrenados y serializados, predicciones de modelos o resúmenes de modelos
│
├── notebooks          <- Notebooks de Jupyter. La convención de nombres es un número (para el ordenamiento),
│                         las iniciales del creador y una descripción corta y delimitada por `-`, p. ej.
│                         `1.0-jqp-initial-data-exploration`.
│
├── references         <- Diccionarios de datos, manuales y todos los demás materiales explicativos.
│
├── reports            <- Análisis generados como HTML, PDF, LaTeX, etc.
│   └── figures        <- Gráficos y figuras generados para ser utilizados en los informes.
│
├── requirements.txt   <- El archivo de requisitos para reproducir el entorno de análisis, p. ej.
│                         generado con `pip freeze > requirements.txt`
│
├── setup.py           <- Hace que el proyecto sea instalable (pip install -e .) para que src pueda ser importado
├── src                <- Código fuente para su uso en este proyecto.
│   ├── __init__.py    <- Hace que src sea un módulo de Python
│   │
│   ├── data           <- Scripts para descargar o generar datos
│   │   └── make_dataset.py
│   │
│   ├── features       <- Scripts para convertir los datos sin procesar en características para el modelado
│   │   └── build_features.py
│   │
│   ├── models         <- Scripts para entrenar modelos y luego usar los modelos entrenados para hacer
│   │   │                 predicciones
│   │   ├── predict_model.py
│   │   └── train_model.py
│   │
│   └── visualization  <- Scripts para crear visualizaciones exploratorias y orientadas a resultados
│       └── visualize.py
│
└── tox.ini            <- Archivo tox con configuraciones para ejecutar tox; consulta tox.readthedocs.io


--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
