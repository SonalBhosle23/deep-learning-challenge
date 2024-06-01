# deep-learning-challenge
Module 21 challenge
Alphabet Soup Charity - Deep Learning
The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. Using the features in the provided dataset, creating a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

Instructions


Install the required libraries using the following commands: !pip install -q -U keras-tuner

Execute the files: "AlphabetSoupCharity.ipynb" and "AlphabetSoupCharity_Optimisation.ipynb".

During the execution of the files, please ensure that "charity_data.csv" is selected during the uploading process of input file.

Summary
Data Preprocessing


What variable(s) are the target(s) for your model?
*The target variable is "IS_SUCCESSFUL"

What variable(s) are the features for your model?
*['APPLICATION_TYPE',
 'AFFILIATION',
 'CLASSIFICATION',
 'USE_CASE',
 'ORGANIZATION',
 'INCOME_AMT',
 'SPECIAL_CONSIDERATIONS']

What variable(s) should be removed from the input data because they are neither targets nor features?
*"NAME", "EIN"

Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?
*2  layers with 120 nodes
Were you able to achieve the target model performance?
*Accuracy: 72.91%
 Loss: 0.5530
What steps did you take in your attempts to increase model performance?
Ran the optimisation way too, which increased accuracy to 73.06% and loss: 0.5560

Resources:
-ChatGPT
-Class activities


Recommendation
A supervised machine learning can be better way to classify the groups and result. Since the number of input parameters are higher.
