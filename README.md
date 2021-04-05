# Neural_Network_Charity_Analysis
To create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

# Results
## Data Preprocessing
- The target variable is the IS_SUCCESSFUL column.
- The features were: 
  - CLASSIFICATION
  - APPLICATION TYPE 
  - AFFILIATION
  - USE_CASE
  - ORGANIZATION
  - INCOME_AMT
  - SPECIAL_CONSIDERATIONS.
- The non target or feature variables are EIN and NAME.
## Compiling, Training and Evaluating the Model
Attempt 1 the hidden layers were increased. On attempt 2 I doubled the hidden layers and changed the all layers and activation functions to sigmoid. For attempt 3 I added another hidden layer, selected sigmoid for the activation function and doubled the epochs from 100 to 200.
- Attempt 1 accuracy: 72.27%
- Attempt 2 accuracy: 72.67%
- Attempt 3 accuracy: 72.50%
# Summary
