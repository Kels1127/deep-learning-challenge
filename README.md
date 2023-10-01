# deep-learning-challenge
Module 21 Challenge

#  Performance Report For alphabet Soup

##  Overview

##  Results
  Data Preprocessing
  -  The only target variable in the dataset is IS_SUCCESSFUL.
  -  The features which contribute to the analysis include: APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS,           INCOME_AMT, SPECIAL_CONSIDERATIONS, and ASK_AMT.
  -  EIN and NAME are both identifications for the specific businesses that received funding in the past. As such, they do not contribute            directly to the success of the funding and therefor are neither targets nor features.ults

  Compiling, Training, and Evaluating the Model
  - The sucessful model was built with 3 hidden layers with the total of 12 neurons for the first layer, 12 neurons for the second layer and 
    8 neurons for the third layer. I used ReLU as the method for all three hidden layers and sigmoid for the output layer.
  - The model was able to meet the target accuracy of 75% with a peak in my last attempt of 76.08%
  - I attempted to increase the performance of my model by adding an additional layer as well as adding additional neurons.

##  Summary

In summary, while it did take more than one attempt, by implementing additional layers as well as increasing the number of neurons...target model performance was achieved! Training and testing on different epoch level resulted in reducing the bias and helped the model perform with better accuracy. Binning of all the classification values also improved the accuracy results. I think a different approach to classification, such as Random Forest, could capture more complex data interactions and thus improve the model's performance.
