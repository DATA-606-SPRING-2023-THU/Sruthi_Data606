1. What is your issue of interest (provide sufficient background information)?
- The issue of interest in using machine learning (ML) models for credit card fraud detection is to improve the accuracy and efficiency of detecting fraudulent transactions. With the increasing amount of financial transactions being conducted online and the growth of sophisticated fraudsters, traditional fraud detection methods may not be enough to effectively detect and prevent fraud. ML models can analyze large amounts of data and identify patterns and anomalies that may indicate fraudulent activity, which can help improve the detection and prevention of credit card fraud.

--------------------------------------------------------------------------------------------------------------------------------------------------------------
2. Why is this issue important to you and/or to others?
- This issue is important because credit card fraud can have serious financial and legal consequences for individuals and businesses. For individuals, fraud can result in unauthorized charges and a loss of funds, as well as damage to their credit score and a loss of trust in the financial system. For businesses, fraud can result in losses from chargebacks, reputational damage, and the cost of investing in fraud prevention measures.
	Moreover, credit card fraud is a major challenge for the financial industry and the economy as a whole. With the increasing number of online transactions, the financial industry is faced with the task of detecting fraud in real-time while still allowing for quick and seamless transactions for legitimate customers.
	Therefore, the use of ML models in credit card fraud detection can have a significant impact by improving the accuracy and speed of detecting fraudulent transactions, reducing financial losses, and restoring trust in the financial system.

-------------------------------------------------------------------------------------------------------------------------------------------------------------
3. What questions do you have in mind and would like to answer?
To prevent from fraudulant transactions from taking place in the future, we can use ML algorithms to:
- Understand the distribution of the data that was provided to us.
- Create a sub-dataframe of "Fraud" and "Non-Fraud" transactions.
- Determine which classifier works the best for classifying the data.
- Also, try to create a Neural Network and compare the accuracy to the best classifier achieved.

-------------------------------------------------------------------------------------------------------------------------------------------------------------
4. Where do you get the data to analyze and help answer your questions (creditability of source, quality of data, size of data, attributes of data. etc.)?
- Acquired the data from data.world.com 
the link to the source is as follows: https://data.world/vlad/credit-card-fraud-detection
- The data is highly imbalanced, hence I'd like to see how it can be used for analysing this real time problem.
- the size of the data is 150MB.
- Attributes include time,  V1, V2, … V28 principal components obtained with PCA, Amount and target class (284807,31).

-------------------------------------------------------------------------------------------------------------------------------------------------------------
5. What will be your unit of analysis (for example, patient, organization, or country)? Roughly how many units (observations) do you expect to analyze?
- The dataset contains transactions made by credit cards in September 2013 by European cardholders so I'd be analysing europeans who have creditr cards and monitor their transactions.

-------------------------------------------------------------------------------------------------------------------------------------------------------------
6. What variables/measures do you plan to use in your analysis (variables should be tied to the questions in #3)?
- I'd be using all the columns first and then try extracting important features to find the best classification problem.

-------------------------------------------------------------------------------------------------------------------------------------------------------------
7. What kinds of techniques/models do you plan to use (for example, clustering, NLP, ARIMA, etc.)?
- I'd like to use models like Random Forest, Logistic Regression, Naive Bayes, K-Nearest Neighbors, Decision Tree, Support Vector Machines and Neural networks (If Possible).

-------------------------------------------------------------------------------------------------------------------------------------------------------------
8. How do you plan to develop/apply ML and how you evaluate/compare the performance of the models?
- Since the data that I have is an imbalanced dataset I'd use f1-score, precision and recall along with the ROC-AUC curve to test the model accuracy and then compare them all to obtain the best data model.

-------------------------------------------------------------------------------------------------------------------------------------------------------------
9. What outcomes do you intend to achieve (better understanding of problems, tools to help solve problems, predictive analytics with practicle applications, etc)?
- The main output we aim to achieve by building an ML model for credit card fraud detection is to improve the accuracy and efficiency of detecting fraudulent transactions. The goal is to develop a model that can analyze large amounts of transaction data and identify patterns and anomalies that may indicate fraudulent activity. The output of the model should be a prediction or a probability of whether a transaction is likely to be fraudulent or not.
	In practical terms, a successful ML model for credit card fraud detection should minimize the number of false negatives (fraudulent transactions that are not detected) and false positives (legitimate transactions that are mistakenly flagged as fraudulent). This can help reduce financial losses and the cost of chargebacks, as well as improve customer trust and confidence in the financial system.
	Ultimately, the intended output of an ML model for credit card fraud detection is to provide a reliable and effective solution for detecting and preventing fraud, while still allowing for quick and seamless transactions for legitimate customers
