# Neural_Network_Charity_Analysis

For this analysis, the data was preprocessed for a Neural Network model and was also optimized

## Overview of the analysis
The knowledge of machine learning and neural networks were used to create a binary classifier that tells the customer whether they will be successful or not using alphabet soup. The dataset was quite large. It contained 34000 organizations that have been funded by alphabet soup. Moreover, the data was detailed with elaborative columns capturing the metadata of the type of organization, the funding ask amounts, etc. There were three steps performed in this analysis. Firstly, we preprocessed the data for the neural network. Than we compiled,,trained and evaluated the model. Lastly, we tried to optimize the model as much as possible

## Results of our analysis

### Data Preprocessing

- Our targeted variable was the IS_SUCCESSFUL column
- Most of the data was used as features for our model with the exception of a few columns that were dropped
- We dropped the 'EIN' & 'NAME' columns since both features had little to do with the outcome

### Compiling, Training and Evaluating the model

![image](https://user-images.githubusercontent.com/76402559/118841170-11e8b280-b896-11eb-9f2e-99440638c20d.png)
![image](https://user-images.githubusercontent.com/76402559/118841255-27f67300-b896-11eb-838d-8cabf9b0a045.png)

- The model has a input feature & two hidden layers. The first hidden layer has 80 neurons, the second has 30 neurons. It also has an output layer. Moreover, each layer has an activation function. The first and second hidden layers have an activation function "relu" & the output layer is "sigmoid"

- The model was not able to acheive the target model performance of 75%

![image](https://user-images.githubusercontent.com/76402559/118845841-1fa03700-b89a-11eb-9af5-f142325d9484.png)
![image](https://user-images.githubusercontent.com/76402559/118845907-2f1f8000-b89a-11eb-9fee-7c561e40c1fc.png)

- Some steps that were taken to improve the performance of the model include the addition of additional hidden layers, changing the activation type, changing the number of epochs and changing the number of neuron in each layer

## Summary

