# CART Regression – Yacht Hydrodynamics

**Machine Learning Assignment | Python | Regression**

## Project Overview

This project implements a Classification and Regression Tree (CART) Regression model to predict the residuary resistance of sailing yachts.

The project uses the Yacht Hydrodynamics dataset from the UCI Machine Learning Repository. The model learns from six numerical yacht characteristics and predicts a continuous resistance value.

The objective is to understand how CART performs binary splitting, minimizes regression impurity and generates interpretable predictions.

## Problem Statement

Predict the residuary resistance of a sailing yacht using its hull geometry and speed-related measurements.

## Dataset Information

- Dataset: Yacht Hydrodynamics
- Source: UCI Machine Learning Repository
- Total observations: 308
- Input features: 6
- Target variable: Residuary resistance per unit weight of displacement
- Problem type: Supervised Regression

### Input Features

1. Longitudinal position of the center of buoyancy
2. Prismatic coefficient
3. Length-displacement ratio
4. Beam-draught ratio
5. Length-beam ratio
6. Froude number

### Target Variable

Residuary resistance per unit weight of displacement.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- UCI Machine Learning Repository
- Jupyter Notebook

## Machine Learning Approach

The CART Regression workflow includes:

1. Dataset loading and exploration
2. Data quality checking
3. Feature and target selection
4. 80:20 train-test split
5. Regression impurity calculation using MSE
6. Tree depth comparison using cross-validation
7. CART model training
8. Model prediction and evaluation
9. Decision tree visualization
10. Feature importance analysis
11. Prediction on a new observation

## Model Evaluation

The model is evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

Actual evaluation values are available in the Jupyter Notebook after execution.

## Project Structure

```text
Arja-Manish_05nov_CART-Regression-Yacht-Hydrodynamics/
│
├── data/
│   └── yacht_hydrodynamics.csv
│
├── images/
│   ├── cart_decision_tree.png
│   ├── actual_vs_predicted.png
│   └── feature_importance.png
│
├── notebooks/
│   └── Arja_Manish_CART_Regression.ipynb
│
├── README.md
├── requirements.txt
├── DATASET_CITATION.md
└── .gitignore
```

## Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/Arjamanish/Arja-Manish_05nov_CART-Regression-Yacht-Hydrodynamics.git
```

### 2. Navigate to the project

```bash
cd Arja-Manish_05nov_CART-Regression-Yacht-Hydrodynamics
```

### 3. Create a virtual environment

```bash
python -m venv .venv
```

### 4. Activate the environment (Windows)

```bash
.venv\Scripts\activate
```

### 5. Install dependencies

```bash
pip install -r requirements.txt
```

### 6. Run the notebook

Open the following file using Jupyter Notebook or VS Code:

`notebooks/Arja_Manish_CART_Regression.ipynb`

Execute the cells sequentially.

## Visualizations

### CART Decision Tree

![CART Decision Tree](images/cart_decision_tree.png)

### Actual vs Predicted

![Actual vs Predicted](images/actual_vs_predicted.png)

### Feature Importance

![Feature Importance](images/feature_importance.png)

## Key Learning Outcomes

- Understanding the CART algorithm.
- Applying decision trees to regression problems.
- Understanding MSE-based impurity reduction.
- Evaluating regression models.
- Understanding model complexity and overfitting.
- Interpreting decision tree rules and feature importance.

## Dataset Reference

Gerritsma, J., Onnink, R., & Versluis, A. (1981). Yacht Hydrodynamics. UCI Machine Learning Repository.

https://doi.org/10.24432/C5XG7R

Dataset license: CC BY 4.0.

## Author

**Arja Manish**

B.Tech – Computer Science and Engineering

GitHub: https://github.com/Arjamanish

LinkedIn: https://www.linkedin.com/in/manish-arja/

## License

This repository contains original project code and documentation alongside an externally sourced dataset. Refer to the original UCI dataset license for data reuse conditions.