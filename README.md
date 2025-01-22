# GLM-on-Depression-Data
Using a Generalized Linear Model to predict factors that caused depression.

- Our Approach involved, loading the data in R, and performing exploratory data analysis of the dataset, looking for missing values.
- Next, the approach involved estimating correlation among the predictor variables, to see if any correlation amongst them had any impact on the outcome of depression.
- We find that there is some correlation between incoming_business and education levels.
- Performing a boxplot on the Age variable indicated, that outliers were present in the Age variable, with most distribution being around ages (20-40).
- To determine, what predictor variables influenced the outcome, we proceeded with fitting a GLM model on the target variable depressed. We compared it with other predictor variables
  using the Logistic Regression model, on the cleaned dataset.
- Using Backward stepwise modeling, we were able to determine the features that contribute most to AIC, which is the goodness of fit of how the predictor variable explains the response variable. The variables that have high p-values do not contribute well to AIC and hence are removed improving the generalizability of the model and preventing overfitting.
- We found out that Age, Education Level, and no_lasting_investment predictor variables influenced the outcome of depression.
- Education_level variable is negatively related to the outcome of depression, as is indicated by the negative estimate of -6.480e-02, whereby people with higher education levels were less depressed than others.


