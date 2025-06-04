
## Heart Disease Prediction: Decision Tree & Random Forest

### Overview

This project implements machine learning models to predict heart disease using clinical data. It includes model training, evaluation, visualization, and interpretation.

### Key Features

1. **Train & Visualize Decision Tree:** Build a decision tree classifier and plot the tree structure for interpretability.
2. **Overfitting Analysis:** Compare training and test accuracy, and control model complexity via tree depth.
3. **Random Forest Training:** Train a random forest classifier and compare its accuracy against the decision tree.
4. **Feature Importance:** Extract and visualize key feature importances influencing predictions.
5. **Cross-Validation:** Evaluate model robustness with k-fold cross-validation and report average accuracy.

### Dataset

* `heart.csv` with clinical features and binary target (`target`: 0 = no disease, 1 = disease).
* Source: [Kaggle Heart Failure Prediction Dataset](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction)

### Requirements

```bash
pip install pandas scikit-learn matplotlib
```


