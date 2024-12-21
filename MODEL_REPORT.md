The purpose of this analysis is to create a deep learning model that predicts whether an organization will be successful based on data provided by Alphabet Soup.
The target is to build a model with a classification accuracy of at least 75% by processing the data effectively, selecting appropriate features, and iteratively refining the model architecture.


Results
Data Preprocessing
- What variable(s) are the target(s) for your model?

The target variable is the IS_SUCCESSFUL column from application_df.
What variable(s) are the features for your model?

The features include all other columns from application_df after dropping the IS_SUCCESSFUL column.
What variable(s) should be removed from the input data because they are neither targets nor features?

The EIN and NAME columns were removed because they do not contribute meaningfully to the prediction and are not relevant as features or targets.



- How many neurons, layers, and activation functions did you select for your neural network model, and why?
The initial model architecture consisted of:
Two hidden layers:
Layer 1: 8 neurons
Layer 2: 5 neurons


 - Were you able to achieve the target model performance?
No, the model achieved an accuracy of approximately 73%


What steps did you take in your attempts to increase model performance?
Modified the network architecture
Refined the input data
Experimented with activation functions


SUMMARY 
The deep learning model successfully captured some patterns in the data, achieving a classification accuracy of 73%, but it fell short of the 75% target.
