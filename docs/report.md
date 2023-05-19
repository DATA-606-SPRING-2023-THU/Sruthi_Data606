# DATA_606 - Capstone Project
- **_Professor_** : **Dr.Chaojie Wang**
- Author : Sruthi Batchala
- Semester : Spring 2023
- Campus ID : OH34738

# Project Title :Credit Card Fraud Detection

# Project Overview
- Credit Card Fraud Detection is the process of identifying and preventing fraudulent transactions made using credit cards. It involves the use of various techniques such as statistical analysis, data mining and machine learning to detect unusual patterns and behaviors that indicate potential fraud.
- The importance of Fraud Detection for Credit Card companies cannot be overstated, as fraud can result in significant financial losses for both the card issuer and the cardholder. 
- It can also damage the reputation of the credit card company, resulting in a loss of customer trust and loyalty. 
- Therefore, it is essential for credit card companies to have effective fraud detection systems in place to protect their customers and themselves. 
- Determine which classifier works best for classifying the data
- Also, Try to implement Artificial Neural Network and compare the accuracy to the best classification model.

# Questions intended to answer
To prevent from fraudulant transactions from taking place in the future, we can use ML algorithms to:
- Understand the distribution of the data that was provided to us.
- Create a sub-dataframe of "Fraud" and "Non-Fraud" transactions.
- Determine which classifier works the best for classifying the data.
- Also, try to create a Neural Network and compare the accuracy to the best classifier achieved.

# Problem Statement
- *Aim*:
Use classification, regression algorithms to identify how well the Model is predicting fraudulent transactions
Along with this, using Artificial Neural Networks to help develop analyzing fraud transactions automatically without human intervention
- *Target Class*:
1. “0” : Non fraudulent cases 
2. “1” : Fraudulent cases 

# EDA Performed
- Understanding the distribution of the data taken
- Scaling the Data columns 
![image](https://github.com/b1sruthi/Sruthi_Data606/assets/124225545/412fbb3d-4e3c-4f4c-af6d-8965396153cc)

- Creating a sub dataframe of fraud and not-fraud transactions
<img width="440" alt="image" src="https://github.com/b1sruthi/Sruthi_Data606/assets/124225545/ee1673b5-473d-4d3a-87d0-c66a65ac3339">
<img width="470" alt="image" src="https://github.com/b1sruthi/Sruthi_Data606/assets/124225545/6e15ef10-1380-4705-8290-9be4776cbe99">

- Checking for Outliers and eliminating them
<img width="1392" alt="image" src="https://github.com/b1sruthi/Sruthi_Data606/assets/124225545/37f92c8d-4f26-4cd9-afd7-8823c7ea194d">

- Determining which classifier works best for classifying the data
- Also, Tried to implement Artificial Neural Network and compare the accuracy to the best classification model.

# ML models used and their accuracy scores
- Have used both regression and classification algorithms to determine which model works best for the given dataset.
*Regression Models used:
1. Random Forest  -  accuracy: 93%
2. Linear Regression  -  accuracy: 88%
3. Bagging Regressor  - accuracy : 89%
4. Decision Tree Regressor  - accuracy: 93.5%
*Classification Models used:
1. Logistic Regression  - accuracy:95%
2. Random Forest Classifier - accuracy: 94%
3. Decision Tree Classifier. - accuracy: 85%
4. Ensemble Model. - accuracy:93%

- From all the models that were used to predict whether a particular transaction Is fraudulent or not, the best model turned out to be Logistic Regression.

# ANN Implementation
- Have implemented Artificial Neural Networks to check how well the AI model is going to perform for this data
- Have used activation functions like relu and sigmoid for a sequential analysis and as expected the Artificial Neural Networks work way better than any of the ML models With accuracy being more than 98% for both train and test datasets.
- It is concluded that ANN’s work best for detecting frauds during credit card transactions.

# Technologies Used
- programming language : Python.
- libraries : Pandas, Seaborn, sklearn, scipy, Tensorflow.
- algorithms : classification, regression models along with Artificial Neural Networks.

# Lessons Learnt 
- Firstly, it was very hard to deal with imbalanced Data along with the actual feature names being hidden for confidential reasons.
- Choose algorithms based on the data you use.
- Try solving the problem with the simplest algorithms and gradually increase complexity.
- What is the best model - Consider two critical factors ? Obviously, consider the results and metrics. Also consider how important the accuracy is, what difference does an improvement of 0.1% make ? Specifically in-case of highly imbalanced classification problems, consider the minority classes.
- Highly imbalanced case - overall accuracy has very less weightage compared to the individual accuracies of the minority classes. 

# Repository Structure
- docs : directory for project draft and final documentations.
- src : directory for project code base.

### Links:
#### Presentation links:
- [Youtube](https://www.youtube.com/watch?v=hBOj2BPYU4Y)
- [Powerpoint presentation](https://github.com/b1sruthi/Sruthi_Data606/blob/main/docs/Capstone_project.pptx)

