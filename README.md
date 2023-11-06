# deep-learning-challenge

## Data Preprocessing

### Variables:
* Names
* Application Types
* Classification

### Features
* "IS_SUCCESSFUL" -- if the money was used effectively

### Variables Removed
* The EIN number was removed from the data

## Compiling, Training, and Evaluating the Model
Since the data is more complex, I added additional layers for the neural network model. I added 4 layers instead of the 2 in the original model. I selected the number of input neurons as the x_train length. For layer 1, I added 110 neurons; layer 2 had 80 neurons, layer 3 had 30 neurons, and layer 4 had 25 layers. The output layer had 1 neuron. This was to start with a lot of neurons and then narrow down to one in order to have better performance and prevent overfitting and high variance. 

To increase model performance, I started with 2 hidden layers and added more until reaching a higher accuracy. Then, I tested different numbers of neurons in the different layers until finding a good accuracy. 

Overall, my model  was improved and ended with an accuracy of 78%. I considered this successful as it was higher than the target of 75%. I liked adding more layers in order to optimize the data. In the future, I would add more variables to sort by in the preproccessing.  
