# Cardio_Predict

### Project Overview
Cardio_Predict is a machine learning project developed by the HeartWise team, aimed at predicting the risk of heart disease in individuals based on clinical and demographic features. Using feature-based analysis, the project involves the training of machine learning models to accurately classify individuals as at-risk or not at-risk for heart disease.

### Team Members
- Muhhamm Owais
- Abdul Hannan
- Zahid Hussain

### Project Objective
The main objective is to build a predictive model that uses various health-related features, such as age, cholesterol levels, and chest pain type, to predict the likelihood of heart disease.

### Dataset Description
- **Shape:** 1025 rows × 14 columns
- **Features:** Includes demographics, clinical measurements, and health history indicators. The primary outcome variable (target) is binary, indicating the presence (1) or absence (0) of heart disease.

#### Key Features Used
1. **Age** - Influential in assessing heart disease risk.
2. **Sex** - Males have a higher risk at a younger age.
3. **Chest Pain Type (cp)** - Differentiates types of chest pain associated with heart disease.
4. **Cholesterol (chol)** - High levels correlate with heart disease.
5. **Exercise-induced Angina (exang)** - Indicates issues during exertion.
6. **Number of Vessels Colored by Fluoroscopy (ca)** - Important for evaluating arterial blockages.

#### Feature Dropped
- **Fasting Blood Sugar (fbs)** - This feature showed weak correlation with heart disease.

### Project Workflow
1. **Data Analysis** - Examine correlations, visualize relationships, and handle missing values.
2. **Feature Selection** - Identify the most relevant features for accurate predictions.
3. **Model Training** - Train models to classify individuals based on the target variable (heart disease).
4. **Evaluation** - Assess model accuracy and fine-tune as necessary.
