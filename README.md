# Prakhar_Tiwari_5._Classify_Customer_Churn
# Customer Churn Prediction and Segmentation - Telecom Industry

## Project Overview

This project addresses two key objectives for a telecom company:

1. **Customer Churn Classification**: Predict which customers are likely to discontinue their services based on their usage patterns, contract types, and billing information.
2. **Customer Segmentation (Clustering)**: Group customers into distinct segments based on behavioral patterns for better understanding and targeted decision-making.

These tasks are designed to support customer retention strategies and enhance service personalization.

---

## Dataset

The dataset used (`5. Classify Customer Churn.csv`) contains various customer-related information including:

- Demographics
- Service subscriptions (internet, phone, streaming)
- Payment methods
- Billing amounts
- Churn status (Yes/No)

---

## Key Components

### Classification
- **Model Used**: Random Forest Classifier
- **Performance Metrics**:
  - Accuracy
  - Precision
  - Recall
- **Visualization**: Confusion matrix heatmap for classification evaluation

### Clustering
- **Algorithm Used**: KMeans
- **Data Processing**:
  - Feature scaling with StandardScaler
  - Dimensionality reduction using PCA for visualization
- **Output**: 2D scatter plot showing clustered customer segments

---

## Results

- Successfully built and evaluated a classification model to predict churn.
- Visualized performance using a confusion matrix and calculated evaluation metrics.
- Implemented KMeans clustering to segment customers, revealing behavioral patterns.

---

## Requirements

- Python 3.x
- Required libraries:
  - pandas
  - numpy
  - scikit-learn
  - matplotlib
  - seaborn

To install dependencies:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
