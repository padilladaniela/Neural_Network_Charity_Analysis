# Neural_Network_Charity_Analysis

Use machine learning and neural networks to help a non-profit predict where to make investments.

# Overview

The purpose of this analysis was to use a neural network to help a non-profit identify investments for fundraising opportunities.

# Results

## Data Preprocessing

- Target variable for the model

IS_SUCCESSFUL

- Feature variables for the model:

APPLICATION_TYPE

AFFILIATION

CLASSIFICATION

USE_CASE

ORGANIZATION

STATUS

INCOME_AMT

SPECIAL_CONSIDERATIONS

ASK_AMT

- Removed variables from the input data:

EIN

NAME

## Compiling, Training, and Evaluating the Model

- Neurons, layers, and activation functions
- 
layer1 = 80 with activation="relu"

layer2 = 30 with activation="relu"

Outer layer activation = "sigmoid"

- Able to achieve the target model performance of 75%?

No

Loss: 0.5594425797462463, Accuracy: 0.7292128205299377

- Steps taken to try and increase model performance:

A third hidden layer was added but decreased the accuracy.

The relu activation was added for layers 1 and 2 was used as they had the highest accuracy of the activations tried.
Neurons in the hidden layers were reassigned several times starting with relatively small numbers (15, 7) to progressively higher (85,50) with out seeing an improvement in accuracy.

# Summary
