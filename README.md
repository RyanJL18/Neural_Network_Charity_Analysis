# Neural_Network_Charity_Analysis

## Analysis Overview

The purpose of this project is to analyze and classify the successfulness of charitable donations using neural networks with the Tensorflow platform. 

The steps for this process are as follows:

- Preprocessing the data for the neural network model
- Compile, train and evaluate the model
- Optimize model

## Resources

Data File: [charity_data.csv](https://github.com/RyanJL18/Neural_Network_Charity_Analysis/blob/main/charity_data.csv)

Software:

Python 3.9.7, Google Colab

## Data Preprocession

- The columns "EIN" and "NAME" are identified as not helpful in the data and cannot be used as features as they are identification tools. These are removed from the data.

- The "IS_SUCCESSFUL" column can be used as our target for this data.

- The columns "APPLICATION_TYPE", "AFFILIATION", "CLASSIFICATION", "USE_CASE", "ORGANIZATION", "STATUS", "INCOME_AMT", "SPECIAL_CONSIDERATIONS", "ASK_AMT" are used as features for the model.

## Compiling and Training the Model

- This deep-learning neural network model is made of two hidden layers, the first with 80 and the second with 30 neurons.

- The output layer is a binarry classification.

- The accuracy of the model is below 75% which does not make it a good tool in predicting the outcomes of charity donations.

- To improve this, we applied bucketing to a specific feature and organized the different values futher to attempt to improve the accuracy. 

- These steps did not successfully improve the accuracy to above 75%.

## Summary

The model was unable to perform well enough to predict the success of charitable donations as it did not get above 75% with our attempts. 

Since we are aware of the outcomes that are possible, we could apply another form of supervised machine learning such as Random Forest Classifier to get a better idea of performance against our deep learning model.
