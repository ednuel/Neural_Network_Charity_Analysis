# Neural_Network_Charity_Analysis


# Overview 
Extracted, transformed, and loaded charity_data.csv onto the Jupyter Notebook environment. The data was then trained and tested to create a prediction using neural networks to predict which charities are successful or not. The accuracy was measured to see how succesful the prediction was, while using Pandas, Python, Jupyter Notebook, Scikit-learn, along with tensorflow
# Summary
The target variable for the model was the 'IS_SUCCESSFUL' column. The features were 'APPLICATION_TYPE', 'CLASSIFICATION', 'USE_CASE', 'ORGANIZATION', 'STATUS', 'INCOME_AMT', 'SPECIAL_CONSIDERATIONS', and 'ASK_AMT'. The variables that were removed were 'EIN' and 'NAME' because these values had too many unique values and were not important to the analysis.
# CLASSIFICATION
![](pics/density.png)

# APPLICATION_TYPE
![](pics/density2.png)

# ASK_AMT
![](pics/density3.png)

## CLASSIFICATION
CLASSIFICATION graph displays much more significant spike in unique values between 0 to 2500. This means that those values can really congest an encoded dataset which means that the columns should be grouped into one column.
## APPLICATION_TYPE
Looking at the APPLICATION_TYPE graph, there is a higher density of values with the unique count from 0 to 10000. The graph can help visualize which values need to be joined to make the a less congested encoded dataframe.
## ASK_AMT
The ASK_AMT graph shows that most of the unique values fall under 10 per column and that there is a skewed data at over 25000 unique values in one column. This data set was organized using bins to help separate the different unique columns.
