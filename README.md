# Breast_cancer_Thermography-detection
This project implements an image classification pipeline using PyTorch to classify images into three categories: 'normal', 'Sick', and 'Unknown_class'. The dataset is initially imbalanced, so oversampling is applied to balance the classes. The pipeline includes data preprocessing, model training with early stopping, loss plotting, and evaluation with a confusion matrix. The goal is to build a robust classifier while addressing challenges like class imbalance and overfitting.
# Dataset Source

The dataset is sourced from Kaggle:
Breast Cancer Detection Using Thermography by Thilak02
URL: https://www.kaggle.com/datasets/thilak02/breast-cancer-detection-using-thermography/data

To consider:
1. when we try to balance the class distribution, oversampling should be done after train-val-test split. doing it before the split will bring data leakage problem

To improve: 
Image preprocesisng to get beter features for thermal images.
recall for sick class is very low, we need to balance and try to imporve the score.
   
