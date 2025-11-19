This project predicts whether a passenger survived the Titanic disaster using a clean and efficient Machine Learning pipeline.
It includes basic EDA, feature engineering, custom transformers, and model building using scikit-learn.
Features:
  1.Basic Exploratory Data Analysis (Age distribution, Sex vs Survival, Pclass vs Survival)
  2.Missing value handling
  3.Custom Transformers:
    a.AgeImputer – fills missing age values
    b.FeatureEncoder – encodes Sex & Embarked
    c.FeatureDropper – removes unnecessary columns
  4.End-to-end ML Pipeline (preprocessing + model)
  5.Hyperparameter tuning with GridSearchCV
  6.Random Forest classifier and Logistic Regression for prediction

Tech Stack
    Python
    Pandas
    NumPy
    Seaborn / Matplotlib
    Scikit-learn
