# 🏦 Loan Prediction using Python

This project involves building a machine learning model to predict whether a loan will be approved or not, based on applicant data. It uses Python, pandas, scikit-learn, and other standard data science libraries to perform data preprocessing, visualization, and model training.

## 📁 Project Structure

├── Loan Prediction using Python.ipynb # Main notebook for analysis and modeling <br>
├── train.csv # Training dataset <br>
├── test.csv # Testing dataset (without target)<br>
├── sample_submission.csv # Sample format for submission<br>
├── logistic.csv # Possibly preprocessed dataset (used in logistic regression)<br>
└── README.md # Project documentation<br>

## 📊 Objective

To predict loan approval (binary classification) based on customer details such as income, education, loan amount, etc. This type of model is commonly used by financial institutions to automate and improve their loan approval processes.

## 📌 Features Used

- Gender
- Married
- Dependents
- Education
- Self_Employed
- ApplicantIncome
- CoapplicantIncome
- LoanAmount
- Loan_Amount_Term
- Credit_History
- Property_Area

## 🛠️ Technologies & Libraries

- Python 3.x
- Jupyter Notebook
- pandas
- numpy
- seaborn & matplotlib
- scikit-learn (Logistic Regression, Random Forest, etc.)

## 📈 Model Building Process

1. **Data Cleaning & Preprocessing**  
   - Handling missing values
   - Encoding categorical variables
   - Normalizing/Scaling features

2. **Exploratory Data Analysis (EDA)**  
   - Visual analysis of features and target distribution
   - Correlation checks

3. **Model Training**  
   - Logistic Regression
   - Random Forest
   - Model Evaluation using accuracy, confusion matrix, etc.

4. **Prediction & Submission**  
   - Predictions made on the test set
   - Output saved in `sample_submission.csv` format

