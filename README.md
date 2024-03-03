# Loan Approval Prediction

This is a binary classification machine learning project focused on determining the best model for predicting loan acceptance, coded in python.

The associated research paper can be found [here](/paper.pdf)
## Dataset

The dataset used for this project is the [Loan Prediction Dataset](https://www.kaggle.com/datasets/ninzaami/loan-predication) from Kaggle. It consists of 13 columns and 614 rows, with the following features:

| Feature              | Description                                       | Data Type/Ranges            |
|----------------------|---------------------------------------------------|-----------------------------|
| Loan_ID              | Unique identifier for each loan application       | -                           |
| Gender               | Gender of the applicant                           | Categorical: Male or Female |
| Married              | Marital Status of the applicant                   | Categorical: Yes or No      |
| Dependents           | Number of dependants if any                       | Categorical: 0, 1, 2, or 3   |
| Education            | Educational Status                                | Categorical: Graduate or Not Graduate |
| Self Employed        | Defines if the applicant is self-employed         | Categorical: Yes or No      |
| Applicant Income     | Applicant income                                  | Numerical: From 150 to 81000 |
| Coapplicant Income   | Co-applicant income                               | Numerical: From 0 to 41667  |
| Loan Amount          | Loan amount (in thousands)                        | Numerical: From 9 to 650    |
| Loan Amount Term     | Terms of loan (in months)                         | Numerical: From 12 to 480   |
| Credit History       | Credit history of individual’s repayment of debts | Categorical: 0 or 1         |
| Property Area        | Area of property                                  | Categorical: Urban, Semiurban, or Rural |
| Loan Status (Target) | The acceptance or rejection of the loan           | Categorical: Yes or No      |

## License 
This project is licensed under the MIT License

