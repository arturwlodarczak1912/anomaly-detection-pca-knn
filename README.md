# Dimensionality Reduction, Anomaly Detection, and k-NN

## Objective
Explore unsupervised analysis techniques (PCA, Isolation Forest) and proximity-based classification (k-NN) across three distinct datasets.

## Content

### 1. PCA — Depression, Anxiety, and Stress Scales
- Dataset: [Depression Anxiety Stress Scales](https://www.kaggle.com/datasets/lucasgreenwell/depression-anxiety-stress-scales-responses)
- Dimensionality reduction using **PCA** (Principal Component Analysis)
- Interpretation of principal components and 2D scatter plot visualization

### 2. Anomaly Detection — Air Quality Data (ESA)
- Data fetched directly from the public API of the Anti-Smog Educational Network (dane.gov.pl)
- Application of the **Isolation Forest** algorithm to identify anomalous pollution readings
- Visualizations comparing variables (humidity, pressure, temperature, PM10, PM2.5) by anomaly status

### 3. Classification with k-NN and Logistic Regression — Autism Screening
- Dataset: [Autism Screening](https://www.kaggle.com/datasets/faizunnabi/autism-screening)
- Data standardization (`StandardScaler`)
- Comparison between Decision Tree, k-NN, and Logistic Regression on an imbalanced classification problem

## Technologies
`Python` `scikit-learn` `pandas` `seaborn` `matplotlib` `requests`

## How to Run
```bash
pip install scikit-learn pandas seaborn matplotlib requests kaggle
jupyter notebook "Analiza PCA - Depression Anxiety Stress Scales.ipynb"
jupyter notebook "Analiza anomalii - dane smogowe.ipynb"
jupyter notebook "autyzm - metoda k-NN.ipynb"