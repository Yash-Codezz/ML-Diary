# Problem Statement:

You are working on an email/SMS filtering system.

The company receives thousands of messages every day, and many of them are unwanted promotional or fraudulent messages.

Your task is to build a machine learning model that classifies a message as:

- spam
- ham → legitimate message

The model should take the text of the message as input and predict whether it is spam.

---

# Solution:

- Build a **Multinomial Naive Bayes Model** both from 'Scikit-Learn' and from 'Scratch'
- also did **Exploratory Data Analysis** and **Feature Engineering**.

Result: 

| **Method** | **Accuracy** | **Precision** | **Recall** | **F1 Score** |
|---|---|---|---|---|
| Scikit-Learn | 100% | 100% | 100% | 100%
| Multinomial Naive Bayes — From Scratch | 100% | 100% | 100% | 100% |

*From the results, it initially appears that the model may be overfitting. However, after further investigation, I found that the issue is primarily with the dataset. The dataset contains a large number of duplicate messages and therefore has very few genuinely unique samples. As a result, the same or nearly identical messages can appear in both the training and testing sets, leading to data leakage. The implementation of the text classification model is correct, but the dataset is not sufficiently diverse to provide a reliable estimate of the model's generalization performance.*
