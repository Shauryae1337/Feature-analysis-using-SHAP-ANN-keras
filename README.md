# Phishing Detection using Keras with SHAP Analysis

## Introduction

Phishing is a prevalent online threat, and this project aims to build and analyze a machine learning model for phishing detection. The primary tool used is the Artificial Neural Network (ANN) implemented using the Keras library for classification, along with SHAP for interpretability.

## ANN Model

The ANN model is trained on a dataset containing features related to URLs, including characteristics like length, presence of certain symbols, and domain information. The model is evaluated on a testing set, and its performance metrics are analyzed.

## SHAP Analysis

SHAP values are used to interpret the predictions of the ANN model. The SHAP summary plot is generated to visualize the impact of each feature on the model's output. Additionally, the mean absolute SHAP values are extracted and presented in tabular format.

## Files and Structure

- `Notebook Shap ann.ipynb`: Jupyter Notebook containing the code for data preprocessing, model training, and SHAP analysis.

- `dataset1.csv`: The dataset used for training and evaluation.

- `mean shap value pred.csv`: Mean SHAP Values for each feature.

- `Images`: Graphs and Tables

- Python 3.x Jupyter Notebook Libraries: `scikit-learn`, `shap`, `pandas`, `matplotlib`, `keras`

Install the required libraries using:

```bash
pip install scikit-learn shap pandas matplotlib keras
```

# Acknowledgments

## The dataset used in this project is sourced from "Hannousse, Abdelhakim; Yahiouche, Salima (2021), “Web page phishing detection”, Mendeley Data, V3, doi: 10.17632/c2gw7fy2j4.3"

## Special thanks to the open-source contributors of scikit-learn, SHAP, and Keras for their valuable tools.

## Special thanks to Prof. Raviraj Vaghela for his guidance and support.

