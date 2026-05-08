# 🏦 Beta Bank Customer Retention Model

This project was developed as part of the **TripleTen Data Science Bootcamp**. The objective is to predict customer churn for Beta Bank, allowing the institution to implement targeted retention strategies, as it is more cost-effective to retain existing clients than to acquire new ones.

## 🎯 Project Goal
Build a classification model with a minimum **F1-score of 0.59** to identify customers likely to leave the bank, while also monitoring the **AUC-ROC** metric for model quality.

## 🛠️ Tech Stack
- **Languages:** Python (Pandas, NumPy)
- **Machine Learning:** Scikit-Learn (Random Forest, Decision Tree, Logistic Regression)
- **Techniques:** Class Imbalance Handling (Upsampling/Downsampling), Hyperparameter Tuning (GridSearchCV).
- **Visualization:** Matplotlib, Seaborn

## 📈 Key Results
The final model was optimized to prioritize the detection of positive cases (churn), achieving:
- **F1-score:** 0.60 (Surpassing the project requirement).
- **AUC-ROC:** 0.87 (Exceptional discriminative power between classes).
- **Recall:** 0.78 (Successful detection of 78% of customers at risk of leaving).

## 📁 How to use
1. Clone the repository.
2. Install dependencies: `pip install -r requirements.txt`.
3. Open `Bank_Churn_Prediction.ipynb` to see the full analysis and model training.

---
**Author:** Carlos Andrés Arias Lopez Reyes  
*Data Scientist & Physics Student*
