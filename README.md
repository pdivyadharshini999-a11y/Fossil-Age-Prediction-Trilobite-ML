#  Fossil Age Prediction using Trilobite Dataset

##  Overview

This project predicts the age of trilobite fossils (in million years ago) using geological and location-based features from a real-world dataset.

##  Technologies Used

* Python
* Pandas
* Scikit-learn

##  Workflow

* Data loading and exploration
* Handling missing values
* Feature selection and leakage removal
* Train-test split
* Model training using Random Forest Regressor
* Model evaluation using MAE, MSE, and R2 Score

##  Model Performance

* R2 Score: ~0.94
* MAE: ~3.26

##  Feature Importance

* Longitude (lng) → most important
* Latitude (lat) → second most important

##  Project Structure

* `data/` → dataset
* `notebooks/` → ML notebook

##  Future Improvements

* Compare with Linear Regression
* Use more geological features
* Try advanced models and hyperparameter tuning

