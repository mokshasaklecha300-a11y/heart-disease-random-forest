# heart-disease-random-forest
 — Random Forest Classifier
Predicts the presence of heart disease from patient clinical data using a Random Forest classifier.
## Overview
Dataset: 303 patient records, 13 clinical features (age, cholesterol, resting blood pressure, max heart rate, etc.) — the standard UCI Heart Disease dataset
Approach: Cleaned and standardized features with `StandardScaler`, split data 80/20 train/test, trained a `RandomForestClassifier` (scikit-learn)
Result: 86.9% accuracy on the held-out test set
## Tools
Python · pandas · scikit-learn · matplotlib
## Files
`ML_Random_Forest.ipynb` — full notebook: data loading, EDA, preprocessing, model training, evaluation
`heart.csv` — dataset (place in the same folder to run the notebook)
## Notes
Training accuracy is 100%, indicating some overfitting on this small dataset — a natural next step would be cross-validation or tuning `max_depth` / `n_estimators` to improve generalization.
