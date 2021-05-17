# Neural_Network_Charity_Analysis


1.	Overview of the analysis:  The purpose of the analysis is to experiment with different neural network strategies in order to develop a model that performs binary classification of whether a loan will be successfully returned or not with roughly 70 to 75% accuracy on the test set.  
2.	Results: 
o	Data Preprocessing
	The target variable is “IS_SUCCESSFUL”
	What variable(s) are considered to be the features for your model?
'EIN', 'NAME', 'APPLICATION_TYPE', 'AFFILIATION', 'CLASSIFICATION',
   'USE_CASE', 'ORGANIZATION', 'STATUS', 'INCOME_AMT',
'SPECIAL_CONSIDERATIONS', 'ASK_AMT’

	What variable(s) are neither targets nor features, and should be removed from the input data?
o	We are going to use all of the data for now   
o	Compiling, Training, and Evaluating the Model
	How many neurons, layers, and activation functions did you select for your neural network model, and why?
For my NN I tried a 2 hidden layer and 3 hidden layer approach with 24, 12, 24 neurons for experimental purposes.  For the hidden layers I utilized relu acitivation function.  
	Were you able to achieve the target model performance?
o	No, I don’t have enough time to experiment right now.   
	What steps did you take to try and increase model performance?
o	I beefed up the number of epochs to 100 and 200 to squeeze out a lift.  
3.	Summary: 
The overall accuracy of my model is around 73%.  If time permits I can try to squeeze out more lift, however I don’t have time right now.   I could consider utilizing XGBoost and compare the accuracy.   Also I’m not satisfied with the current validation methodology of only getting a single accuracy score on a single test set.   I would prefer to implement a K-fold cross validation strategy to solve this problem.  I would likely utilize XGBoost to compete with NN.  

