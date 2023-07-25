# credit-risk-classification

# Overview

This analysis is used to determine the creditwortiness of a borrower based on previous lending activity. The data used contains multiple financial factors and indications of healthy and unhealthy loans, factors such as debt to income ratio, loan amounts and total debt are some contributing factors to creditworthiness. To analyze, the data was split into testing and training buckets. The training data was used to build the machine model, and the testing dataset was used to test the accuracy of the model. A logistic regression model was used rate the accuracy of the data, and later the original dataset was resampled as a second check of the accuracy.

# Results
- Logistic regression 1
    In the logistic regression of the original data. The model showed high accuracy for healthy loans with an accruary and f1 score of 1, and recall score of .99. The high-risk loans had a lower accuracy ratings with precision of .85, accuarcy of .91, and f1 score of .88. Overall the total model, had an accuracy score of .99

- Logistic regression Resampled
    The resampled data demonstrated all over higher accuracy with scores of .99 across the board in all metrics.

# Summary
In summary, the accuracy of the model increases with larger samples. In the original model, the high risk loans had a small sample of data to test which would justify the lower accuracy ratings. I would suggest this model as a good tool to use based on the performance in these models.