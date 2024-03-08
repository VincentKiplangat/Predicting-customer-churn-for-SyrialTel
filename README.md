
# PREDICTIVE ANALYSIS IN CUSTOMER CHURN FOR SYRIATEL USING CLASSIFICATION
![Telecommunication Image](Telecomunication.jpg)

## INTRODUCTION
Syriatel, a telecommunications provider in Damascus, Syria, aims to predict customer churn by analyzing their data. The goal is to forecast if a customer will stop using their services. For telecom companies to grow revenue, attracting new customers while retaining existing ones is crucial. SyriaTel, offering mobile and data services, recognizes that maintaining long-term customer relationships is more effective than constantly seeking new ones. Hence, churn prediction is part of their key strategy.

### OVERVIEW
This project is centred on building a classifier on whether a customer will soon stop doing business with SyriaTel telecommunications company. The project is a binary classification project that aims to develop a model which accurately predicts customers who are most likely to churn and identify the features that are important for predicting customer churn. Thus, advise SyrialTel on ways to reduce customer churn if there is a predictable pattern.

### NOTEBOOK STRUCTURE
1. Business Understanding
2. Data Understanding
3. Data Cleaning
4. Exploratory Data Analysis
5. Data Preparation
6. Modelling
7. Evaluation
8. Conclusion

## 1. BUSINESS UNDERSTANDING
### *Stakeholders and Their Interests:* ###
The key stakeholder impacted by this project is the SyrialTel Telecom Business. Their interest is trying to predict whether there is a predictable pattern to customer churning and possible ways to reduce customer churning.

**Benefits for Syrialtel Customer Churn:**
- *Informed Decision-Making*: SyrialTel can provide its clients with data-driven insights to reduce their losses from customer churn 
- *Tailored Advice*: Customized recommendations based on the unique features of SyrialTel communication.
- *Minimised Churn and thus losses*: SyrialTel can know the do's and don't to minimise the customer churn rate which in turn leads to money loss reduction because of customers who do not stick around. 

### OBJECTIVES ###
#### - Main Objective: ####
The main objective of this project is to build a predictive classifier that assists SyrialTel Telecommunication company in determining if there is a predictable pattern to customer churning. The classifier aims to predict the potential predictable patterns of customer churning.

#### - Specific Objectives ####

i). Identify Key Factors Influencing customer churning from the Telecommunication company.

ii). Evaluate the classifier performance for the classification problem using metrics such as accuracy, precision, recall, F1 score, and confusion matrix to assess the effectiveness of the model.

iii). Provide Actionable Recommendations to SyrialTel company to reduce money lost because of customers who do not stick around.


## 2.DATA UNDERSTANDING
-The data utilized for this project has been sourced from [Kaggle](https://www.kaggle.com/becksddf/churn-in-telecoms-dataset)

- The dataset contains 3333 entries and 21 columns, including information about the state, account length, area code, phone number, international plan, voice mail plan, number of voice mail messages, total day minutes, total day calls, total day charge, total evening minutes, total evening calls, total evening charge, total night minutes, total night calls, total night charge, total international minutes, total international calls, total international charge, customer service calls and churn.

#### **Summary of Features in the Dataset**
Each entry in the dataset represents a customer, and the attributes describe different aspects of their account and usage.

| Attribute                | Description                                                                                     |
|--------------------------|-------------------------------------------------------------------------------------------------|
| State                    | The state in which the customer resides.                                                       |
| Account Length           | The number of days the customer has had the account.                                             |
| Area Code                | The area code of the customer's phone number.                                                    |
| Phone Number             | The customer's phone number.                                                                    |
| International Plan       | A boolean indicating whether the customer has the international calling plan (True or False).   |
| Voice Mail Plan          | A boolean indicating whether the customer has the voicemail plan (True or False).               |
| Number Vmail Messages    | The number of voicemail messages the customer has sent.                                          |
| Total Day Minutes        | The total number of minutes the customer has been in calls during the day.                        |
| Total Day Calls          | The total number of calls the customer has made during the day.                                   |
| Total Day Charge         | The total amount of money charged by the telecom company for calls during the day.               |
| Total Eve Minutes        | The total number of minutes the customer has been in calls during the evening.                    |
| Total Eve Calls          | The total number of calls the customer has made during the evening.                               |
| Total Eve Charge         | The total amount of money charged by the telecom company for calls during the evening.           |
| Total Night Minutes      | The total number of minutes the customer has been in calls during the night.                      |
| Total Night Calls        | The total number of calls the customer has made during the night.                                  |
| Total Night Charge       | The total amount of money charged by the telecom company for calls during the night.             |
| Total Intl Minutes       | The total number of minutes the user has been in international calls.                             |
| Total Intl Calls         | The total number of international calls the customer has made.                                     |
| Total Intl Charge        | The total amount of money charged by the telecom company for international calls.                 |
| Customer Service Calls   | The number of calls the customer has made to customer service.                                     |
| Churn                    | A boolean indicating whether the customer terminated their contract (True or False).              |

### Data Types: ###
The data types include categorical, numerical and boolean data.
- Categorical Data: These are variables that represent categories or groups. Examples include 'state', 'phone number', 'international plan', and 'voice mail plan'.

- Numerical Data: These are variables that represent numerical values. This includes both integer and floating-point numbers, such as 'account length', 'area code', 'number vmail messages', 'total day minutes', 'total day charge', 'total eve minutes', 'total eve charge', 'total night minutes', 'total night charge', 'total intl minutes', 'total intl charge', 'total day calls', 'total eve calls', 'total night calls', 'total intl calls', and 'customer service calls'.

- Boolean Data: This data type represents variables that can have only two possible values, typically 'True' or 'False'. In this dataset, the 'churn' column is boolean, indicating whether a customer has churned ('True') or not ('False').

### Independent and Dependent variables ###
The dataset contains 21 features and of the 21:
- The dependent variable is **'Churn'**
- The independent variables are the remaining 20 features.

## 3.DATA CLEANING AND PRE-PROCESSING
The data was loaded and assessed after which some EDA was performed for better understanding. There were no missing values and no duplicates. All of the categorical features were changed for one hot encoding to be performed so that the data could be fit for modelling. The numerical features were also normalised to equalize the features and improve model performance. 

## 6.MODELING
## 7.EVALUATION
## 8.CONCLUSION
