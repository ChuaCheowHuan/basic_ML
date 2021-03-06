# What's in this repository?

This repository contains simple usage examples for basic machine learning
libraries. These notebooks are tested in Colab.

`XGB_classification_titanic.ipynb`
- A supervised ML classification example using XGBoost (GPU),
sklearn (pipeline & auto hyperparameter tuning) & SMOTE on the
[titanic](https://www.kaggle.com/c/titanic) dataset.
(Custom feature extraction/engineering & SMOTE excluded from pipeline.)

`imblearn_XGB_titanic.ipynb`
- A supervised ML classification example using XGBoost (GPU) &
sklearn (auto-hyperparameter tuning & custom transformer) with imblearn
pipeline & SMOTE on the
[titanic](https://www.kaggle.com/c/titanic) dataset.
(**Full pipeline**)

`XGB_regression_kc_house.ipynb`
- A supervised ML regression example using XGBoost (GPU) &
sklearn (pipeline & auto hyperparameter tuning) on the
[King county house sales](https://www.kaggle.com/harlfoxem/housesalesprediction) dataset.

`cust_trans_XGB_kc_house.ipynb`
- A supervised ML regression example using XGBoost (GPU) &
sklearn (pipeline, custom transform & auto hyperparameter tuning) on the
[King county house sales](https://www.kaggle.com/harlfoxem/housesalesprediction) dataset.
(**Full pipeline**)

`clustering_iris.ipynb`
- An unsupervised ML clustering example using sklearn on the iris dataset.

`CNN_classification_MNIST.ipynb`
- A supervised ML classification example using CNN from Keras &
Kerastuner (auto hyperparameter tuning) on the MNIST dataset.
