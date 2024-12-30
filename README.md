# ECG Signal Classification

This project focuses on the classification of Electrocardiogram (ECG) signals using machine learning techniques, with an emphasis on comparing the performance of various classifiers such as Random Forest and Neural Networks.

## Overview

Electrocardiograms (ECGs) provide crucial information for diagnosing cardiac conditions. Accurate classification of ECG signals into categories such as normal or abnormal heartbeats is essential for healthcare applications. This project uses machine learning techniques to classify ECG signals effectively.

## Dataset

The dataset used in this project is derived from the following sources:
- **MIT-BIH Arrhythmia Dataset**
- **PTB Diagnostic ECG Database**

It is available on Kaggle: [Heartbeat Dataset](https://www.kaggle.com/datasets/shayanfazeli/heartbeat).

The dataset includes heartbeat signals labeled into classes, making it suitable for supervised learning tasks.

## Classifiers Compared

The project evaluates the performance of various machine learning classifiers:
- **Support Vector Machine (SVM)**
- **Naive Bayes**
- **Logistic Regression**
- **Decision Tree**
- **Random Forest**
- **Neural Networks**

### Key Findings
- Random Forest demonstrated superior performance compared to other classifiers.
- Neural Networks also performed well, highlighting their suitability for signal processing tasks.

## Project Structure

- **Data**: Contains the ECG dataset and any preprocessed data files.
- **Notebooks**: Jupyter notebooks showcasing data exploration, preprocessing, model training, and evaluation.
- **Results**: Contains outputs such as model metrics, confusion matrices, and visualizations.

## Methodology

1. **Data Preprocessing**:
   - Load and clean the ECG dataset.
   - Normalize signal values to ensure consistency.
   - Split data into training, validation, and testing sets.

2. **Feature Extraction**:
   - Extract meaningful features from ECG signals using signal processing techniques.
   - Use statistical measures and domain-specific knowledge for feature engineering.

3. **Model Training**:
   - Train classifiers using extracted features.
   - Use cross-validation to optimize hyperparameters.

4. **Evaluation**:
   - Evaluate models using metrics like accuracy, precision, recall, F1-score, and ROC-AUC.
   - Compare the performance of different classifiers.


