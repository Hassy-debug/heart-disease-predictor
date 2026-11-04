# Heart Disease Predictor

A machine learning project that predicts whether a patient has heart disease from 13 health measurements.

## What I did
- Loaded and explored a heart disease dataset with Pandas
- Removed duplicate records to avoid data leakage
- Split the data into 80% training and 20% testing sets
- Trained a Random Forest Classifier with Scikit-learn
- Checked the model with accuracy, a confusion matrix and a classification report
- Looked at which features the model relied on most

## Results
- Accuracy: about 75% on 61 unseen test patients
- Recall for heart disease: 0.79 (found 26 of 33 patients with the disease, missed 7)
- Most relied-on features: chest pain type and maximum heart rate

## Limitations
- The test set is small, so results can change with a different split
- Feature importance shows what the model used, not what causes heart disease
- This is a learning project, not a medical tool

## Tools
Python, Pandas, Matplotlib, Scikit-learn, Jupyter

## How to run it
1. Install the libraries: pip install pandas matplotlib scikit-learn jupyter
2. Keep heart.csv in the same folder as the notebook
3. Open heart_disease.ipynb and click Run All

## Dataset
Heart Disease dataset from Kaggle (https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset)
