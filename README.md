# 🏋️ Obesity Level Prediction - Machine Learning Project  

![Python](https://img.shields.io/badge/Python-3.11.5-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![Framework](https://img.shields.io/badge/PyCaret-3.0.4-orange)

Predict obesity levels based on dietary habits and physical condition using PyCaret. Developed for academic/research purposes.

## 📌 Overview  
This project trains a multiclass classification model to predict obesity levels (`NObeyesdad`) using variables like caloric intake, physical activity frequency, and family medical history. The workflow includes EDA, hypothesis testing, automated preprocessing, and model deployment.

## 🔍 Dataset  
**`ObesityDataSet.csv`** (2,111 samples, 17 features):  
- **Features**: Age, Height, Weight, FAVC (High Caloric Food Consumption), FCVC (Vegetable Intake), FAF (Physical Activity), etc.  
- **Target**: `NObeyesdad` (7 classes: Normal_Weight, Overweight_Level_I, Obesity_Type_II, etc).  

[Sample Data](data/ObesityDataSet.csv)  

## 🛠️ Features  
- **Automated Preprocessing**: Handling outliers, SMOTE for class imbalance, feature normalization.  
- **Model Comparison**: Logistic Regression, SVM, Random Forest.  
- **Metrics**: Accuracy, F1-Score, Precision-Recall Curves, Confusion Matrix.  
- **Deployment**: Saved pipeline for inference on new data.  

## ⚙️ Installation  
1. **Clone the repository**:  
   ```bash
   git clone https://github.com/BRNDLD/ML_Level_of_Obesity.git

👍
