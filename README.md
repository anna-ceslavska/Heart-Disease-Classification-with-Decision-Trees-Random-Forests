# Heart Disease Classification with Decision Trees & Random Forests

This project explores how decision trees, random forests, and custom ensembles can be used to predict types of heart disease based on patient health metrics.

---

## Dataset
The dataset used is `dataset_heart.csv`, containing health-related features (e.g., age, blood pressure, cholesterol) and a target variable indicating heart disease status.

---

## Project Goals
- Compare Decision Tree and Random Forest classifiers
- Evaluate model performance using accuracy and confusion matrices
- Create custom ensembles using feature-split decision trees
- Visualize and analyze model results

---

## Techniques Used
- Decision Tree & Random Forest Classification
- Cross-validation
- Hard voting ensemble of trees trained on different feature subsets
- Accuracy visualization using bar plots
- Feature importance analysis

---

# Key Results
- Random Forest outperformed Decision Tree at shallow depths
- Custom ensemble of three trees outperformed individual trees
- Model accuracy ranged from ~55% to ~70%

---

## Technologies
- Python, Jupyter Notebook
- scikit-learn
- NumPy, Pandas
- Matplotlib, Seaborn
