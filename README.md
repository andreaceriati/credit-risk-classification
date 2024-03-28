# credit-risk-classification

## Peer-to-Peer Lending Risk Assessment Report

### Overview of the Analysis
The purpose of this analysis is to train and evaluate machine learning models to predict the creditworthiness of borrowers using historical lending activity data from a peer-to-peer lending services company. 

The dataset contains various financial information about borrowers, including loan size, interest rate, income, debt to income, number of accoutns, derogatory marks, total debt, and loan status. The goal is to predict the loan status, classifying it as either a healthy loan (0 label) or a high-risk loan (1 label). The dataset contains 77536 rows and takes into consideration loan sizes varying from $5,000.00 to $23,800.00, with the average loan size being $9,805.56. The income of the considered borrowers ranges from $30,000.00 to $105,200.00,

The dataset contains 77,536 rows and takes into consideration loan sizes varying from $5,000.00 to $23,800.00, with the average loan size being $9,805.56, and the income of the considered borrowers ranges from $30,000.00 to $105,200.00. The dataset also includes various interest rates, reflecting the annual percentage rate (APR) charged on the borrowed amount. It considers the number of accounts held by borrowers, providing insights into their credit history and financial behavior. Finally, the dataset incorporates information about derogatory marks (from 0 to 3 for each borrower), representing negative items on borrowers' credit reports such as late payments, defaults, or bankruptcies, which can impact creditworthiness and risk profile.

The analysis involves typical stages of the machine learning process, including data preprocessing, model creation, training, and evaluation. 

Logistic Regression is utilized as the primary algorithm for binary classification. Logistic Regression is a statistical method commonly used for binary classification tasks, where the goal is to predict the probability that an instance belongs to one of two classes.


## Results
Logistic Regression Model:

- With a precision of 100% for healthy loans and 87% for high-risk loans, the logistic regression model demonstrates a high level of accuracy in correctly identifying healthy loans and a slightly lower but still respectable precision for identifying high-risk loans.

- Achieving a recall of 100% for healthy loans and 89% for high-risk loans, the model effectively captures nearly all instances of healthy loans while also capturing a significant portion of high-risk loans.

- The model achieves an overall accuracy of 99%, highlighting its ability to make correct predictions for the majority of instances across both classes.

## Summary
The logistic regression model exhibits excellent performance in predicting both healthy and high-risk loans. It achieves high accuracy, precision, and recall scores for both classes, indicating its effectiveness in distinguishing between creditworthy and high-risk borrowers. However, it's noteworthy that the model's performance metrics, particularly precision and recall, are slightly higher for healthy loans compared to high-risk loans, suggesting that it may be more effective in identifying healthy loans.

The importance of predicting each class depends on the specific problem and the business context. Predicting healthy loans accurately is crucial for minimizing the risk of default and ensuring the financial health of the lending portfolio, while predicting high-risk loans accurately is essential for mitigating the risk of defaults and managing the overall risk exposure. Therefore, striking a balance between accurately predicting both healthy and high-risk loans is crucial for maintaining a healthy lending portfolio and achieving sustainable growth.

Given the robustness of the model's performance metrics and its ability to accurately classify loans into healthy and high-risk categories, I recommend deploying the logistic regression model for predicting loan risks in the company's peer-to-peer lending activities. Its interpretability and reliable performance make it a valuable tool for enhancing loan assessment processes and minimizing financial risks, especially in accurately identifying healthy loans where its performance excels.

## Repository

In this repository you will find a "Credit Risk" folder, containing a "Resources" folder, with the data used for the analysis, and a Jupyter notebook titled "credit_risk_classification".