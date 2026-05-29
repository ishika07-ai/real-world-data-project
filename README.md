
# Real-world Data Project (Health Domain)

## Dataset: Pima Indians Diabetes Dataset

## Tools Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- NumPy

## About This Project
Analyzed a real-world health dataset to predict
diabetes outcomes using machine learning and
data visualization techniques.

## What I Did
- Loaded and explored the diabetes dataset
- Performed exploratory data analysis
- Visualized distributions of all health features
- Identified correlations between health indicators
- Built a machine learning prediction model
- Evaluated model using multiple metrics

## Visualizations Created
1. Diabetic vs Non-Diabetic count chart
2. Glucose levels by Outcome box plot
3. BMI by Outcome box plot
4. Feature distributions - all 8 health features
5. Correlation Heatmap - relationships between variables
6. Confusion Matrix - model prediction results
7. Feature Importance - key factors for diabetes
8. ROC Curve - model performance (AUC = 0.83)

## Machine Learning Results
- Model: Random Forest Classifier
- Confusion Matrix Results:
  - True Negatives: 78 (No Diabetes correct)
  - True Positives: 37 (Diabetes correct)
  - False Positives: 21
  - False Negatives: 18
- AUC Score: 0.83 (Excellent!)

## Key Findings
- Glucose was the most important factor
  for predicting diabetes
- BMI was the second most important factor
- Age and DiabetesPedigreeFunction also
  played significant roles
- Diabetic patients had significantly higher
  glucose levels than non-diabetic patients
- Strong correlation between BMI and
  SkinThickness (0.54)
- Model achieved AUC of 0.83 showing
  strong predictive performance

## Files in this Project
- finance_project.ipynb - Main notebook
- distributions.png - All feature distributions
- correlation_heatmap.png - Correlation heatmap
- confusion_matrix.png - Model evaluation
- feature_importance.png - Feature importance chart
- roc_curve.png - ROC curve chart

## Dataset Features
- Pregnancies - number of pregnancies
- Glucose - plasma glucose concentration
- BloodPressure - diastolic blood pressure
- SkinThickness - triceps skin fold thickness
- Insulin - 2-hour serum insulin
- BMI - body mass index
- DiabetesPedigreeFunction - diabetes hereditary score
- Age - age of patient
- Outcome - diabetic or not (target variable)

## Expected Outcome
Applied data science skills in a real-world
health context by building an end-to-end
diabetes prediction system with 83% AUC score
