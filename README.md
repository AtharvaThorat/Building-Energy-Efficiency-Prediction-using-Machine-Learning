
# Building Energy Efficiency Prediction using Machine Learning

This project develops machine learning models to predict **Heating Load (HL)** and **Cooling Load (CL)** of buildings based on architectural and environmental features. The goal is to enable data-driven design decisions that reduce HVAC energy consumption, lower operational costs, and support sustainable construction practices.

---

## Project Overview

Energy efficiency in buildings is a critical global challenge. HVAC systems account for a significant portion of building energy usage, and accurate early-stage predictions of heating and cooling requirements can significantly improve design optimization.

This project builds regression models that learn the relationship between building characteristics (such as surface area, wall area, glazing area, height, etc.) and energy load demands.

The implementation follows a structured end-to-end machine learning workflow including preprocessing, model training, evaluation, and performance comparison.

---

## Problem Statement

Given a set of building design parameters:

* Relative Compactness
* Surface Area
* Wall Area
* Roof Area
* Overall Height
* Orientation
* Glazing Area
* Glazing Area Distribution

Predict:

* Heating Load (HL)
* Cooling Load (CL)

This is a supervised regression problem with continuous outputs.

---

## Machine Learning Approach

The project implements and compares multiple regression models:

* Decision Tree Regressor
* Random Forest Regressor
* Gradient Boosting Regressor
* Support Vector Regressor

The workflow includes:

1. Data loading and inspection
2. Feature scaling using StandardScaler
3. Train-test split (67% training, 33% testing)
4. Model training
5. Performance evaluation using R² and RMSE
6. Model comparison and interpretation

---

## Key Findings

* Ensemble methods such as **Gradient Boosting** and **Random Forest** provide the strongest predictive performance.
* Decision Trees achieve near-perfect training performance but can overfit without proper regularization.
* Gradient Boosting demonstrates the best balance between accuracy and generalization.
* Building geometry and glazing characteristics significantly influence heating and cooling demands.

The results show that structured tabular regression models can achieve very high predictive accuracy on this dataset.

---

## Evaluation Metrics

The following metrics are used to evaluate performance:

* R² Score (variance explained by the model)
* Root Mean Squared Error (RMSE)
* Cross-validation for robustness

These metrics ensure the models are both accurate and stable.

---

## Technology Stack

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Repository Structure

The repository includes:

* Dataset files
* Jupyter notebook with full ML pipeline
* Model evaluation results
* Documentation

---

## How to Run

1. Clone the repository
2. Install dependencies listed in requirements.txt
3. Open the notebook in Jupyter
4. Run all cells to reproduce preprocessing, training, and evaluation

---

## Skills Demonstrated

This project highlights competencies relevant to Machine Learning, AI, and Software Engineering roles:

* Supervised regression modeling
* Ensemble learning techniques
* Feature scaling and preprocessing
* Model evaluation and comparison
* Data-driven interpretation of results
* Structured ML pipeline design

---

## Why This Project Matters

This project demonstrates the ability to:

* Translate a real-world sustainability problem into a machine learning task
* Apply ensemble learning methods effectively
* Evaluate models rigorously
* Interpret model outputs for practical insights

It reflects practical experience in applying machine learning techniques to structured tabular datasets in an energy optimization context.

---

## Future Improvements

Potential extensions include:

* Incorporating climate or occupancy data for dynamic load prediction
* Deploying the trained model via a web API
* Adding SHAP-based model explainability
* Comparing performance with neural network regressors

---

## Author

Atharva Thorat
Master’s in Computer Science – University of Southern California
Interested in Machine Learning, AI Systems, and Scalable Engineering Solutions

