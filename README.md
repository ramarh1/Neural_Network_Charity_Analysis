# Neural_Network_Charity_Analysis
Deliverable 1: Preprocessing Data for a Neural Network Model
Deliverable 2: Compile, Train, and Evaluate the Model
Deliverable 3: Optimize the Model

## Overview of the analysis

In this analysis, we use neural networks to predict a binary outcome, in this case, we are predicting if customers will be successful if funded by Alphabet Soup. The dataset includes 34,000 organizations that have used Alphabet Soup. The challenge consists of preprocessing data, compiling, training, and evaluting the neural network model, and optimizing the neural network model.

## Results

### Data Preprocessing

What variable(s) are considered the target(s) for your model?

*The target variable would be the IS_SUCCESSFUL column in the dataframe.

What variable(s) are considered to be the features for your model?

*The features of the model will be every column that we use, not including the dropped columns.

What variable(s) are neither targets nor features, and should be removed from the input data?

*The 'EIN' and 'NAME' columns are neither targets nor features because we don't believe that they contribute insightful information to our model.

### Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?

*The first model was made up of an input feature, 2 hidden layers, and output layer. The first hidden layer has 100 neurons, while the second hidden layer has 50 neurons. The first two hidden layers have the activation function "relu", while the output layer has the activation function "sigmoid".

![first opt model](https://user-images.githubusercontent.com/88624677/149649984-632ad245-3f9b-4d73-9cbf-8aa18987efe4.png)
![first opt model acc %](https://user-images.githubusercontent.com/88624677/149649992-3265f915-8b74-44e5-a3fb-c525fd6990bb.png)



Were you able to achieve the target model performance?

*Although I attempted to reach the target model performance of 75%, I was unable to reach the target percentage.

What steps did you take to try and increase model performance?

*I tried increasing the neurons for the two hidden layers, changing the activation functions for the hidden layers, as well as adding more hidden layers to the original model.

![3rd opt model](https://user-images.githubusercontent.com/88624677/149650127-f2a85e45-0c92-425d-a98e-c3795fc6cc07.png)
![3rd opt model acc %](https://user-images.githubusercontent.com/88624677/149650130-a423b677-c91b-43b5-b026-a2f889d12d80.png)


## Summary

Overall the accuracy of all the models were around 72.8%, which was not too different from the original model. Even though we dropped two variables that would not be useful in predicting the binary outcome, we could not reach the target of 75% prediction accuracy. I recommend that we drop even more variables to decrease the noise, therefore increasing the accuracy of the model. Perhaps having a larger dataset would help improve the model.
