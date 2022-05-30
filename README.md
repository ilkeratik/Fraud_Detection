# Fraud_Detection


*Preprocessing notebook has the details of preprocessing while in the model building notebook preprocessing steps applied without verbose.*

## Preprocessing:
- Scaling amount and time features
- Random Under-Sampling
- Anomaly detection & Removing outliers
- Dimensionality Reduction and Clustering

## Models:
- Logistic Regression
- Support Vector Machine
- Decision Tree + SMOTE
- Decision Tree with undersampled data
- AdaBoost
- GradientBoosting
- NN-Perceptron

## Results:
| **Model**              | **Accuracy** | **Precision** | **Recall** | **F1-Score** |
| ---------------------- | ------------ | ------------- | ---------- | ------------ |
| Logistic Regression    | 0.926        | 1.0           | 0.847      | 1.0          |
| Decision Tree          | 0.873        | 0.905         | 0.826      | 0.904        |
| Support Vector Machine | 0.952        | 0.989         | 0.919      | 0.989        |
| AdaBoost               | 0.915        | 0.931         | 0.890      | 0.931        |
| GradientBoosting       | 0.915        | 0.951         | 0.868      | 0.951        |
| NN-Perceptron          | 0.957        | 0.936         | 0.979      | 0.957        |


*Model building without preprocessing notebook is there for you to see and don't use it.*
