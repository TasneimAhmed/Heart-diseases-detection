# Heart Disease Prediction 

## Dataset Overview:

The dataset contains 76 attributes, but the analysis focuses on 14 primary features, extracted from the Cleveland database. The target variable is "AHD" (presence of heart disease), with values ranging from 0 (no presence) to 4.

## Objective:

To predict the presence of heart disease using classification models. 

## This involves:

Cleaning and preprocessing the dataset.

Building classification models and fine-tuning hyperparameters.

Comparing evaluation metrics to select the best-performing model.

## Data Preprocessing Steps:

Cleaning and Handling Missing Values

Dropped unnecessary column Unnamed: 0.

## Filled missing values in:

Ca using median imputation.

Thal using mode imputation.

Encoded categorical variables using Label Encoding.

## Feature Scaling:

Applied StandardScaler and MinMaxScaler for normalization.

## Feature Selection:

Selected the following features for modeling:

Age, Sex, ChestPain, RestBP, Chol, Fbs, RestECG, MaxHR, ExAng, Oldpeak, Slope, Ca, Thal

## Best Model: Random Forest

## Performance Metrics:

Training Accuracy: 1.0000

Testing Accuracy: 0.9016

Precision: 0.9037

Recall: 0.9016

F1 Score: 0.9017

Confusion Matrix:

[[27  2]
 [ 4 28]]

## Why Random Forest?

High accuracy and robust generalization performance.

Minimal overfitting compared to models like Decision Tree.

Key Insights from Data:

Age and maximum heart rate (MaxHR) strongly influence heart disease prediction.

High correlation observed between Oldpeak and the target variable (AHD).

Features like Ca and Thal significantly impact the classification task.

Visualizations:

Age Distribution by AHD:

Patients with heart disease (AHD=1) tend to have higher age ranges.




   ![image](https://github.com/user-attachments/assets/f930c26e-93e8-44b1-9533-582f8aabc48b)
