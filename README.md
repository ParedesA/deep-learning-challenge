# deep-learning-challenge

Overview of the analysis: Explain the purpose of this analysis.

Results: Using bulleted lists and images to support your answers, address the following questions:

Data Preprocessing

What variable(s) are the target(s) for your model? IS_SUCCESSFUL
What variable(s) are the features for your model? APPLICATION_TYPE, CLASSIFICATION, ORGANIZATION, INCOME_AMT, ASK_AMT, AFFILIATION, USE_CASE, STATUS, SPECIAL_CONSIDERATIONS
What variable(s) should be removed from the input data because they are neither targets nor features? EIN, NAME

Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why? 43 neurons to match input and 1 activation function "relu"
Were you able to achieve the target model performance? unfortunately, no
What steps did you take in your attempts to increase model performance? I tried changing the activation function, increasing the number of neurons and layers, reducing the number of features and reducing the number os bins

Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.

Unfortunately, both models kept an accuracy of 53%. I was not able to increase it even after many attempts.
