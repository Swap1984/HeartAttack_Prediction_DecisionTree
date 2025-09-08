# ❤️ Heart Attack Prediction with Decision Tree (CART & C5.0)

## 📌 Repository Description  
This repository contains my project on **heart attack prediction** using **Decision Tree models (CART & C5.0)**.  
The aim is to explore how decision trees can classify patients at risk of heart attack based on medical attributes such as age, cholesterol, blood pressure, and more.  

This project is part of my journey into applied machine learning, combining healthcare data with interpretable models.

---

## 🚀 Project Overview  
Cardiovascular disease is a major global health concern. Early risk detection can significantly improve preventive care.  

In this project, I:  
- Preprocessed the heart disease dataset  
- Built and compared **Decision Tree (CART & C5.0) models**  
- Tuned hyperparameters for improved performance  
- Evaluated accuracy, confusion matrix, and classification metrics  
- Analyzed feature importance to highlight the most relevant medical predictors  

---
Results & Observations
✅ Model Performance

Accuracy: ~81%

The Decision Tree models (CART & C5.0) performed consistently well, with interpretable rules.

📊 Confusion Matrix

The model correctly classified a majority of heart attack and non-heart attack cases.

Some false negatives were observed (patients predicted as “no risk” who actually had risk).

This highlights the importance of improving recall for high-risk cases.

🧾 Classification Report

Precision: High for non-heart attack class, slightly lower for heart attack class.

Recall: Reasonable but can be improved for the heart attack class.

F1-Score: Balanced overall, demonstrating the model generalizes fairly well.

🔑 Top 5 Important Features

cp (Chest Pain Type)

thalach (Maximum Heart Rate Achieved)

oldpeak (ST depression induced by exercise)

ca (Number of major vessels colored by fluoroscopy)

thal (Thalassemia)

🔎 Interpretation

The Decision Tree achieved ~81% accuracy, making it a reliable baseline predictor for heart attack risk.

Chest pain type, maximum heart rate, and exercise-induced ST depression were the strongest predictors of heart attack risk.

The model showed good precision for detecting patients without risk but needs improvement in recall for at-risk patients (to reduce false negatives).

These results align with medical expectations, adding trustworthiness to the model’s predictions.

Future improvements can include:

Hyperparameter tuning with cross-validation

Handling class imbalance to boost recall

Comparing with ensemble methods (Random Forest, XGBoost)
-----

Inference: By analysing and comparing the confusion matrices of the Best Fit Model(BFM) and the Correlation Based Model we see that,
In the correlation based model(CBM).

1.The proportion of predicting the true positive and true negetive values is the same and more that of the best fit model.
2.The FP values for the CBM are less than the BFM.
3.Also the FN values for the CBM are less than the BFM.

Comparing the Accuracy, Precision and F1 scores of both model

Accuracy: CBM (0.8524)> BFM(0.7868)
Precision: CBM(0.8125) < BFM(0.8461)
Recall: CBM(0.8965) > BFM(0.7096)
F1 score: CBM(0.8524) > BFM(0.7719)

The averge nested crossvalidation score for the BFM(0.77)shows that the model performs morderately Thus the correlation based model is best suited for classification wrt the given heart dataset.

✨ Personal Note

This project is another step in my transition into data science and machine learning.
I enjoy working on healthcare datasets because they have real-world impact, and interpretable models like Decision Trees are valuable in building trust with doctors and patients.

Working on this analysis reinforced how important it is not only to look at accuracy but also at precision, recall, and feature importance, especially in healthcare where each misclassification can have critical consequences.

---

## ⚙️ Installation & Usage  

1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/ANS_Heart_Attack_Decision_Tree.git
   cd ANS_Heart_Attack_Decision_Tree


