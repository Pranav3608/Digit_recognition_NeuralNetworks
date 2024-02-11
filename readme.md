## Handwritten Digit Classification using Neural Networks
Handwritten Digit Recognition using a Neural Network is a prediction tool which employs the capabilities of Tensorflow, Keras for developing sequential neural network for predicting correct digits from a Handwritten Digits Dataset. The model utilizes Matplotlib & Seaborn for seamlessly visualizing Data.

# Installation
There are a few prerequisite libraries and dependencies that you need to have for running this model 

-Tensorflow 
-Keras 
-Matplotlib 
-numpy 
-seaborn 

All these dependencies have been mentioned in the requirements file in the repository. 

# Usage and Implementation
The code or the Notebook is divided into majorly five different sections:
1. Data preparation & exploartion: This step involves loading the Handwritten digit dataset and further exploring the dataset ie. shape, structure of the dataset which are necessary steps for further developing the Neural Network for the predictions.

2. Data Modelling and Model/Neural Network Implementation: This step further analyzes the dataset and performs certain Data transformations. Further, a basic Sequential Neural Network is setup using a sigmoid activation function and the training data is trained on the model.

3. Model Evaluation and Predctions: In this step, certain observations regarding the performance of our model on test data set are made. The accuracy is noted for further optimisation. The predictions are visualised against the Truth data ie. Test data for clear conclusions and understanding.

4. Neural Network optimisation: The accuracy and predcitions are noted from the base model and a Hidden layer is added with an activation function 'relu' for further optimising the model accuracy and predictions. 

5. Conclusions and Observations: Significant observations and conclusions are made for better analysis. The model accuracy jumps from 92%(Base model) to 97%(Optimised model). 

# Additional Notes
- The number of Hidden layers can be increased as per the use case, here I have just used one layer for tracking the loss and the accuracy.
- This Neural Network can be further optimised by tuning the parameters.