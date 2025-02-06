# Challenge21_DeepLearning
## Overview
The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.
## Results
### 1. Data Processing
#### What variable(s) are the target(s) for your model?
* The target variable for the model is “IS_SUCCESSFUL”. The value 1 represents Yes and value 0 represents No.
#### What variable(s) are the features for your model?
* The columns exclude EIN and NAME are the features of the model.
#### What variable(s) should be removed from the input data because they are neither targets nor features?
* EIN and NAME was dropped from the model from very beginning.
### 2. Compiling, Training, and Evaluating the Model
#### How many neurons, layers, and activation functions did you select for your neural network model, and why?
Three layers where applied and details can be seen below:
<img width="726" alt="Screenshot1" src="https://github.com/RunningWomann/Challenge21_DeepLearning/assets/126307180/e8d87033-cd70-4d63-94ec-86f253b3ff47">
* Total 477 parameters were generated. 
#### Were you able to achieve the target model performance?
<img width="472" alt="Screenshot 2" src="https://github.com/RunningWomann/Challenge21_DeepLearning/assets/126307180/d25ac5bd-477b-4516-b1b7-fa9109edeed6">

####
* Model accuracy is 73%, below the 75% desired value.
#### Summary
* Adding multipal layers could improve the accuracy of machine leaning. Also, adjust the input data to ensure that no variables or outliers are causing confusion in the model could improve the target predictive accuracy. 
