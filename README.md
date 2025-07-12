# A Comparative Analysis of Machine Learning Models for Occupation Classification

This repository contains the source code and report for a university assignment focused on implementing and comparing three machine learning classification models.

## Project Overview

The goal of this project is to predict an individual's occupation based on demographic data from the **UCI Adult (Census) Dataset**. Three different classification algorithms were implemented and evaluated:

1.  **Support Vector Machine (SVM)** with Linear, RBF, and Polynomial kernels.
2.  **Gaussian Naive Bayes (GNB)**
3.  **Deep Neural Network (DNN)** using TensorFlow/Keras.

The project covers the entire machine learning workflow, including data preprocessing, model training, evaluation, and a comparative analysis of the results.

---

## Key Findings

- The **Support Vector Machine (SVM) with an RBF kernel** was the top-performing model, achieving the highest accuracy and F1-score.
- The **Deep Neural Network (DNN)**, despite its complexity, suffered from severe overfitting and performed worse than the SVM.
- The **Gaussian Naive Bayes** model failed completely due to its core assumptions being a poor match for the dataset's characteristics.

This project highlights the importance of choosing a model that is appropriate for the data's structure and complexity, as a more complex model does not always guarantee better performance.

---

## Repository Structure

- `classification-model-comparison.ipynb`: The main Jupyter Notebook containing all the Python code for data preprocessing, model training, and evaluation.
- `adult.csv`: The dataset used for this project.
