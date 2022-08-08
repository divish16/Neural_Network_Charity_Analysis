# Neural_Network_Charity_Analysis
## Overview
#### The purpose of this project is to use machine learning and neural networks with the Tensorflow platform in order to make predictions on where our company, Alphabet Soup, should make its next investments. With a CSV file consisting of over 34,000 organizations, we use this data to capture data on successful organizations and feed it into our neural networking algorithm so that we can make predictions on which companies Alphabet Soup should continue funding.
## Results
### Data Preprocessing
* The IS_SUCCESSFUL column is our target variable for this project and was the feature chosen our our dataset.
* The EIN and NAME columns were unnecessary for our datasets and were removed from the data.
* Other feature columns include APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, and ASK_AMT.
### Compiling, Training, and Evaluating the Model
* In the optimized model, layer 1 started with 120 neurons with a relu activation.  For layer 2, it dropped to 80 neurons and continued with the relu activation.  From there, the sigmoid activation seemed to be the better fit for layers 3 (40 neurons) and layer 4 (20 neurons). 
* The target for our model was 75%, however, our model could only best at 72.5%
* To increase the performance of our model, we increased the number of neurons in one of our networks and dropped columns STATUS and SPECIAL_CONSIDERATION. We also tried the tanh function, however, none of these tactics greatly improved our model's performance.
## Summary
#### Our model did not reach the desires 75% target. Relu and Sigmoid activation closed in at 72.5% accuracy which was the best performing out of all other models. For better accuracy, I would recommend using Random Forest Classifier since there is less chance that the effects of outliers will affect the data.
