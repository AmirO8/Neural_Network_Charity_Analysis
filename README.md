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
Attempt 1 the neurons in the hidden layers were increased. On attempt 2 I doubled the neurons in the hidden layers and changed the all layers and activation functions to sigmoid. For attempt 3 I added another hidden layer, selected sigmoid for the activation function and doubled the epochs from 100 to 200.
- Attempt 1 accuracy: 72.27%
- Attempt 2 accuracy: 72.67%
- Attempt 3 accuracy: 72.50%
# Summary
Alll 3 attempts failed to reach the goal of 75% accuracy. Attempt 2 was slightly higher than 1 and 3 but it was a significant difference. Looking at what made attempt 2 slightly higher I could also increase the second hidden layer neurons. This is becuase chaninging the numbr of neurons is an elite way to optimize a models performance. 
