This machine learning project focuses on predicting the presence of diabetes in patients based on various health-related features. Using a Support Vector Machine (SVM) classifier, the model analyzes diagnostic data such as glucose levels, blood pressure, insulin levels, BMI, and other health indicators. The primary objective is to build a reliable binary classifier that can determine whether an individual is likely to have diabetes or not.

---

## Project Objective  
The aim of this project is to implement an SVM model that can accurately classify whether a patient is diabetic based on input health parameters.

---

## What Was Done  
- Loaded and explored the diabetes dataset to understand the structure and the significance of each feature.
- Preprocessed the data.
- Split the dataset into training and testing subsets to ensure unbiased model evaluation.
- Trained a Support Vector Machine classifier on the training data.
- Evaluated model performance using accuracy, precision, recall, and F1 score on both training and testing data.

---

## Evaluation Metrics

**Training Data:**  
- **Accuracy:** 0.78  
- **Precision:** 0.74  
- **Recall:** 0.56  
- **F1 Score:** 0.64  

**Testing Data:**  
- **Accuracy:** 0.74  
- **Precision:** 0.62  
- **Recall:** 0.67  
- **F1 Score:** 0.64  

---

## Final Outcome  
The SVM model demonstrated moderate predictive performance on both training and testing datasets. While the accuracy and F1 scores suggest a balanced model, the relatively lower recall on training data indicates room for improvement, particularly in reducing false negatives. Nonetheless, the model offers a foundational approach for predictive healthcare applications involving diabetes detection.

---

**Developed by:** *Nischal Baidar*
