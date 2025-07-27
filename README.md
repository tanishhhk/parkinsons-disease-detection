
# Parkinson's Disease Prediction using Machine Learning

This project focuses on predicting Parkinson's Disease using vocal features extracted from voice recordings. It utilizes machine learning algorithms such as Random Forest and SVM for classification, along with Explainable AI (XAI) techniques like SHAP and LIME for model interpretability.

## 🧠 Project Objective

To build a robust machine learning model capable of predicting the presence of Parkinson's Disease using biomedical voice measurements and make the predictions explainable to end-users and clinicians.

---

## ⚙️ Technologies & Libraries

- Python
- Jupyter Notebook
- Pandas, NumPy
- Scikit-learn (Random Forest, SVM)
- SHAP
- LIME
- Matplotlib, Seaborn

---

## 🧪 Methodology

1. **Data Preprocessing**
   - Handling missing values (if any)
   - Feature scaling
   - Train-test split

2. **Model Building**
   - Random Forest Classifier
   - Support Vector Machine (SVM)

3. **Evaluation**
   - Accuracy, Precision, Recall, F1-score, Confusion Matrix

4. **Explainability**
   - SHAP (SHapley Additive exPlanations)
   - LIME (Local Interpretable Model-agnostic Explanations)

---

## 📈 Results

- Achieved high accuracy and robust performance with both Random Forest and SVM.
- SHAP and LIME provided interpretable insights into which features contributed most to predictions.

---

## 💡 Explainable AI (XAI)

Explainability is crucial in healthcare applications. This project implements:
- **SHAP** to show global and local feature importance.
- **LIME** to provide instance-level explanations for specific predictions.

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/SohamSaoji/parkinsons-disease-prediction.git
   cd parkinsons-disease-prediction
   ```

2. Install required libraries:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter notebook:
   ```bash
   jupyter notebook Parkinson_Disease_Prediction.ipynb
   ```

---
