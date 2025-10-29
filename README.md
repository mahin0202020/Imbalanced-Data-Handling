📄 Project Overview

This project demonstrates:

How to train a Decision Tree Classifier using entropy.

How to apply Logistic Regression for binary classification.

How to handle imbalanced datasets using:

Random Under Sampling (RUS)

SMOTE (Synthetic Minority Over-sampling Technique)

SMOTE-Tomek (Combination of over & under sampling)

📊 Datasets Used

salaries.csv

Columns: company, job, degree, salary_more_then_100k

Used for Decision Tree Classification

Predicts whether a person earns more than 100k or not

churn.csv

Used for Logistic Regression

Predicts whether a customer will churn (leave) or stay

⚙️ Technologies & Libraries

Python 3.x

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn (sklearn)

Imbalanced-learn (imblearn)

🔍 Steps Followed

Imported and explored dataset using pandas

Encoded categorical columns (like company, job, degree)

Trained a Decision Tree Classifier (entropy)

Evaluated using classification_report and confusion_matrix

Trained Logistic Regression model on churn.csv

Fixed imbalance using:

RandomUnderSampler

SMOTE

SMOTETomek

Compared model performance (before & after balancing)

📈 Results

Decision Tree model achieved high accuracy on the salary dataset

Logistic Regression model improved after applying SMOTE & SMOTETomek

Balanced data gives better recall for minority classes

🚀 How to Run
# Install dependencies
pip install pandas numpy scikit-learn imbalanced-learn seaborn matplotlib

# Run the notebook
jupyter notebook project.ipynb

👨‍💻 Author

Abdullah 504
B.Sc. in Software Engineering, Daffodil International University
📧 Email: abdullahmahiner@gmail.com

📞 Contact: 01625205641
