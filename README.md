# Numerical Feature Classification: A Feature Engineering Case Study

A machine learning project focused on classifying an unlabeled numerical dataset through exploratory analysis, feature engineering, and model development.

## Overview

This repository contains a data science workflow applied to a dataset composed exclusively of numerical features and a target classification label. With no contextual metadata, the project emphasizes understanding patterns purely through data exploration and engineering.

## Objectives

- Explore the structure and distribution of numerical features through visualizations and statistical summaries.
- Engineer and select features to improve classification performance.
- Train and evaluate machine learning models using tools such as `scikit-learn` and `XGBoost`.
- Document findings and modeling decisions to provide a clear, reproducible workflow.

## Technologies Used

- Python 3.11.11
- pandas, numpy, matplotlib, seaborn, scikit-learn, XGBoost
- Jupyter Notebook

## Techniques Used

- Data Exploration: Descriptive statistics, visualizations (box plots, correlation heatmaps, scatter plots)
- Feature Engineering: Principal Component Analysis (PCA), t-SNE
- Balancing unbalanced datasets
- Preliminary binary classification
- Model Selection: Multi-layer Perceptron, XGBoost
- Evaluation Metrics: Precision, Recall, F1 Score, Confusion Matrix

## Folder Structure

```

├── data (ignored by .gitignore due to size)
│   ├── train_data.npy
│   ├── eval_data.npy
│   ├── train_labels.npy
│   └── eval_labels.npy
├── res
│   ├── output1.png
│   ├── output2.png
│   ├── output3.png
│   ├── output4.png
│   ├── output5.png
│   ├── output6.png
│   ├── output7.png
│   └── output8.png
├── report.ipynb
├── README.md
└── .gitignore

```