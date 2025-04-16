# Imbalaced Learn Tests

This project explores techniques for handling imbalanced datasets in the context of credit card fraud detection. The experiments were conducted using various resampling methods and machine learning models to evaluate their performance on detecting fraudulent transactions.

## Overview

The primary goal of this project was to test and compare different techniques provided by the `imbalanced-learn` library. The results and insights from this project were shared in a Medium post:

[Dominando Dados Desbalanceados: Qual Técnica de Balanceamento Vence na Detecção de Fraudes?](https://medium.com/@samuelpndx/dominando-dados-desbalanceados-qual-técnica-de-balanceamento-vence-na-detecção-de-fraudes-57470fd3aae4)

## Key Features

- **Resampling Techniques**: Tested methods like SMOTE, ADASYN, SMOTETomek, and SMOTEENN.
- **Machine Learning Models**: Evaluated models such as Logistic Regression, Random Forest, XGBoost, and LightGBM.
- **Metrics**: Used metrics like F1-Score, Recall, AUC-ROC, and AUC-PR to assess performance.
- **Visualization**: Generated plots to compare the effectiveness of different techniques.

## Repository Structure

- **notebooks/**: Contains Jupyter notebooks for data preprocessing, model training, and hyperparameter tuning.
- **results/**: Includes CSV files summarizing the performance of various models and techniques.

## Dependencies

- Python 3.12+
- Libraries: `imbalanced-learn`, `scikit-learn`, `xgboost`, `lightgbm`, `matplotlib`, `seaborn`, `pandas`, `numpy`


## Results

The results of the experiments are summarized in the `results/` directory. Key findings and visualizations are detailed in the Medium post linked above.

## License

This project is for educational purposes and is not licensed for commercial use.

---
Happy experimenting!
