# SCML: Superconductor Classification with Machine Learning

This repository provides a machine learning pipeline for classifying and predicting the critical temperature (\(T_c\)) of superconducting materials using a dataset of experimentally verified superconductors.

## 🧪 Description

This project supports research into data-driven discovery and analysis of superconducting materials. It applies classical machine learning models to predict whether a given material is a high-\(T_c\) or low-\(T_c\) superconductor, using features derived from elemental and structural properties.

The code is designed for researchers interested in applying machine learning to materials science, especially for accelerating discovery in superconductivity.

## 🔧 Techniques Used

- **Support Vector Classification (SVC):** Used to classify materials as high-\(T_c\) or low-\(T_c\).
- **Principal Component Analysis (PCA):** For dimensionality reduction and visualization of material feature space.
- **Random Forests and Decision Trees:** For baseline comparison and feature importance analysis.
- **Custom Feature Engineering:** Elemental statistics (e.g., average atomic number, electronegativity, etc.) are computed for compound-level prediction.

## 📦 Libraries and Tools

- [scikit-learn](https://scikit-learn.org/)
- [Pandas](https://pandas.pydata.org/)
- [NumPy](https://numpy.org/)
- [Matplotlib](https://matplotlib.org/)
- [Jupyter Notebook](https://jupyter.org/)

## 📁 Project Structure

```plaintext
.
├── Data/
├── Figures/
├── SCML_Classification.ipynb
├── SCML_Visualization.ipynb
└── README.md
```

### Notable Directories

- `Data/`: Dataset of superconducting materials, including chemical composition and critical temperature.
- `Figures/`: Visual output from classification models, including confusion matrices and decision boundaries.

## 🔬 Context

This repo is part of an ongoing effort to explore structure–property relationships in superconductors using data-centric methods. It complements symbolic and physics-informed ML approaches under development for discovering interpretable predictors of superconducting behavior.
