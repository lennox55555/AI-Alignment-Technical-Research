# Interpretable Machine Learning Models Repository

Welcome to the **Interpretable Machine Learning** folder. This section focuses on comparing interpretable machine learning models, with a specific interest in understanding how these models can be used in practical settings, especially for tasks such as predicting customer churn. The goal is to maintain a balance between model performance and interpretability, ensuring that the models are not only accurate but also explainable.

## Overview

This repository contains:

- **Jupyter Notebook**: A comprehensive analysis comparing interpretable models like **Logistic Regression** and **Generalized Additive Models (GAM)**. The goal was to evaluate their performance on a binary classification task (churn prediction) and assess how well they balance interpretability and accuracy.
  
- **ROC Curve Comparison**: Visual representation of the model performance, plotting the ROC curves for both Logistic Regression and GAM to evaluate their discriminative power.

- **Model Metrics**: Analysis of key metrics such as accuracy, precision, recall, f1-score, and ROC AUC to help decide which model performs better while remaining interpretable.

## Purpose of This Repository

I’m particularly interested in exploring **interpretable machine learning models** that can be applied in real-world tasks where transparency is critical. This repository serves as a workspace for my research and experiments on comparing these models.


## Structure

1. **Notebook**:
   - [InterpretableML.ipynb](./InterpretableML.ipynb): The Jupyter notebook contains all the code, data processing steps, model training, evaluation, and visualizations comparing the interpretable models.

2. **Model Metrics**:
   - Logistic Regression: Accuracy, Confusion Matrix, Precision, Recall, and ROC AUC score of **0.85**.
   - Generalized Additive Model (GAM): Accuracy, Confusion Matrix, Precision, Recall, and ROC AUC score of **0.82**.

3. **ROC Curves**:
   - A side-by-side comparison of the ROC curves for both Logistic Regression and GAM, showing the performance differences visually.

## Insights from the Analysis

- **Logistic Regression**: Simpler, more interpretable, and slightly better at distinguishing between churners and non-churners, as indicated by its higher ROC AUC score (0.85 vs 0.82).
  
- **GAM**: Provides more flexibility to model non-linear relationships but comes at the cost of slightly lower performance and complexity in interpretation.

## Conclusion

For tasks that prioritize **transparency and ease of interpretation**, **Logistic Regression** may be the model of choice due to its balance between interpretability and strong performance. However, **GAM** offers an alternative when flexibility in modeling relationships is required, even though it might sacrifice some performance and simplicity.



