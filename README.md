# Neural_Network_Charity_Analysis

## Overview.

The purpose of this project is create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

## Results.

### Data Preprocessing.
- What variable(s) are considered the target(s) for your model?
  The column "IS_SUCCESSFUL".
  
- What variable(s) are considered to be the features for your model?
  All columns except "IS_SUCCESSFUL", "EIN" and "NAME".
  
- What variable(s) are neither targets nor features, and should be removed from the input data?
  "EIN" and "NAME" columns.
  
### Compiling, Training, and Evaluating the Model
- How many neurons, layers, and activation functions did you select for your neural network model, and why?
  Two hidden layers were used in the model. With 10 neurons for the first layer aprox. number of features and 20 for the second layer.  The activation function for the     input layers was "relu" and for the output layer was "sigmoid". The accuracy achieved was  73.17%.
  
![image](https://user-images.githubusercontent.com/120151872/236702948-9bf08a11-effd-4ae7-b463-789afbb0b917.png)

- Were you able to achieve the target model performance?
  No.

- What steps did you take to try and increase model performance?
  

## Summary.
