# neural-network-challenge-2
This assignment aims to predict two key outcomes for employees: whether they will stay or leave the company (attrition) and which department they are best suited for. The goal is to assist HR teams in reducing turnover and optimizing employee placement.

The model uses a dataset with 10 features, such as age, years at the company, job role, and income. It predicts:

1. Attrition: Whether an employee will stay or leave.
2. Department: The most suitable department for the employee, like Sales, IT, or HR.

# Model Details:
 Preprocessing: 
Categorical data, like department and gender, is converted into numerical values. For example, departments are turned into binary columns, and gender is represented as 0 (male) or 1 (female).

Model Structure:
1. For Attrition: The Sigmoid activation function is used with Binary Cross-Entropy as the loss function.
2. For Department: Softmax activation is used with Categorical Cross-Entropy loss.

Training: The Adam optimizer is employed, and the model's performance is evaluated using accuracy and F1-score.


