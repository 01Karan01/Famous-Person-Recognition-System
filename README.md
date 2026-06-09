# FamousPerson_Classifier_System
##Overview

This project is a machine learning-based FamousPerson Classifier system that identifies famous personalities from images. The system uses OpenCV for face detection, Wavelet Transform for feature extraction, and Scikit-Learn classifiers for training and prediction.

##Features
Face detection using OpenCV Haar Cascades
Image preprocessing and face cropping
Wavelet Transform-based feature extraction
Comparison of multiple machine learning models:
Logistic Regression
Linear SVM
Random Forest
Hyperparameter tuning using GridSearchCV
Confusion Matrix and Classification Report for evaluation
Model serialization using Joblib

##Dataset
The dataset consists of images of the following celebrities:

Virat Kohli
Lionel Messi
Serena Williams
Maria Sharapova
IShowSpeed

After preprocessing and face detection, valid face images were extracted and used for model training.

##Model Performance
Model	Cross Validation Accuracy	Test Accuracy
Logistic Regression	83.45%	75.68%
Linear SVM	80.00%	70.27%
Random Forest	70.34%	64.86%

Best Model: Logistic Regression

##Technologies Used
Python
OpenCV
NumPy
PyWavelets
Scikit-Learn
Matplotlib
Seaborn
Joblib
Future Improvements
Increase dataset size and diversity
Use deep learning models such as CNNs
Build a web application for real-time predictions
Improve face detection using modern detectors
##Author

Karan Arya
