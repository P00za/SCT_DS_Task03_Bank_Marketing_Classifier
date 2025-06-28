# SCT_DS_Task03_Bank_Marketing_Classifier
# SCT_DS_Task_03 – Decision Tree Classifier on Bank Marketing Dataset
This repository contains the solution for *Task 3 (SCT_DS_Task_03)* assigned during my Data Science Internship at *Skillcraft Technology*.

## Task Objective

To build and evaluate a *Decision Tree Classifier* to predict whether a customer will subscribe to a *term deposit, using the **Bank Marketing Dataset* from the UCI Machine Learning Repository.

##  Key Steps

- 🔹 Loaded bank.csv and bank-full.csv datasets
- 🔹 Preprocessed categorical variables using LabelEncoder
- 🔹 Trained a baseline DecisionTreeClassifier using scikit-learn
- 🔹 Applied GridSearchCV for hyperparameter tuning
- 🔹 Evaluated with accuracy, precision, recall, and F1-score
- 🔹 Visualized:
  - Feature importance
  - Decision tree structure
- 🔹 Exported model to .pkl format
- 🔹 Wrote a predict_user() function to simulate real-time predictions

---

##  Files in This Repo

| File | Description |
|------|-------------|
| bank.csv | 10% sample of bank marketing data |
| bank-full.csv | Full version of the dataset |
| bank_marketing_model.ipynb | Full code and analysis in notebook format |
| tuned_decision_tree_model.pkl | Saved model file |
| predict_user.py | Python function to make prediction from user input |
| streamlit_app.py | (Optional) Streamlit UI for live prediction |
| requirements.txt | Python libraries needed |


## Technologies Used

- Python
- pandas, numpy
- scikit-learn
- matplotlib, seaborn
- joblib

## Dataset Source

*Bank Marketing Dataset*  
 [UCI ML Repository – Bank Marketing](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing)

## Acknowledgement

This task was completed as part of the *Data Science Internship at Skillcraft Technology*.

> Task Code: *SCT_DS_Task_03*  
> Role: *Data Science Intern*

##  Author

Pooja Kumari  
p00zasingh@outlook.com  
Data Science Intern at Skillcraft Technology

##  How to Run

1. Clone the repo:
```bash
git clone https://github.com/yourusername/SCT_DS_Task_03_Bank_Marketing_Classifier.git
cd SCT_DS_Task_03_Bank_Marketing_Classifier
