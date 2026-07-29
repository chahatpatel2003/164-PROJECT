# Wine Classification and Quality Prediction

A machine-learning project that analyzes wine chemistry data for cultivar classification and red/white wine quality prediction.

## Project Overview

This academic project uses two established datasets:

- Wine Recognition: 178 samples with 13 chemical features from three Italian wine cultivars
- Wine Quality: 1,599 red-wine samples and 4,898 white-wine samples

The workflow covers data preparation, exploratory analysis, model development, hyperparameter tuning, cross-validation, and performance evaluation.

## Objectives

- Classify wine cultivars using chemical measurements
- Predict wine quality scores for red and white wines
- Compare multiple machine-learning models
- Tune model parameters systematically
- Evaluate results using classification and regression metrics

## Methods

### Data Preparation

- Missing-value inspection and preprocessing
- Feature standardization
- 80/20 train-test split
- Five-fold cross-validation
- Processed dataset generation

### Classification

The Wine Recognition analysis includes:

- Logistic Regression
- k-Nearest Neighbors
- Model comparison
- Confusion matrices
- Classification reports
- ROC and AUC analysis

### Regression

The Wine Quality analysis includes:

- Linear Regression
- Multi-Layer Perceptron regression
- Hyperparameter search
- Mean squared error
- R-squared evaluation
- Model comparison

## Repository Structure

```text
.
├── archive/
│   └── code-and-docs.zip
├── data/
│   ├── processed/
│   │   ├── red-wine-processed.csv
│   │   ├── white-wine-processed.csv
│   │   └── wine-recognition-processed.csv
│   └── raw/
│       ├── wine.data
│       ├── wine.names
│       ├── wine.zip
│       ├── wine-quality.zip
│       ├── winequality-red.csv
│       ├── winequality-white.csv
│       └── winequality.names
├── docs/
│   ├── executive_summary.docx
│   ├── executive_summary.pdf
│   ├── index.txt
│   └── project_introduction.docx
├── notebooks/
│   └── wine_classification_and_quality_analysis.ipynb
├── .gitignore
├── README.md
└── requirements.txt
```

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Run Locally

```bash
python3 -m pip install -r requirements.txt
jupyter notebook
```

Open `notebooks/wine_classification_and_quality_analysis.ipynb`.

## Academic Context

Developed as part of artificial intelligence coursework at California State University, Fresno.
