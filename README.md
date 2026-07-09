# 💳 Credit Scoring Model using Machine Learning

## 📌 Project Description

The **Credit Scoring Model** is a Machine Learning classification project that predicts a customer's **Credit Score** (High, Average, or Low) based on demographic and financial information. The objective is to help financial institutions assess a customer's creditworthiness using historical data.

This project demonstrates the complete Machine Learning pipeline, including data preprocessing, feature engineering, model training, evaluation, and prediction.

---

## 🎯 Project Objective

To build a machine learning model that accurately classifies customers into different credit score categories using financial and personal attributes.

---

## 📂 Dataset

The dataset consists of customer information such as:

- Age
- Gender
- Income
- Education
- Marital Status
- Number of Children
- Home Ownership
- Credit Score (Target Variable)

**Target Classes:**
- High
- Average
- Low

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Joblib
- Jupyter Notebook

---

## 📋 Project Workflow

1. Import Required Libraries
2. Load the Dataset
3. Explore and Understand the Data
4. Handle Missing Values (if any)
5. Encode Categorical Features
6. Feature Scaling using StandardScaler
7. Split Data into Training and Testing Sets
8. Train Machine Learning Models
9. Evaluate Model Performance
10. Compare Models
11. Save the Best Model
12. Predict Credit Score for New Customers

---

## 🤖 Machine Learning Algorithms

The following classification algorithms were implemented:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

---

## 📊 Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Classification Report

---

## 📁 Project Structure

```
Credit-Scoring-Model/
│
├── credit_scoring_model.ipynb
├── credit_scoring.csv
├── credit_score_model.pkl
├── requirements.txt
├── .gitignore
└── README.md
```

---

## 📈 Results

- Successfully built a multiclass classification model.
- Compared the performance of multiple machine learning algorithms.
- Evaluated models using standard classification metrics.
- Saved the trained model using Joblib for future predictions.

---

## 💾 Saving the Model

```python
import joblib

joblib.dump(rf, "credit_score_model.pkl")
```

Loading the saved model:

```python
model = joblib.load("credit_score_model.pkl")
```

---

## 🚀 How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/Credit-Scoring-Model.git
```

### 2. Navigate to the Project Folder

```bash
cd Credit-Scoring-Model
```

### 3. Install Required Libraries

```bash
pip install -r requirements.txt
```

### 4. Open Jupyter Notebook

```bash
jupyter notebook
```

Run all cells in **credit_scoring_model.ipynb**.

---

## 📌 Future Improvements

- Hyperparameter Tuning using GridSearchCV
- Cross Validation
- ROC-AUC Curve Analysis
- SHAP Feature Importance
- Streamlit Web Application
- Model Deployment

---

## 🎓 Learning Outcomes

This project helped in understanding:

- Data Preprocessing
- Feature Encoding
- Feature Scaling
- Classification Algorithms
- Model Evaluation
- Model Comparison
- Machine Learning Pipeline
- Model Serialization using Joblib

---

## 👨‍💻 Author

**Kirti Singh**

B.Tech Computer Science Engineering

Machine Learning & AI Enthusiast

GitHub: https://github.com/TechKirtisingh

LinkedIn: *(Add your LinkedIn profile link here)*

---

## ⭐ Acknowledgement

This project was developed as part of my Machine Learning learning journey using a Kaggle dataset. It demonstrates the end-to-end implementation of a credit scoring system using Python and Scikit-learn.

If you found this project useful, consider giving it a ⭐ on GitHub.
