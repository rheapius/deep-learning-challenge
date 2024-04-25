# deep-learning-challenge
Module 21


# Overview:

The purpose of this analysis was to build a binary classifier model that would help select applicants with the best chance of having successful ventures. if funded by nonprofit foundation Alphabet Soup.


# Results: 

## Data Preprocessing

What variable(s) are the target(s) for your model?
'IS_SUCCESSFUL' column in the dataset was the target variable for the model.

What variable(s) are the features for your model?
All the other columns within the dataset have been used as features

What variable(s) should be removed from the input data because they are neither targets nor features?
Variables such as 'EIN' & 'Name' columns should be removed from input data.

## Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?

132 neurons- Three times of the number of features (44) for optimisation
3 layers- Given the complexity of the data, the number of layers was increased
Rectified Linear unit & Sigmoid-  ReLU is best to model positive, non-liner data. Whereas Sigmoid is ideal for binary classification of dataset and used in the outer layer.

Were you able to achieve the target model performance?

Target model performance with accuracy of 75% was not achieved. The model showed accuracy of approximately 72%

What steps did you take in your attempts to increase model performance?
Dropped columns (ASK_AMT)
Added more neurons in hidden layers (from 44 to 132)
Reduced number of epochs (from 200 to 100)

# Summary: 

Overall, the deep learning model could produce 72.6% accuracy, slightly short of the target predictive accuracy of 75%. There are many ways we could make improvements to the model with better data preprocessing.

Firstly, the column ‘ASK_AMT’ i.e. the asked amount for funding, could have been categorised into bins. This could, potentially, improve the performance of the model.
Secondly, the number of columns could be reduced by dropping less relevant ones such as ‘Status’ and ‘Special considerations’. Lastly, more layers could be added to handle the complexity of the dataset. 

These steps could essentially solve the classification problems and improve overal performance of the model
