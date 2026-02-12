This project proposes a data-driven approach for evaluating faculty performance using supervised machine learning. Since the dataset did not contain a target variable, a synthetic performance score was generated using domain-based weighted features.

The model was trained on faculty data including teaching performance, research output, experience, and feedback scores.


**Methodology**

- Conditional logic imputation for missing values

- Synthetic target generation using weighted formula

- Applied regression models for prediction
- 

**Models Used**

- Ridge Regression

- Lasso Regression

- Decision Tree

- Random Forest

- XGBoost


**Best Model**

Lasso Regression

  MSE: 0.0000271

  R²: 0.9991


**Technologies**

- Python

- Pandas

- Scikit-learn

- NumPy
