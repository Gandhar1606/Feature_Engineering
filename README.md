# Feature_Engineering
Comprehensive data preprocessing project demonstrating core techniques (scaling, encoding, selection, PCA) on the MNIST (Image) and Iris (Tabular) datasets.

# Data Preprocessing & Feature Engineering Project

## Project Overview 📊

This repository contains a comprehensive demonstration of essential data preprocessing and feature engineering techniques applied to two distinct machine learning datasets: a **Tabular Classification** task and an **Image Classification** task.

The project follows a rigorous assignment structure, ensuring all steps—from initial loading to final feature selection—are explicitly documented and executed using Python (Scikit-learn, Pandas, NumPy, Keras).

## Datasets Used

| Dataset | Type | Problem | Key Transformations Demonstrated |
| :--- | :--- | :--- | :--- |
| **Iris Flower Dataset** | Tabular | Multi-Class Classification | Imputation (Demo), Standardization, SelectKBest, PCA |
| **MNIST Digits** | Image | Multi-Class Classification | Normalization, Flattening, One-Hot Encoding, Variance Threshold |

## Preprocessing Tasks Performed

The following core transformations were applied across the two datasets to prepare the data for machine learning model training:

### 1. Data Cleaning & Preparation
* **Missing Value Handling:** Demonstrated Mean Imputation (on tabular data).
* **Data Exploration:** Checked data types, shapes, and pixel ranges.

### 2. Feature Transformation
* **Feature Scaling:** Applied **Normalization** (MNIST) and **Standardization** (Iris).
* **Categorical Encoding:** Applied **One-Hot Encoding** (MNIST labels) and **Label Encoding** (Iris target).

### 3. Dimensionality Management
* **Feature Extraction:** Applied **Flattening** (MNIST) and **Principal Component Analysis (PCA)** (Iris).
* **Feature Selection:** Applied **Variance Threshold** (MNIST) and **SelectKBest** (Iris) to optimize input dimensionality.

## Requirements

To run the notebooks in this repository, you will need the following key libraries (easily accessible via Google Colab or a standard Python environment):

* `numpy`
* `pandas`
* `scikit-learn`
* `tensorflow` (for MNIST dataset loading)
* `matplotlib`
