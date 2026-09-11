# Problem Statement:

You are working as a Data Scientist for a mid-sized technology company.

Employee turnover has increased over the last year. HR wants to identify employees who are likely to leave the company so they can intervene early with retention strategies.

Your task is to build a binary classification model that predicts **whether an employee will leave the company**.

Target Variable: **Attrition**

*Yes* → Employee left the company.
*No* → Employee stayed.

---

## Solution:

- Build a **Logistic Regression Model** both from 'Scikit-Learn' and from 'Scratch'
- also did **Exploratory Data Analysis** and **Feature Engineering**.

Result:

| **Method** | **Accuracy** | **Precision** | **Recall** | **F1 Score** |
|---|---|---|---|---|
| Scikit-Learn | 75.66% | 14.29% | 85.71% | 24.29% |
| Gradient Descent | 73.36% | 12.36% | 78.57% | 21.36% |

*According to the problem statement, goal is to maximize the Recall and the model can identify ~86% of employees who actually leave the company. Although the Precision is relatively low, this trade-off is acceptable for the current business objective, since missing an employee who is likely to leave is more costly than incorrectly flagging an employee who would stay.*
