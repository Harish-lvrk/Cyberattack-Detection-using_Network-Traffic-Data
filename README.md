# Cyberattack-Detection-using_Network-Traffic-Data

## Project Overview  
This project focuses on detecting and classifying cyberattacks by analyzing network traffic data with machine learning techniques. The work utilizes the widely recognized **NSL-KDD dataset** to benchmark intrusion detection models.

---

## Dataset Details: NSL-KDD  
The NSL-KDD dataset contains network traffic records labeled as normal or attack, each described by 41 features. The data is preprocessed and formatted for effective training and testing.

**Dataset Source:** [NSL-KDD Dataset on Kaggle](https://www.kaggle.com/datasets/hassan06/nslkdd)

- **Training Set:** `KDDTrain+.txt`  
- **Class Labels:**  
  - Normal Traffic (`0`)  
  - Attack Traffic (`1`)

---

## Machine Learning Models Evaluated  

A variety of machine learning classifiers were compared to identify the most suitable model for cyberattack detection:

- Logistic Regression  
- Decision Tree Classifier  
- Random Forest Classifier  
- K-Nearest Neighbors (KNN)  
- Support Vector Machine (SVM)  

---

## Performance Metrics  

Model performance was assessed using:

- Accuracy  
- Precision  
- Recall (Sensitivity)  
- F1-Score  
- Confusion Matrix  
- ROC-AUC Curve  

---

## Conclusion  

This project presents a comparative analysis of multiple machine learning models for detecting cyberattacks in network traffic data. Using the NSL-KDD dataset, it highlights that while simpler models like Logistic Regression and Decision Trees provide interpretability, ensemble methods such as Random Forest typically deliver improved accuracy.

Despite promising results, challenges such as imbalanced data and false positives remain. Future enhancements may include incorporating deep learning models for sequential pattern recognition, advanced feature engineering, and real-time detection capabilities.
