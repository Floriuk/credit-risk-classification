# credit-risk-classification

## Overview of the Analysis

* The analysis performes wasa to create and evaluate a predictive model for the loan status over the population analyzed, using supervised machine learning. 

* The information inside the file was related to lending activities. This information is used by banks to grant credits to people. Loan accounts, number of accounts, number of loans, interests rates, among others. This information was useful to predict if a loan application will be granted or denied.

* The first model trained, contained almost three times more the amount of healthy loans when compared to the amount of high-risk loans. The value counts gave me information to sustain why the model was prediciting perfectly the healthy loans but no the high-risk loans.

* First we loaded and splitted the data to enable the training of the model. This model's performance was evaluated with logistic regression and then resampled to get a better result. When it was resampled, the model was trained again and the new results were evaluated.

## Results

* Machine Learning Model 1:
    * The balanced accuracy of 95% indicated that the model performs correctly when balancing between 0 and 1
    * The precission in Class 0 was prefect with 1.0 ot 100%, but the precission in Class 1 was of 0.85 it is accurate but no perfect.
    * The recall scores scores of 0.99 and 0.91 indicated that the model is better at identifying the 0 Class than the 1 Class, but overall is a great answer
    
* Machine Learning Model 2:
    * The balanced accuracy of 99% indicated that the model performs almost perfectly when balancing between 0 and 1
    * The precission in Class 0 was prefect with 1.0 ot 100%, but the precission in Class 1 was of 0.84 it is accurate but no perfect (lower than the first model).
    * The recall scores scores of 0.99 indicated that the model improved when predicting the 1 Class, and stayed with the same great accuracy in class 0.
    
## Summary

Model 2 performed better. The balanced accuracy score is better with 0.99. The recall values were also higher in this model, this means that the model identifies better both classes. 
Depending on the problem you are facing, you could choose one model over the other. In this case, identifying a class was the main problem, this is why I would choose the Model 2, because it did this job better than the other model. 