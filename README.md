# Predicting Australia’s Unemployment using a Support Vector Machine and Vanilla Neural Network

The project was a final Capstone for one of the hardest subject I had completed throughout the MDS course at JCU. For this project students were expected to implement a Vanilla Neural Network (VNN) and compare it to a selected machine learning (ML) algorithm in order to predict unemployment rate from a time series dataset. For this assessment I chose the ML algorithms Random Forest and Support Vector Machine (SVM) with radial kernel to complete the regression task. The following passage is the Abstract of the report in which the full report has been attached as a PFD in this repository. 

## Abstract

The purpose of this report is to compart the predictive performance of a selected machine learning algorithm with a vanilla Neural Network at a regression task. The regression task involves predicting the Australian Unemployment form a small dataset containing 158 observations and included 7 numeric and one date pre- dictor as well as the numeric response variable. Optimisation techniques were implement on this supervised regression task such as scaling and k fold cross validation to tune each selected algorithm to find the optimal hyper parameters. The metrics used to compare the model performance included, mean squared residual error, R squared and mean absolute error. The final machine learning model used in the final comparison was a support vector machine using a radial kernel which was compared to a three level network with 32 nodes at each hidden layer. Combinations of varying neurons and hidden layers, with the use of K fold cross validation, revealed that 32 nodes in 3 hidden layers produced the most accurate prediction results. However this result may have changed if further time was spent investigating different optimisers available with various combinations of hidden layers and neurons.

Both algorithms produced similar results with observations from June 2018 quarter ranging to December 2020 quarter, However the support vector machine predicted reduced unemployment rates compared to the spike from March 2020 to September whilst the neural network predicted in higher unemployment at this period. However, all evaluation metrics regarding the test data indicated that the support vector machine did a much better job of predicting the unemployment rate than the vanilla neural network. It was expected that the neural network would produce better predictive results due to the complexity of the model however, this may be due to the small amount of observations and features in the supplied dataset in which the simpler model succeeded. Another method that may have improved both results was increase the number of predictors or engineering the variables so that both model could make potential unseen connection. A number of measures could be improve the performance of the neural network included, incorporating back testing or lags on the times series dataset, which would add another level of complexity to the neural network and increase computational demand. Overall, the simple machine learning model won and is more interpretable than the neural network. If this report was repeated and more time was allowed for experimentation of hidden layer and neuron combinations, this may have yielded a different result.
