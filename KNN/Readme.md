# Problem Statement:

You work for a subscription-based streaming company.

The company wants to identify customers who are likely to churn so the retention team can contact them before they cancel their subscription.

Your task is to build a binary classification model using K-Nearest Neighbors to predict whether a customer will churn.

---

## Solution:

- Build a **K-Nearest-Neighbors Model** both from 'Scikit-Learn' and from 'Scratch'
- also did **Exploratory Data Analysis** and **Feature Engineering**.

Result:

| **Method** | **Accuracy** | **Precision** | **Recall** | **F1 Score** |
|---|---|---|---|---|
| Scikit-Learn | 90.98% | 15.38% | 15.38% | 15.38% |
| KNN - From Scratch | 90.98% | 15.38% | 15.38% | 15.38% |

*low Recall and F1 Score are mainly due to the highly imbalanced dataset, where churn cases are only ~4.67%.Therefore, the model favors the majority class, giving high accuracy (90.98%) but poor churn detection but implementation is correct, as the scratch implementation produced the same results as Scikit-Learn.*
