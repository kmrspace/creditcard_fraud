# Creditcard Fraud Prevention Case Study

Fraudulent activities percolate across industries and business lines, and affect almost every enterprise and individual. Such activities could be described as business transactions that are perpetrated by malicious entities that appear genuine.


 
A 2019 report by the University of Portsmouth estimates that globally, the losses caused due to frauds equate to roughly 6% of the entire world’s GDP, or around $5.127 trillion. An enterprise could face around 3–6% of losses due to fraud, with the highest losses amounting to 10% of the revenue.
 

Enterprises are being severely affected by fraudsters. Losses owing to fraud have increased from an average of 4.57% in the global recession phase of 2007–2008 to 7.15% in 2017–2018. This is a staggering growth of 56.5% in a period of 10 years.

 
The report summarises how existing individuals and businesses are more susceptible to fraud than their predecessors due to:

* Increasing preference of individuals towards unconventional modes of payment, with lesser adherence to common standards;

* Greater complexity of processes and systems, which makes it easier for fraudsters to escape the process without any trace;

* Increase in digital transactions, with less in-person interaction, making it difficult for victims to identify fraudsters; and

* Rapid change in businesses, with necessary safety and control protocol struggling to catch up

Each of these factors gives you hints regarding what enterprises can do to reduce the frequency and severity of fraudulent activities. In this session, you will learn how enterprises aim to detect fraudulent transactions, with a special focus on fraudulent credit card transactions.

### Problem Statement
Finex is a leading financial service provider based out of Florida, US. It offers a wide range of products and business services to customers through different channels, ranging from in-person banking and ATMs to online banking. Over the last few years, Finex has observed that a significantly large number of unauthorised transactions are being made, due to which the bank has been facing a huge revenue and profitability crisis. Many customers have been complaining about unauthorised transactions being made through their credit/debit cards. It has been reported that fraudsters use stolen/lost cards and hack private systems to access the personal and sensitive data of many cardholders. They also indulge in ATM skimming at various POS terminals such as gas stations, shopping malls, and ATMs that do not send alerts or do not have OTP systems through banks. Such fraudulent activities have been reported to happen during non-peak and odd hours of the day leaving no room for suspicion.

 
In most cases, customers get to know of such unauthorised transactions happening through their cards quite late as they are unaware of such ongoing credit card frauds or they do not monitor their bank account activities closely. This has led to late complaint registration with Finex and by the time the case is flagged fraudulent, the bank incurs heavy losses and ends up paying the lost amount to the cardholders.

 

Now, Finex is also not really equipped with the latest financial technologies, and it is becoming difficult for the bank to track these data breaches on time to prevent further losses. The Branch Manager is worried about the ongoing situation and wants to identify the possible root causes and action areas to come up with a long-term solution that would help the bank generate high revenue with minimal losses.

### Project Pipeline
The project pipeline can be briefly summarised in the following steps:

 
* Understanding Data: In this step, you need to load the data and understand the features present in it. This will help you choose the features that you need for your final model.



* Exploratory data analytics (EDA): Normally, in this step, you need to perform univariate and bivariate analyses of the data, followed by feature transformations, if necessary. You can also check whether or not there is any skewness in the data and try to mitigate it, as skewed data can cause problems during the model-building phase.
 

* Train/Test Data Splitting: In this step, you need to split the data set into training data and testing data in order to check the performance of your models with unseen data. You can use the stratified k-fold cross-validation method at this stage. For this, you need to choose an appropriate k value such that the minority class is correctly represented in the test folds.
 

* Model Building or Hyperparameter Tuning: This is the final step, at which you can try different models and fine-tune their hyperparameters until you get the desired level of performance out of the model on the given data set. Ensure that you start with a baseline linear model before going towards ensembles. You should check if you can get a better performance out of the model by using various sampling techniques.

 

* Model Evaluation: Evaluate the performance of the models using appropriate evaluation metrics. Note that since the data is imbalanced, it is important to identify which transactions are fraudulent transactions more accurately than identifying non-fraudulent transactions. Choose an appropriate evaluation metric that reflects this business goal.

 

* Business Impact: After the model has been built and evaluated with the appropriate metrics, you need to demonstrate its potential benefits by performing a cost-benefit analysis which can then be presented to the relevant business stakeholders. 
