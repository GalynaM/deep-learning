## deep-learning

## Project description:
### Create an algorithm to predict whether or not applicants for funding will be successful

### Tools used:
* Pandas and the Scikit-Learn.
* TensorFlow to design a neural network.

### Starter_Code.ipynb

#### Data Preprocessing
* Defined the target(s)/feature(s) variable(s) for the model.
* Droped non significant columns, reduced data by binning rare values.
* Categorical variables encoded using pd.get_dummies(). 

#### Model Compilation, Training, and Evaluation
* A neural network created via TensorFlow Keras with defined hidden layers, output layer and appropriate activation functions.
* Model saved and exported to HDF5 file - AlphabetSoupCharity.h5.

### AlphabetSoupCharity_Optimization.ipynb

#### Model Optimization 
* In order to achieve a target predictive accuracy higher than 75%, model was optimized using all of the following:
  - Adjusting the input data.
  - Adding more neurons to a hidden layer.
  - Adding more hidden layers.
  - Using different activation functions for the hidden layers.

### Charity Funding Predictor Report.pdf
* This is a Report on the Neural Network Model.

Please note a1, a2, a3 are just folders where tuned models data were stored
