# credit-risk-classification

## Objective:
The objective of this analysis was to use historical lending activity from a peer-to-peer lending services company to build and train a model than can identify the creditworthiness of borrowers.

The features included in the data used to determine the loan status were loan amount, interest rate, income, debt to income ratio, number of accounts, derogatory remarks, and total debt.

The data was split into testing and training. The testing set was put through a LinearRegression model to determine if the model with the aim of determining whether a borrower was a low (0) or high (1) risk of defaulting on a loan. 

## Results:
The overall accuracy of the model was 99%. 
* Low risk: Precision 100%, Recall 99%, F1-score 100%, Support 18765
* High risk: Precision 85%, Recall 91%, F1-score 88%, Suppot 619

## Summary:
The model performs very well for identifying low risk loans, with a nearly perfect precision score. When it comes to predicting high risk loans there is room for improvement. Given that there are many more instances of low risk loans in the dataset a more balanced set of data could aid in improving future models ability to detect higher risk loans. Given the lower accuracy of class 2 (high risk) I would likely recomment additional measures such as resampling the data or adjusting the class weights to define a better prediction model before preceeding with the current one. 
