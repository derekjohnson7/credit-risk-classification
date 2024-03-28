# credit-risk-classification

**Overview of the Analysis:**

The purpose of this analysis is to develop a machine learning model to predict whether a loan is healthy (label `0`) or high-risk (label `1`). This model can help the company assess the risk associated with each loan application, aiding in decision-making processes regarding loan approval.

**Results:**
- Accuracy Score: 0.99
- Precision Score (0 - healthy loan): 1.00
- Recall Score (0 - healthy loan): 0.99
- Precision Score (1 - high-risk loan): 0.84
- Recall Score (1 - high-risk loan): 0.94

**Summary:**

The machine learning model achieved an impressive accuracy score of 0.99, indicating its ability to correctly classify loans into healthy and high-risk categories. The model performed exceptionally well for healthy loans, with a precision score of 1.00 and a recall score of 0.99. This means that the model rarely misclassifies healthy loans and effectively identifies the majority of healthy loans in the dataset.

For high-risk loans, the model achieved a precision score of 0.84 and a recall score of 0.94. While the precision score indicates that there are some false positives (healthy loans incorrectly classified as high-risk), the recall score suggests that the model is effective in identifying high-risk loans.

I recommend using this model for loan risk assessment due to its high accuracy and strong performance in distinguishing between healthy and high-risk loans. The model's ability to accurately predict the majority of high-risk loans, along with its high precision for healthy loans, makes it a valuable tool for the company in evaluating loan applications.