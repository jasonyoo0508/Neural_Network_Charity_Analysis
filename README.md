# Neural_Network_Charity_Analysis

## Overview 

With the knowledge of machine learning and neural networks, we'll use the features in the provided dataset to help a hypothetical company create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup (hypothetical company). The 'Alphabet Group' funded over 34,000 organizations over the years, and the dataset would be provided. 



## Results

**Preorcessing the Data**
Data Preprocessing: The target variables that we wanted to use was the "IS_SUCCESSFUL" feature, which is what we wanted to predict for the success rate of the charity data
The features for the neural network model is the APPLICATION_TYPE and CLASSIFICATION in order to determine the integrity of the charity organization

During the processing, I had to remove STATUS, INCOME_AMOUNT, as well as SPECIAL_CONSIDERATIONS because they did not assist us in the assessment.





**Compiling, Training, and Evaluating the Model**
When creating the model 1 used 2 hidden layers because it seemed like it would help in improving the accuracy score of the model we are trying to use.

![plot](https://user-images.githubusercontent.com/89154507/147517295-adf032ad-509f-4249-bc75-2de068fbe125.png)


**Attempt #1**

![Image 1](https://user-images.githubusercontent.com/89154507/147517367-0c53aeb9-835c-44c6-aedc-3653490a227e.png)


**Attempt #2**

![Image 2](https://user-images.githubusercontent.com/89154507/147517381-ac1c8ff9-d9f4-4688-ac57-6fd8bc9177ca.png)


**Attempt #3**

![Image 3](https://user-images.githubusercontent.com/89154507/147517385-caa7a39f-e2e1-4ff9-a7e8-c379d89f48d2.png)


**Attempt #4**

![Image 4](https://user-images.githubusercontent.com/89154507/147517389-42ea6e59-3dd9-4480-9ff4-5108f496c35a.png)


I tried to implement the modifications by increasing the number of hidden nodes, I also increased the epochs of the machine learning model. 
I also tried to combine both modification into a one set. 

## Summary

The modifications failed to get to 75%, where it was 73%~ and the changes only slightly increased the default accuracy score of the predictions.

To increase the accruacy of the model, changing the number of layers and perhaps using different variables could carry out different results.
