# Neural Networks and Deep Learning Models
# Module 19 Assignment



## Overview of the analysis:

The purpose of the analysis is to utilize deep learning to predict which Alphabet Soup funded projects will use their funding successfully. 
Pre-processing the data, train and evaluate the model, and then optimizing it. 

## Results:

## Data Preprocessing

Variable that was considered as the target for my model: IS_SUCCESSFUL Column.
Variables that were considered features for my model: Every Column except for IS_SUCCESSFUL which is our target and the ones we will drop.
Variable that were neither targets or features for the dataset: Columns that I dropeed are EIN, NAME because they will have little to no impact om our outcome

The variable that should be removed are the identification variables: EIN and NAME. They are being excluded as they do not provide any additional data to the data set.


# Compiling, Training, and Evaluating the Model

For neural network model, we had 2 hidden layers.Our first layer had 80 neurons, the second has 30 there is also an output layer. The first and second hidden layer have the "relu" activation function and the activation function for the output layer is "sigmoid."

Was the model able to achieve the target model performance?

The model was not able to reach the target 75%. The accuracy for my model was 69%.


## The steps taken to try and increase model performance

Attempt 1: Removed additional feature, that is the 'USE_CASE' column. Rest of the model components stayed the same, however model accuracy went down to 63%.

Attempt 2: Adding Additional neurons to hidden layers and additional hidden layers are added. The accuracy went down again, this time it was 53%.

Attempt 3: Changing activation function of output layer from "sigmoid" to "tanh." The accuracy of the model went down even more to 50%.



## Summary:

After optimization, Model got 50% accuracy. Initially, Neural Network had 69% accurary score. This loss in accuracy score can be explained from the facts that model got overfitted. We can increase the accuracy score by simply removing more features or adding more data to the dataset. 

Would like to recommend Random Forest Classifiers as it is robust and accurate model due to their sufficient number of estimators and tree depth. Further, it has faster performance than neural network, and can avoid overfitted. 
 
