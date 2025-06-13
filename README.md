# Breast Cancer Detection Using Machine Learning
A complete machine learning pipeline to classify breast tumors as benign or malignant using the Breast Cancer Wisconsin Diagnostic Dataset.

## Table of Contents
        About the Project
        Business Case
        Dataset Description
        Project Workflow
        EDA Highlights
        Preprocessing Steps
        Model Training & Evaluation
        Conclusion
        Future Scope
        How to Run

## About the Project
This project aims to assist medical professionals in detecting breast cancer early using machine learning classification techniques. By analyzing various features derived from breast mass scans, we predict whether a tumor is malignant or benign.

## Business Case
Breast cancer is one of the leading causes of death among women. Timely and accurate diagnosis is critical. This project supports doctors in making data-driven decisions using predictive models.

## Dataset Description

    Source: Breast Cancer Wisconsin (Diagnostic) Dataset
    Total Samples: 569
    Features: 30 numeric features (plus ID and diagnosis)
    Target: diagnosis (M = Malignant, B = Benign)

## Project Workflow

    Upload CSV Dataset
    
    Understand Data Columns
    
    Exploratory Data Analysis (EDA)
    
    Handle Corrupted & Missing Data
    
    Remove Highly Correlated Features
    
    Replace Outliers using IQR Capping
    
    Encode and Scale Features
    
    Split Data into Train/Test Sets
    
    Train ML Models (Logistic Regression & KNN)
    
    Evaluate & Select Best Model

## EDA Highlights

Used describe(), countplot, and histplot to explore data.

Found highly correlated features (corr > 0.9 or < -0.9) and removed them to reduce multicollinearity.

## Preprocessing Steps
Corrupted zero values were replaced with median values.

Categorical target (diagnosis) encoded into binary labels.

Outliers handled using IQR-based capping.

Feature scaling done using StandardScaler.

## Model Training & Evaluation

| Metric	  | Logistic Regression |	KNN   |
|-----------|---------------------|-------|
| Accuracy  |        95%	        |  90%  | 
| Precision |	       94%	        |  93%  | 
| Recall	  |        94%	        |  81%  |
| F1 Score	|        94%	        |  87%  | 

## Best Model: Logistic Regression (based on accuracy, precision, and interpretability)

## Conclusion
This project built a reliable breast cancer detection model with high performance. Logistic Regression achieved 95% accuracy, outperforming KNN. The model helps clinicians make informed decisions faster and with greater confidence.

## Future Scope
Explore deep learning models like CNN for raw image data

Create a web app for real-time predictions

Integrate other clinical and genomic datasets

## Contact
If you have any questions, suggestions, or would like to collaborate, feel free to reach out:

👤 Name: Aditya Barahate
📧 Email: adityabarhate18@gmail.com

