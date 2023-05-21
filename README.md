# Loan Eligibility Predict

# Features

| **#** | **Column** | **Dtype** | **Description** |
| :--- | :--- | :--- | :--- |
| 0 | Loan Id | Object | Unique loan id of applicant |
| 1 | Gender | Object | Gender of applicant Male/Female |
| 2 | Married | Object | Status of applicant Married or not |
| 3 | Dependent | Object | Number of children |
| 4 | Education | Object | Education status Graduate or not graduate |
| 5 | Self Employed | Object | self employed or not |
| 6 | Applicant Income | int64 | Income of Applicant |
| 7 | Co-applicant Income | float64| Income of Co-applicant if having other wise 0 |
| 8 | Loan Amount | float64 | Loan amount required by applicant |
| 9 | Loan Amount Term | float64 | Loan amount term in months |
| 10 | Credit History | float64 | Having any loan history |
| 11 | Property Area | Object | Applicant property in which area |
| 12 | Loan Status | Object | Target variable |


# Models
| **Classifiers**  | **accuracy** |
| :--- | :--- |
| **Logistic Regression** | 0.77 |
| **Decision Tree** | 0.69 |
| **Random Forest** | 0.78 |
