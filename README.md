# Neural_Network_Charity_Analysis

## Overview
The purpose of this analysis is to use a deep learning neural network with tensorflow to classify data from organizations funded by AlphabetSoup. We are using a binary classifier to help predict which organizations will be successful if funded by AlphabetSoup. Here is a brief description of the metadata:

##### Columns
- EIN and NAME — Identification columns
- APPLICATION_TYPE — Alphabet Soup application type
- AFFILIATION — Affiliated sector of industry
- CLASSIFICATION — Government organization classification
- USE_CASE — Use case for funding
- ORGANIZATION — Organization type
- STATUS — Active status
- INCOME_AMT — Income classification
- SPECIAL_CONSIDERATIONS — Special consideration for application
- ASK_AMT — Funding amount requested
- IS_SUCCESSFUL — Was the money used effectively

## Results

##### Data Preprocessing
- What variable(s) are considered the target(s) for your model?
  - IS_SUCCESSFUL is one of the variables that are considered a target for the model. This variable is binary and depicts if the org was successful after receiving a donation.
- What variable(s) are considered to be the features for your model?
  - APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT are the variables we want to explore in relation to the binary success, or non-success of the org.
- What variable(s) are neither targets nor features, and should be removed from the input data?
  - EIN and NAME have been removed because they are only used for identification.

##### Compiling, Training, and Evaluating the Model
- How many neurons, layers, and activation functions did you select for your neural network model, and why?
- Were you able to achieve the target model performance?
- What steps did you take to try and increase model performance?

## Summary

- Overall results of the deep learning model
- Recommendation for how a different model could solve the classification problem, and the explanation for your recommendation.
