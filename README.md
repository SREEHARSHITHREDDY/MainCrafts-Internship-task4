# AI & ML Task 4 - Classification Models, Evaluation Metrics & Imbalanced Data

## Project Overview
This project focuses on building and evaluating a binary classification model using machine learning techniques. The goal is to understand classification metrics beyond accuracy and handle class imbalance effectively.

---

## Objectives
- Understand classification problems
- Train and evaluate classification models
- Use evaluation metrics (Precision, Recall, F1-score, ROC-AUC)
- Handle imbalanced datasets
- Compare multiple models

---

## Dataset Used
- Breast Cancer Dataset (from sklearn)
- Binary Classification:
  - 0 → Malignant
  - 1 → Benign

---

## Tools & Technologies
- Python
- Jupyter Notebook
- pandas, NumPy
- scikit-learn
- matplotlib

---

## Implementation Steps
1. Import required libraries
2. Load dataset
3. Perform train-test split (with stratification)
4. Apply feature scaling (StandardScaler)
5. Train Logistic Regression model
6. Evaluate using:
   - Confusion Matrix
   - Classification Report
7. Plot ROC Curve & calculate AUC
8. Handle class imbalance using class weights
9. Compare with Decision Tree classifier

---

## Evaluation Metrics Used
- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC

---

## Key Observations
- Accuracy alone is not reliable for imbalanced datasets
- F1-score provides a better balance between precision and recall
- ROC-AUC helps measure model discrimination ability
- Class weighting improves performance for minority class

---

## Model Comparison
| Model               | Strengths                         | Weaknesses                     |
|--------------------|----------------------------------|--------------------------------|
| Logistic Regression| Stable, less overfitting         | Less interpretable             |
| Decision Tree      | Easy to interpret                | Prone to overfitting           |

---

## Final Conclusion
Logistic Regression performed better due to its stability and generalization ability. Decision Tree showed higher variance and overfitting tendencies.

---

## Project Structure
AI_ML_Task4/
│── AI_ML_Task4_Classification_Evaluation.ipynb
│── README.md
│── Task4_Report.pdf

---

## Future Improvements
- Hyperparameter tuning
- Use advanced models (Random Forest, XGBoost)
- Try different datasets
- Deploy model as a web app
