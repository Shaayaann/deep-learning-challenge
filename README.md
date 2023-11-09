# deep-learning-challenge

This analysis aimed to create a model to predict the success of charitable projects. 

The process involved data preprocessing, including dropping irrelevant columns, binning application types, converting categorical data to numeric, and scaling numerical data. The model's target variable was 'IS_SUCCESFUL', and the features used for prediction were listed. 

The initial model accuracy was 72.3% which was below 75%. Two optimization models were accomplished:

Optimized Model 1:
Utilized the kerastuner library for auto-optimization, testing various activation functions, numbers of hidden layers, and neurons in each layer.
Achieved a predictive accuracy of approximately 72.99%.

Optimized Model 2:
Add more neurons to a hidden layer, and 
add more hidden layers.

Revised the model to achieve higher accuracy; however, it was 72.7% and still below 75%.




Both optimized models had higher accuracy than intial one; however, none reached the desired 75% accuracy. Further improvements may be possible by refining the optimization process, such as exploring different activation functions and expanding parameter ranges, dependent on available processing power.
