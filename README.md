CUSTOMER-TRANSACTION-PREDICTION
==============================

El banco Santander busca entender mejor a sus clientes, de forma tal que pueda ofrecerles los productos que les permitan alcanzar sus metas financieras. Es por ello que con este dataset se busca predecir cuáles son los clientes que van a realizar una determinada transacción en el futuro, independientemente del monto de dicha transacción.

Organización del Proyecto
------------

    ├── LICENSE
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── processed      <- Dataset utilizado para el proyecto.
    │   └── raw            <- Folds utilizados para la entrenamiento y predicción de modelos
    │
    │
    ├── models             <- Todos los mejos modelos probados por cada uno de los integrantes
    │
    ├── notebooks          <- Notebooks de todos los participantes del equipo de trabajo. 
    │
    ├── reports            <- Presentación de proyecto y conclusiones
    │   └── figures        <- Figuras importanes del proyecto. 
    │
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
--------
