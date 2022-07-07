# Neural_Network_Charity_Analysis
Deep Learning Models

## Environment
Tensorflow 

## Overview 
1. Differences between the traditional machine learning classification and regression models 
2. Use neural network models using TensorFlow.
4. Construct datasets for neural network models.
6. State differences between neural network models and deep neural networks.
7. Implement deep neural network models 

## Purpose
Alphabet soup wanted to predict where and how to make investements. The end goal was to use machine learning models as well as neural networks to be able to predict whether applicants will succeed if funded by Alphabet Soup. 

## Results:

### Data Preprocessing
1.Checking to see if the target is marked as successful in the DataFrame, showing that it has been successfully funded by AlphabetSoup.  

2. The IS_SUCCESSFUL column is the feature chosen for this dataset.

3. The EIN and NAME columns will not increase the accuracy of the model.

### Evaluating the Model
![Pic 1](https://github.com/YannMusz/Neural_Network_Charity_Analysis/blob/main/Image/Model%202.PNG)   

4. The target for the model was 75%, but the best the model could produce was 72%

6. Steps used to better performance
Columns were analyzed and the STATUS and SPECIAL_CONSIDERATIONS columns were removed as well as increasing the number of neurons and layers.
![Pic 2](https://github.com/YannMusz/Neural_Network_Charity_Analysis/blob/main/Image/Dev_1_and_2.PNG)   
![Pic 3](https://github.com/YannMusz/Neural_Network_Charity_Analysis/blob/main/Image/Dev3.PNG)    

### Summary:   
The relu and sigmoid activations gave a 72.7% accuracy and is the most accurate model produced using various number of neurons and layers.
-----
