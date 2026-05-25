# Loan Approval Prediction Using Machine Learning

## Project Overview

This project focuses on predicting loan approval status using supervised machine learning algorithms. The model analyzes applicant information such as income, education, credit history, employment status, and loan amount to determine whether a loan application is likely to be approved.

The project demonstrates the complete machine learning workflow including:
- Data preprocessing
- Exploratory Data Analysis (EDA)
- Feature engineering
- Model training
- Model evaluation
- Performance visualization

---

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Machine Learning Algorithms Used

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

---

## Dataset

Dataset used:
Loan Prediction Dataset from Kaggle

Main target variable:
- `Loan_Status`

Features include:
- Gender
- Married
- Education
- ApplicantIncome
- CoapplicantIncome
- LoanAmount
- Credit_History
- Property_Area
- and more

---

## Project Workflow

1. Data Collection
2. Data Cleaning
3. Handling Missing Values
4. Encoding Categorical Variables
5. Exploratory Data Analysis
6. Feature Selection
7. Train-Test Split
8. Model Training
9. Model Evaluation
10. Visualization and Conclusion

---

## Model Evaluation Metrics

The models were evaluated using:
- Accuracy Score
- Confusion Matrix
- Classification Report
- ROC Curve
- ROC-AUC Score

---

## Visualizations

### Confusion Matrix

![Confusion Matrix](confusion_matrix.png)

---

### ROC Curve

![ROC Curve](roc_curve.png)

---

### Feature Importance

![Feature Importance](feature_importance.png)

---

## Results

Among all models, the Random Forest Classifier achieved the best performance with higher accuracy and ROC-AUC score.

The project successfully demonstrated predictive modeling techniques and supervised machine learning concepts.

---

## Files Included

- `Loan_Approval_Prediction.ipynb`
- `train_u6lujuX_CVtuZ9i.csv`
- `output_predictions.csv`
- `confusion_matrix.png`
- `roc_curve.png`
- `feature_importance.png`
- `README.md`
- `requirements.txt`

---

## Author

Aditya Patil

---

## Future Improvements

- Hyperparameter tuning
- Cross-validation
- Model deployment using Streamlit
- Advanced feature engineering
- Integration with web applications
