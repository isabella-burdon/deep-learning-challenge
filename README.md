# deep-learning-challenge

## Report:

### Overview of the analysis: 
This neural network model was built for a (fictional) venture capital fund 'Alphabet Soup' to predict if companies are likely to be successful based on historical data the company had collected.

### Results: 
Using bulleted lists and images to support your answers, address the following questions:

#### Data Preprocessing

What variable(s) are the target(s) for your model?
* The targets are the companies

What variable(s) are the features for your model?
* The features are the metadata that Alphabet Soup have been collecting about their venture companies.
* This includes data like "ask amount", "application type", "income amount", "Special considerations" and of course whether or not that venture company became successful.

What variable(s) should be removed from the input data because they are neither targets nor features?
Compiling, Training, and Evaluating the Model
* EIN
* Name

How many neurons, layers, and activation functions did you select for your neural network model, and why?
* number of input neurons selected was = number of features
* number of output nodes = 1 (binary outcome)
Were you able to achieve the target model performance?
* Yes
What steps did you take in your attempts to increase model performance?
= Preprocessing of data to suitable standard
* Removal of features that had few values so as not to overfit the data
* Scaling of data
* Splitting of data for testing and training
* Selection of n nodes

Summary: Summarise the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.
* The loss value of 0.56 indicates that there is a moderate prediction error
* The accuracy is 0.73 indicating that the the prediction are correct 73% of the time.
* The company may be interested in improving the performance of the model to reduce these prediction errors, they can use the loss value as a guide for how the model performs in training and if there will be a reduction in prediction errors. They may be able to improve the model by increasing the amount of data or improving the quality of the metadata being used as features in the model.
