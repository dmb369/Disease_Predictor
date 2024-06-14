## Datasets: You are provided with the following datasets:
1. Training Dataset (Disease_train.csv): Contains patient features and the target variable for training and validation.
2. Test Dataset (Disease_test.csv): Contains patient features without the target variable for final evaluation.

## Dataset Features:
1. patient_id: Unique identifier for each patient
2. feature_1 to feature_n: Anonymized patient features
3. diagnosis: Target variable (0 = no disease, 1 = disease)
   
# Instructions:

## Download the Dataset:
1. Load the training dataset.
2. Handle missing values appropriately.
3. Perform feature engineering and scaling as required.
   
## Model Training:
1. Split the training dataset into training and validation subsets for model development.
2. Train a machine learning model of your choice (e.g., Logistic Regression, Random Forest, Gradient Boosting).
3. Optimize model hyperparameters for best performance.
   
## Prediction:
1. Load the test dataset.
2. Generate predictions on the test dataset.
3. Save the predictions in a CSV file named student_<ID>_predictions.csv 
