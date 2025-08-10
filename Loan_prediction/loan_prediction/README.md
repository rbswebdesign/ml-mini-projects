# 🏦 Loan Approval Prediction — Machine Learning in Python

This project predicts **loan approval status** based on applicant details using multiple Machine Learning models.  
It was built for **fast delivery (under 30 minutes)** and tested with 6 different models.

---

## 📊 Project Overview
We use a dataset of loan applications to train classification models and determine whether a loan will be approved.  
Models tested:
1. **SVC (Support Vector Classifier)** — 61.83% accuracy
2. **Logistic Regression** — 73.85% accuracy
3. **Gaussian Naive Bayes** — 74.08% accuracy
4. **Voting Classifier** — 66.51% accuracy
5. **Decision Tree Classifier** — 97.97% accuracy
6. **Random Forest Classifier** — **98.28% accuracy (Best)** ✅

---

## 📂 Dataset
- **Source:** Loan Approval Dataset (CSV)
- **Preprocessing:** Label encoding for categorical variables (`education`, `self_employed`, `loan_status`)

---

## 🛠 Tools & Libraries
- Python 3
- Pandas
- scikit-learn
- Matplotlib
- NumPy

---

## ⚙ How It Works
1. Load the dataset with `pandas`
2. Encode categorical features with `LabelEncoder`
3. Split the data into training/testing sets
4. Train multiple models (`SVC`, `LogisticRegression`, `GaussianNB`, `DecisionTreeClassifier`, `RandomForestClassifier`, `VotingClassifier`)
5. Evaluate models using `accuracy_score`
6. Compare performance to select the best model

---

## 📈 Model Accuracy Chart
![Model Accuracy](loan_prediction_accuracy_chart.png)

---

## 🚀 Quick Start
```bash
# Clone this repository
git clone https://github.com/yourusername/loan-prediction.git

# Navigate into the project folder
cd loan-prediction

# Install dependencies
pip install pandas scikit-learn matplotlib numpy

# Run the script
python loan_prediction.py

