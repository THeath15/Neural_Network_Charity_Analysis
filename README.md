# Neural_Network_Charity_Analysis

** Overview of the analysis:** The purpose of this project is to desgin a neural network or deep learning model to create a binary classification that can predict if an Alphabet Soup - funded organization  will be successful based on the features provided in the datataset. Number of inputs, neurons and layers will be determined to classify and evaluate the binary classification model to calculate the model loss and accuracy.

The dataset consisted of a CSV of over 34,000 organizations that received funding from Alphabet Soup. Use of Tensorflow is used to  optimize the model in order to achieve a target predictive accuracy higher than 75%.

# Results: Using bulleted lists and images to support your answers, address the following questions.

** Data Preprocessing**
  ## What variable(s) are considered the target(s) for your model? 
  The target variable is  IS_SUCCESSFUL column  to check and see if it is maked as succesful in dataframe that indicates its funded by Alphabet Soup. 
  ## What variable(s) are considered to be the features for your model?
  IS_SUCCESSFUL column is the feature chosen for this dataset.
  ## What variable(s) are neither targets nor features, and should be removed from the input data?
  EIN and NAME columns are the insignificant columns that can be removed to improve code efficiency  and increase the accuracy of the model. 
  
** Compiling, Training, and Evaluating the Model**
  ## How many neurons, layers, and activation functions did you select for your neural network model, and why? 
    For the first model used. I used 2 layer nodes to train and evaluate the model, one with 80 neurons and the other with 20 neurons, which provided me with 5,241 total trainable parameters. Both  input layers used "relu" activation funcion and an output layer of "sigmoid" function. . 
  
  ## Were you able to achieve the target model performance?  Unfortunately, the  initial model was only able to achieve a 72.6% of accuracy
  
  ## What steps did you take to try and increase model performance?
I tried 3 more models in an attempy to achieve a target predictive accuracy  higher than 75%. Below are the number of input layers, neurons, output layers, activation functions used and the resulting accuracy percentage for each models.
  
 Attempt 1: 
 ![image](https://user-images.githubusercontent.com/92903447/157957080-51e6e8b8-04e7-46eb-a607-6d9a63cc05ef.png)
 Loss and accuracy rate  of 5.56$ Loss and 72.5 % accuracy:
 ![image](https://user-images.githubusercontent.com/92903447/157957607-d95b2c9a-cb8c-4cf4-86b8-e5d55e4dc1e9.png)

Attempt 2: 
![image](https://user-images.githubusercontent.com/92903447/157958088-f2673aec-0c6a-47e5-b900-ba0279598d7c.png)
 Loss and accuracy rate  of 5.54 % Loss and 72.6 % accuracy:
![image](https://user-images.githubusercontent.com/92903447/157958281-35980fe7-c0d1-41dd-87d9-dd2d98c0ab9d.png)

Attempt3":
![image](https://user-images.githubusercontent.com/92903447/157958827-0dde54c1-9ff0-49de-b0c1-7d40c242e53a.png)
Loss and accuracy rate  of 5.6 % Loss and 72.76 % accuracy:

  # Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and explain your recommendation.
Across the different models used,  I was not able to raise the accuracy higher to 75% but the adjustment made yield up to increase in rate  of 72.7% but still close from  initial model  percentage of accuracy of 72.5%. Perhaps we can pursue to attempt more models such as random forests classifier  or SVM and/ or an attempt to increase the epochs or parameters to get the desired accuracy  may yield to a better result. 
