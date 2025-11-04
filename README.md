#  Supervised Learning Algorithms — Recap

##  Definition
**Supervised Learning** is a type of machine learning where a model is trained on **labeled data** — meaning the input features and their corresponding correct outputs (targets) are known.  
The goal is to learn the relationship between **inputs (X)** and **outputs (y)** so the model can make accurate predictions on new, unseen data.

---

##  Main Categories of Supervised Learning

| Type | Description | Example Output |
|------|--------------|----------------|
| **Classification** | Predicts **categorical outcomes** (discrete labels) | Yes/No, Pass/Fail, Spam/Not Spam |
| **Regression** | Predicts **continuous outcomes** (numeric values) | Salary, Score, Price, Temperature |

---

##  Examples of Common Supervised Learning Algorithms

| Algorithm | Type | Description | Example Use Case |
|------------|------|--------------|------------------|
| **Linear Regression** | Regression | Finds a straight-line relationship between input variables and target variable. | Predicting student final score or house price. |
| **Logistic Regression** | Classification | Estimates the probability that an instance belongs to a particular class. | Predicting whether a student is eligible for an exam (Yes/No). |
| **Decision Tree** | Both | Splits data into branches based on feature values for easy interpretation. | Predicting student performance or loan approval. |
| **Random Forest** | Both | Combines multiple decision trees to improve prediction accuracy and reduce overfitting. | Predicting exam eligibility or income range. |
| **K-Nearest Neighbors (KNN)** | Classification | Classifies data based on the majority class of its nearest neighbors. | Predicting if a student passes based on similar students. |
| **Support Vector Machine (SVM)** | Classification | Finds the best boundary (hyperplane) that separates different classes. | Classifying spam emails or medical diagnoses. |
| **Naive Bayes** | Classification | Uses probability (Bayes’ theorem) to classify text or categorical data. | Spam detection or sentiment analysis. |

---

##  Example Datasets

### ** Classification Example — Student Exam Eligibility**
| Attendance (%) | Assignments | Disciplinary_Record | Eligible_For_Exam |
|----------------|--------------|---------------------|-------------------|
| 92 | 8 | No | Yes |
| 65 | 5 | No | No |
| 70 | 6 | Yes | No |
| 88 | 7 | No | Yes |

 **Target (y):** `Eligible_For_Exam` (Yes/No)

---

### **2️ Regression Example — Student Final Score Prediction**
| Study_Hours | Attendance (%) | Assignments | Final_Score |
|--------------|----------------|--------------|--------------|
| 4 | 80 | 7 | 65.4 |
| 6 | 90 | 9 | 82.1 |
| 2 | 60 | 4 | 48.2 |
| 8 | 95 | 10 | 91.7 |

 **Target (y):** `Final_Score` (numeric value)

---

##  Key Differences Between Classification and Regression

| Feature | Classification | Regression |
|----------|----------------|-------------|
| **Output Type** | Categorical (labels) | Continuous (real numbers) |
| **Goal** | Assign items to categories | Predict a numeric value |
| **Example Algorithms** | Logistic Regression, Random Forest, SVM, KNN | Linear Regression, Decision Tree Regressor |
| **Evaluation Metrics** | Accuracy, Precision, Recall, F1-Score | MAE, MSE, RMSE, R² |
| **Example** | Predict if student is eligible (Yes/No) | Predict student’s final score |

---

##  Summary

- **Supervised Learning** uses labeled datasets to train predictive models.  
- **Classification** predicts categories, while **Regression** predicts continuous values.  
- Algorithms like **Linear Regression**, **Decision Tree**, **Random Forest**, **SVM**, and **KNN** are core to supervised learning.  
- Proper **data preprocessing** (encoding, scaling, handling missing values) ensures model accuracy and reliability.

---

###  Example Evaluation Workflow

1. **Split data** into training and test sets.  
2. **Encode** categorical columns (e.g., Yes/No → 1/0).  
3. **Scale** numeric features using StandardScaler.  
4. **Train** model using chosen algorithm.  
5. **Evaluate** using metrics (Accuracy for classification, R² for regression).  
6. **Visualize** actual vs predicted results.

---

###  Final Takeaway
> Supervised Learning is the foundation of predictive modeling —  
> enabling systems to learn from examples and make intelligent decisions on unseen data.
