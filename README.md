# **TITANIC - MACHINE LEARNING FROM DISASTER**

This project was developed as part of the Kaggle competition [Titanic - Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic). The goal was to build a classification model that predicted if a passenger survived the sinking of the Titanic or not.

As my second Kaggle competition, following the “House Prices - Advanced Regression Techniques” challenge, it allowed me to deepen my understanding of classification problems, unbalanced datasets, and model optimization using advanced tools like Optuna. Working through this dataset helped strengthen my ability to build structured, reproducible data science workflows — and continues to support my transition toward the Data Science field.
<br>
<br>

## **PROJECT OBJECTIVE**

Build a robust classification model capable of accurately predicting passenger survivability using advanced data preprocessing, feature engineering, and Stratified K-Fold Cross-validation for Unbalanced Data.
<br>
<br>

## **LANGUAGES AND TOOLS**

- **Programming Language**: Python;
- **Data Manipulation**: `pandas`, `numpy`;
- **Visualization**: `matplotlib`, `seaborn`;
- **Modeling**: `XGBoostClassifier` with `Stratified K-Fold Cross-validation`;
- **Hyperparameter Tuning**: `Optuna`;
- **Preprocessing**: `MaxAbsScaler`, `K-Fold Target Encoding`, `Feature Importance`.
<br>

## **PROJECT WORKFLOW**

### 1. Missing Data Handling
- Missing values were treated **case-by-case**, with contextual understanding of each feature;
- No blind imputation or mass dropping of data to preserve useful information.

### 2. Outlier Analysis
- Outliers were also evaluated **individually** to avoid discarding valuable data;
- Visual and statistical analysis were used to detect and decide on their treatment.

### 3. Exploratory Data Analysis (EDA)
- Target variable distribution analysis and normalization;
- **K-Fold Target Encoding** for categorical features;
- Feature importance avaliation;
- **Feature Engineering** to uncover new patterns and relationships between features and the target.

### 4. Data Normalization
- Used **MaxAbsScaler** to normalize the data and maintain sparsity of the features.

### 5. Modeling and Optimization
- Trained a XGBoost Classifier model;
- Used **Optuna** for hyperparameter tuning to optimize model performance;
- Used Stratified K-Fold Cross-validation because the target variable was unbalanced;
- Achieved an **Accuracy Score of 0.85**.
<br>

## **MODELING**

Trained and tuned a XGBoost Classifier model that underwent **hyperparameter tuning using Optuna**, a powerful optimization framework.

Used Stratified K-Fold Cross-validation because the target variable was unbalanced.

## **PROJECT STRUCTURE**

```bash
├── data/                   # Raw and processed data
├── notebooks/              # Jupyter Notebooks (EDA, modeling, etc.)
├── models/                 # Saved model files and evaluation results
├── visuals/                # Plots and visualizations
├── README.md               # Project documentation
└── requirements.txt        # Required Python packages
```
<br>

## **RESULTS**

- Final Accuracy Score: **0.85**;
- Strong performance thanks to:
  - Feature engineering and encoding;
  - Individualized outlier/missing data treatment;
  - Stratified K-Fold Cross-validation.
<br>

## **WHAT I LEARNED**

- Applying data preprocessing and handling missing data contextually;
- Engineering features that improve model performance;
- Using cross-validation techniques for unbalanced classification tasks;
- Tuning hyperparameters with Optuna;
- Building an end-to-end workflow in a structured and replicable way.
<br>

## **FUTURE IMPROVEMENTS**

- Test other classifiers like LightGBM, Random Forest and Stacking;
- Explore SHAP for model interpretability;
- Optimize pipeline using scikit-learn's Pipeline;
- Deploy model using Flask or Streamlit.
<br>

## **AUTHOR**

**Fábio Galdino**