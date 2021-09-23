# LoanPredictor
- Rough mini-project to automate and deploy a loan predictor using Flask API deployed on an AWS EC2 Instance.

- Constructed transformation pipelines to transform data through preprocessing and feature engineering stages.

- Used WinSCP and PuTTy to connect and deploy Flask API on EC2 instance manually. 


### Example JSON QUERY:

{
"Gender": "Male",
"Married": "No",
"Dependents": "1",
"Education": "Graduate",
"Self_Employed": "No",
"Property_Area": "Rural",
"LoanAmount": 4.85,
"Loan_Amount_Term" : 360.0,
"Credit_History": 1,
"TotalIncome_log": 7.32
}
** NOTE loan amount and total income_log are logged values that were not implemented within the ML pipeline, will implement at a later stage.
