# Violence Reduction – Advanced Machine Learning Project
<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/67fec910-ef02-4237-a9fe-456833f35603" />

This project applies supervised and unsupervised machine learning techniques to analyze and predict violent incidents in the city of Chicago, with a specific focus on distinguishing fatal from non-fatal events.

The work was completed as part of the Machine Learning and Advanced Machine Learning courses.

---

## Project Objectives
- Predict whether a violent incident will result in a fatal outcome using classification models.
- Explore hidden spatial and temporal patterns in violent incidents using clustering.
- Address real-world challenges such as class imbalance and noisy data.
- Compare multiple machine learning algorithms and evaluate their performance.

---

## Dataset
The dataset used in this project is:

**Violence Reduction – Victims of Homicides and Non-Fatal Shootings**

- Each row represents a single violent incident.
- Features include demographic, spatial, and temporal attributes.
- The target variable (`y_fatal`) indicates whether the incident resulted in a homicide.

The data is provided as a CSV file and can be found in the `data/` directory.

---

## Methods and Models

### Supervised Learning (Classification)
The following models were evaluated:
- Random Forest
- XGBoost
- Gradient Boosting
- AdaBoost
- Multilayer Perceptron (MLP)

Model selection was based primarily on **F1-score** and **ROC-AUC**, due to class imbalance.
Hyperparameter tuning and decision-threshold optimization were applied to the top-performing models.

### Unsupervised Learning (Clustering)
- K-Means (K-Means++) clustering was applied to identify groups of similar incidents.
- PCA was used for dimensionality reduction and visualization.
- Clustering focused on spatial and temporal features to reveal interpretable behavioral patterns.

---

## Evaluation Metrics
Models were evaluated using:
- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC
- Confusion Matrix

---
