# Neural_Network_Charity_Analysis

## Overview

Create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

From Alphabet Soup’s business team, Beks received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years.

- Deliverable 1: Preprocessing Data for a Neural Network Model
- Deliverable 2: Compile, Train, and Evaluate the Model
- Deliverable 3: Optimize the Model
- Deliverable 4: A Written Report on the Neural Network Model (README.md)

## Results

### Data Preprocessing
- What variable(s) are considered the target(s) for your model?
The "IS_SUCCESSFUL" column.

- What variable(s) are considered to be the features for your model?
EIN, NAME, APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT, IS_SUCCESSFUL.

- What variable(s) are neither targets nor features, and should be removed from the input data?
EIN, NAME.

### Compiling, Training, and Evaluating the Model
- How many neurons, layers, and activation functions did you select for your neural network model, and why?
To optimize the model, I ran through a variety of models, trying three hidden layers, four hidden layers, and five hidden layers. I also increased the neurons for each hidden layer which although a potential for overfitting, was showing slight improvement. 

- Were you able to achieve the target model performance?
The base model of 0.7297 was slightly improved to 0.7350 but did not reach the target of 0.750.

- What steps did you take to try and increase model performance?
Additional neurons were added to the hidden layers, additional hidden layers were added to the model, and the activation function of the hidden layer was changed from relu to tanh. 
