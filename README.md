# Neural Network Charity Analysis
## Overview
#####
## Results
### Data Preprocessing
- The target of our deep machine learning algorithm is the IS_SUCCESSFUL variable. 
- The features of our model are the APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, and ASK_AMT variables.
- The EIN and NAME variables are not target or feature variables needed in this case, so we removed them from the input data. 
### Compiling, Training, and Evaluating the Model
- The first model's nuerons, layers, and activation functions are below. We started the model with only two hidden layers to minimize the likelihood of our model overfitting, creating a baseline to compare to and knowing that we could build and edit our model from here.
![defining_model1.PNG](https://github.com/carinaediaz/neural_network_charity_analysis/blob/main/Images/defining_model1.PNG)
![evlauting_model1.PNG](https://github.com/carinaediaz/neural_network_charity_analysis/blob/main/Images/evaluating_model1.PNG)
- For the second model, epochs were increased from 100 to 250, but there were no significant change to the model's accuracy. 
![defining_model2.PNG](https://github.com/carinaediaz/neural_network_charity_analysis/blob/main/Images/defining_model2.PNG)
![evaluating_model2.PNG](https://github.com/carinaediaz/neural_network_charity_analysis/blob/main/Images/evaluating_model2.PNG)
- For the third model, an additional hidden layer with a lower nodes count was attempted, but the increase in the model's accuracy was only slight. 
![defining_model3.PNG](https://github.com/carinaediaz/neural_network_charity_analysis/blob/main/Images/defining_model3.PNG)
![evaluating_model3.PNG](https://github.com/carinaediaz/neural_network_charity_analysis/blob/main/Images/evaluating_model3.PNG)
- For the fourth model, activation codes for the hidden layers were changed from relu to sigmoid, but the increase in the model's accuracy was also only slight. 
![defining_model4.PNG](https://github.com/carinaediaz/neural_network_charity_analysis/blob/main/Images/defining_model4.PNG)
![evaluating_model4.PNG](https://github.com/carinaediaz/neural_network_charity_analysis/blob/main/Images/evaluating_model4.PNG)
- For the final model, an fourth hidden layer was added and the nodes per hidden layer were increased, but there was no significant change to the model's accuracy. 
![defining_model5.PNG](https://github.com/carinaediaz/neural_network_charity_analysis/blob/main/Images/defining_model5.PNG)
![evaluating_model5.PNG](https://github.com/carinaediaz/neural_network_charity_analysis/blob/main/Images/evaluating_model5.PNG)
- Our target model performance was 75%, so while getting our model very close to this, we did not achive the target model performance in any of our model versions. 
## Summary
