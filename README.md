# Neural_Network_Charity_Analysis

## Overview of the loan prediction risk analysis:

In this analysis, we are trying to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.we used neural network and deep learning to 
With machine learning and neural networks, we used the features in our dataset to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup. The CSV contains more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization, such as the following:

•	EIN and NAME—Identification columns

•	APPLICATION_TYPE—Alphabet Soup application type

•	AFFILIATION—Affiliated sector of industry

•	CLASSIFICATION—Government organization classification

•	USE_CASE—Use case for funding

•	ORGANIZATION—Organization type

•	STATUS—Active status

•	INCOME_AMT—Income classification

•	SPECIAL_CONSIDERATIONS—Special consideration for application

•	ASK_AMT—Funding amount requested

•	IS_SUCCESSFUL—Was the money used effectively

## Results: 

o	Data Preprocessing

We started by eliminating the columns that are unique for each organization such as name and id. Next, we specified our variable of interest is_successful which indicates if the organization used the money funded from Alphabet Soup effectively. All the other features were included in the model.  
All the categorical features were encoded using one-hot encoding technique. After splitting the data into train and test sets, the features were scaled before fitting the neural network model. 
