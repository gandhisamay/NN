# Neural Network
Neural Networks are complex networks which try to figure out the relationship between input features and the output desired.Initially they are defined with some random values and thus have some random relationship but after updating the parameters the model gets better and better and we get close to exact relationship between the input features and outputs

# Overview
Here, I have made a neural network from scratch predicting the probability that a student might be a researcher or not based on the [**Graduates Admssion Dataset**](https://www.kaggle.com/mohansacharya/graduate-admissions) available on [**Kaggle**](https://www.kaggle.com/).
Since the dataset is very small and I have made it from scratch without using any leading frameworks its accuracy might not be that up to the mark but with more data it can be improved to a considerably high level

# Classifier
I have made class NN which I used to classifiy the inputs to 1 or 0 where 1 signifies that the student pursued research and other way round for 0. It is made using a neural network with one hidden layer

## Result
The loss decreases with every passing epoch and the accuracy of the model reaches to 90 %. Coincidently,in this case the loss decreases linearly with every passing epoch as it can be seen from the graph obtained.

![**Loss graph**](https://github.com/gandhisamay/Research-Predictor/blob/main/Images/Graph_Loss_with_iterations.png)
