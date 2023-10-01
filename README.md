# deep-learning-challenge

Overview of the analysis:
- The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. Using machine learning and neural networks, and the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

Results:

Data Preprocessing

What variable(s) are the target(s) for your model?
   The target variable is the 'IS_SUCCESSFUL' column from application_df

What variable(s) are the features for your model?
   The feature variables are every other column from application_df --> this was defined by dropping the 'IS_SUCCESSFUL' column from the original dataframe

What variable(s) should be removed from the input data because they are neither targets nor features?
   Both 'EIN' and 'NAME' columns were dropped/removed, because they were neither targets nor features for the dataset.
Compiling, Training, and Evaluating the Model
How many neurons, layers, and activation functions did you select for your neural network model, and why?
Were you able to achieve the target model performance?
What steps did you take in your attempts to increase model performance?

Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.
-
