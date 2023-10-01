# deep-learning-challenge

Overview of the analysis:
- The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. Using machine learning and neural networks, and the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

Results:

Data Preprocessing

1. What variable(s) are the target(s) for your model?

- The target variable is the 'IS_SUCCESSFUL' column.

2. What variable(s) are the features for your model?

- The feature variables are every other column.

3. What variable(s) should be removed from the input data because they are neither targets nor features?

- The 'EIN' and 'NAME' columns were dropped because they were not targets nor features in the dataset.


Compiling, Training, and Evaluating the Model

4. How many neurons, layers, and activation functions did you select for your neural network model, and why?

- I used 10 hidde nnodes for layer 1 and 5 nodes for layer 2. I chose this as a estimate i thought would work.
  
5. Were you able to achieve the target model performance?
   
- The model only reached 72.5% accuaracy

6. What steps did you take in your attempts to increase model performance?
   
- I added layers, removed columns, and added more hidden nodes in order to achieve a higher accuracy.

Summary:
- The model was 72.5% accurate in predicting successful applicants. Using a model with a more correlating input and output would result in a higher prediction accuracy. This could be acheived by doing more extensive data cleaning.
