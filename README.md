# Liver-Disease-Classification-Analysis
## Description This project applies **machine learning techniques** to classify whether a patient has liver disease based on clinical and demographic features.   The work is built on the **Indian Liver Patient Dataset**, and explores data balancing, preprocessing, and supervised learning models.  

Key highlights:
- Data preprocessing and handling class imbalance
- Splitting into train, validation, and test sets
- Training and evaluating models (Random Forest, Logistic Regression, etc.)
- Saving the best model (`Random Forest`) using Joblib for reuse
- Interpreting key clinical indicators contributing to liver disease

The project demonstrates how data-driven approaches can support **early detection** and improve **clinical decision-making**.

## Project Structure
├── LiverAnalysis.ipynb # Main analysis notebook
├── LiverAnalysis.html # Notebook export
├── indian_liver_patient_balanced.xls # Balanced dataset
├── X_Train.xls / X_Val.xls / X_Test.xls # Features (train/val/test)
├── y_Train.xls / y_Val.xls / y_Test.xls # Labels (train/val/test)
├── RF_liver_model.joblib # Trained Random Forest model
├── requirements.txt # Dependencies

## Features
- Data preprocessing & balancing (addressing skew in the dataset)  
- Feature exploration and correlation analysis  
- Model training and hyperparameter tuning  
- Evaluation metrics (accuracy, precision, recall, F1-score)  
- Deployment-ready trained model 
