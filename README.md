**Institución:** Politécnico Malvinas Argentinas.  https://politecnico.tdf.gob.ar/

**Carrera:** Tecnicatura Superior en Ciencia de Datos e Inteligencia Artificial.

*Asignatura:* Aprendizaje Automático 

*Año:* 2024

**Profesor:** Martin Mirabete

**cookiecutter.project:** Predicción de Rotación de Puestos para la Prevención de Lesiones en Fábricas de Ensamblaje

**Autor:**  Lucas Alejandro Riveros
==============================

**{{cookiecutter.description}}**

El objetivo principal de este proyecto es aplicar técnicas de Aprendizaje Automático para predecir cuándo un trabajador de una fábrica de ensamblaje debe rotar de un puesto específico para prevenir lesiones. Utilizando datos históricos de lesiones, información demográfica de los trabajadores y detalles de los puestos de trabajo, se desarrollará un modelo predictivo que ayude a identificar el momento óptimo para la rotación, considerando factores como la duración en el puesto, la repetitividad de las tareas y la postura requerida. Este análisis busca proporcionar insights valiosos para mejorar la seguridad y el bienestar de los trabajadores en el entorno de fabricación.

*Dataset*: El dataset fue proporcionado directamente por la fábrica de ensamblaje, con el consentimiento y la aprobación de la gerencia y los representantes sindicales. Los datos fueron anonimizados para proteger la privacidad de los trabajadores.

[-] Preguntas de Investigación del Proyecto:

1-¿Cuáles son las características más influyentes para predecir el riesgo de lesiones en un puesto específico?

Propósito: Identificar los factores clave que contribuyen al riesgo de lesiones para tomar medidas preventivas.

2-¿Cuál es el intervalo de tiempo óptimo para la rotación de puestos con el fin de minimizar el riesgo de lesiones?

Propósito: Determinar la frecuencia adecuada de rotación para mantener la seguridad de los trabajadores.

3-¿Qué nivel de precisión y rendimiento se puede lograr con el modelo de aprendizaje automático propuesto?

Propósito: Evaluar la efectividad del modelo para predecir la necesidad de rotación y prevenir lesiones.

4-¿Cómo se puede integrar el modelo de predicción en los procesos existentes de las fábricas de ensamblaje?

Propósito: Desarrollar una estrategia para implementar el modelo de manera práctica en el entorno de fabricación.

Project Organization
------------

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── docs               <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data           <- Scripts to download or generate data
    │   │   └── make_dataset.py
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.py
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization  <- Scripts to create exploratory and results oriented visualizations
    │       └── visualize.py
    │
    └── tox.ini            <- tox file with settings for running tox; see tox.readthedocs.io


--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
