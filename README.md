# 🎯 Famous Person Recognition System

## 📌 Overview

This project is a Machine Learning-based Famous Person Recognition System that identifies celebrities from images using Computer Vision and Machine Learning techniques.

The system performs face detection, image preprocessing, feature extraction using Wavelet Transform, and classification using multiple machine learning algorithms. Model performance was evaluated using Cross-Validation and Test Accuracy metrics.

---

## 🚀 Features

* Face Detection using OpenCV Haar Cascades
* Automatic Face Cropping and Preprocessing
* Wavelet Transform Feature Extraction
* Feature Scaling using StandardScaler
* Multi-Class Celebrity Classification
* Model Comparison using GridSearchCV
* Confusion Matrix Visualization
* Model Serialization using Joblib

---

## 🏆 Celebrities Included

* Virat Kohli
* Lionel Messi
* Serena Williams
* Maria Sharapova
* IShowSpeed

---

## 🛠️ Technologies Used

* Python
* OpenCV
* NumPy
* PyWavelets
* Scikit-Learn
* Matplotlib
* Seaborn
* Joblib
* Jupyter Notebook

---

## 🔄 Project Workflow

1. Collect celebrity images from publicly available sources
2. Detect faces using Haar Cascade Classifiers
3. Crop and preprocess face regions
4. Extract wavelet features
5. Combine raw image and wavelet features
6. Train multiple machine learning models
7. Perform hyperparameter tuning using GridSearchCV
8. Evaluate model performance
9. Save the best-performing model

---

## 📊 Model Performance

| Model               | Cross Validation Accuracy | Test Accuracy |
| ------------------- | ------------------------- | ------------- |
| Logistic Regression | **83.45%**                | **75.68%**    |
| Linear SVM          | 80.00%                    | 70.27%        |
| Random Forest       | 70.34%                    | 64.86%        |

### ✅ Best Model

**Logistic Regression**

---

## 📈 Classification Report

* Accuracy: **75.68%**
* Macro F1 Score: **77%**
* Weighted F1 Score: **76%**

The Logistic Regression model achieved the best balance between precision, recall, and overall generalization performance.

---

## 📂 Project Structure

```text
Celebrity-Face-Recognition-System/
│
├── opencv/
├── test_images/
├── Face_Recognition_pipeline.ipynb
├── saved_model.pkl
├── class_dictionary.json
├── requirements.txt
├── README.md
└── .gitignore
```

---

## ▶️ How to Run

### Clone Repository

```bash
git clone <repository-link>
cd Celebrity-Face-Recognition-System
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Open Notebook

```bash
jupyter notebook
```

Run:

```text
Face_Recognition_pipeline.ipynb
```

---

## 📷 Results

The system successfully classifies celebrity faces using OpenCV-based face detection, Wavelet Transform feature extraction, and machine learning classifiers. Logistic Regression achieved the best performance with 83.45% cross-validation accuracy and 75.68% test accuracy.

---

## 🔮 Future Improvements

* Increase dataset size and diversity
* Implement CNN-based Deep Learning models
* Real-time webcam face recognition
* Deploy as a Flask/Streamlit web application
* Use modern face detectors such as MTCNN or YOLO

---

## 👨‍💻 Author

**Karan**

---
