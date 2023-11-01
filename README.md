# GenderClassification_MLmodel

This model is built to predict the gender based on the other features. 
This is a twitter dataset.

The csv file is read with the help of pandas library and stored in the Dataframe df. 
With the help of functions like df.describe(), df.corr() and visual data representation using seaborn library (heatmap function), We can compare and eliminate the unnecessary column data. 


After Preprocessing

**Independent features**: '_unit_id', 'profile_yn', 'description', 'gender_gold', 'name', 'profile_yn_gold', 'profileimage'

**Dependent feature** (Target feature): 'gender'

*For the neural network that is built with the sklearn library, ‘relu’ activation function is used.
*For the neural network that is built with the tensorflow library, ‘relu’ activation function is used. For the last dense layer(output), ‘softmax’ activation function is used.
#Rectified Linear Unit(relu): This is a default activation function that makes it is easier for the model to train. It often achieves better performance.
#Softmax: Calculates the relative probabilities and returns the probability of each class.
