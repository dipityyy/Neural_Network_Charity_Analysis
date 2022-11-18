# Neural_Network_Charity_Analysis


Overview

Using Tenser Flow, the goal of the project is use the neural network features and machine learning to help create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

Results:

Data Preprocessing Variables targeted: The successful variable was used to measure the outcome.

What variable featured: 'APPLICATION_TYPE', 'AFFILIATION', 'CLASSIFICATION', 'USE_CASE', 'ORGANIZATION', 'INCOME_AMT', 'SPECIAL_CONSIDERATIONS'

What variable(s) are neither targets nor features, and should be removed from the input data:

The EIN and NAME columns were removed because they didn't contribute to the efficiency of the model.

Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?<img width="910" alt="Screen Shot 2022-10-20 at 11 49 41 PM" src="https://user-images.githubusercontent.com/106028585/202596996-5bbbca2d-9143-435e-a23b-0d394ba96217.png">

The first layer has 140 neurons, the second layer has 90, the third layer has 20, and the last two have 1.

Were you able to achieve the target model performance? <img width="659" alt="Screen Shot 2022-10-20 at 11 49 29 PM" src="https://user-images.githubusercontent.com/106028585/202597077-6703547f-78ad-4e42-8c9c-ceecc4645e26.png">


What steps did you take to try and increase model performance? I changed the number of layers I had, the algorithms I used and the number of neurons.

Summary:

By using the relu, sigmoid, and linear algorithms, I was able to achieve 50% accuracy. I would recommend to continue to work with the neurons to see if a higher accuracy can be achieved. Alternatively a different machine learning module can be used. By using supervised learning such as a Random Forest Classifier it is possible to yeild more favorable resutls.
