# credit-risk-classification

In this analysis, the purpose was to predict the risk level of loans using financial data. The data included information about the loans such as loan size, interest rate, borrower income, and other relevant financial details. The target variable was the loan status, which was categorized as `0` for healthy loans and `1` for high-risk loans.

The machine learning process involved several stages. First, the data was preprocessed, which included cleaning the data, handling missing values, and encoding categorical variables. Then, the data was split into features (the input data) and labels (the target variable). The features and labels were then split into training and testing sets. A logistic regression model was instantiated and trained on the training data. Finally, the model was evaluated on the test data.

The machine learning method used in this analysis was Logistic Regression from the scikit-learn library.

## Results

* Logistic Regression Model:
    * Accuracy: Approximately 99.25%
    * Precision for `0` (healthy loan): 100%
    * Recall for `0` (healthy loan): 99%
    * F1-score for `0` (healthy loan): 100%
    * Precision for `1` (high-risk loan): 84%
    * Recall for `1` (high-risk loan): 94%
    * F1-score for `1` (high-risk loan): 89%

## Summary

The logistic regression model performed very well in predicting both healthy and high-risk loans, with an overall accuracy of approximately 99.25%. The model was particularly effective in predicting healthy loans, with a precision of 100%.

However, the precision for predicting high-risk loans was slightly lower at 84%. This suggests that the model may occasionally misclassify some high-risk loans. Depending on the specific problem we are trying to solve, this could be an area for improvement. For example, if it's more important to correctly predict high-risk loans, we might want to explore other models or techniques that could improve precision for the `1` label.

Despite this, the high overall accuracy and the strong performance in predicting healthy loans make the logistic regression model a strong candidate for this task.