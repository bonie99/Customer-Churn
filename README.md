# Customer-Churn
# intruduction
- SyriaTel, a telecommunications company, aims to predict customer churn by analyzing their data to forecast whether a customer might discontinue their services. For telecom businesses, sustaining growth requires balancing the acquisition of new customers with retaining current ones. SyriaTel, which provides mobile and data services, understands that fostering long-term customer loyalty is more cost-effective than focusing solely on acquiring new customers while losing existing ones. As a result, predicting churn has become a vital part of their strategic approach.
# OVERVIEW
- This project focuses on creating a binary classification model to determine whether a customer is likely to stop using SyriaTel's services. The goal is to build an accurate predictive model that identifies customers at risk of churning and highlights the key factors influencing this behavior. This information can then be used to provide actionable recommendations to SyriaTel to reduce customer attrition if discernible patterns emerge.
# Notebookstructure
Business Understanding
Data Understanding
Data Cleaning
Exploratory Data Analysis
Data Preparation
Modelling
Evaluation
Conclusion
# Business Understanding
- problem stament: SyriaTel, a leading telecom provider, is experiencing rising churn rates due to declining customer loyalty. The company aims to identify at-risk customers and implement strategies to retain them proactively
- key stakeholders:Business Analysts who will Focused on analyzing churn patterns and their impact on revenue, providing actionable insights and Executive Team who are
- Responsible for developing strategies to enhance customer retention and driving business growth.
# Data understanding
- the dta set  used for this project was obtained from kagle and  it has 3333 rows and 21 columns featuring details such as the customer's state, account duration, area code, phone number, and subscription plans. It also includes usage data like the number of voicemail messages, total minutes and calls during different times of the day (day, evening, night), associated charges, international call metrics, and the number of customer service interactions. The target variable indicates whether the customer has churned.The data type in this dataset  include both numerical and categorical data type.
- The dataset provided by SyriaTel includes important factors for analyzing customer behavior and predicting churn, such as subscription types and call usage data. The 'Churn' column indicates whether a customer has left the service or not. This dataset serves as a basis for creating a predictive model to identify churn risks and improve retention strategies, aligning with the goal of reducing customer churn.
# data cleaning and preparation
- The data was imported and evaluated, followed by exploratory data analysis (EDA) for deeper insight. There were no missing values or duplicate entries. All categorical features were transformed to allow for one-hot encoding, making the data suitable for modeling. Additionally, the numerical features were normalized to standardize them and enhance model performance.S
# data visualization
![alt text](images/image.png)
![alt text](images/image1.png)
![alt text](images/image2.png)
# modelling
- The dataset was divided into training and test sets, with the training set used for model fitting and the test set for model evaluation. A baseline model was developed using Logistic Regression, while additional models included  Decision Trees and Random Forest. The modeling process involved optimizing performance through hyperparameter tuning and feature importance selection to identify the best-performing model.
# Evaluation
- from the difrent model i used that is logistic regretion,decision tree  and random forest model i found that  the best model was  random forest model with roc score:0.92
# conclusion
## Recommendations
- 1.Improve on customer services: This may include services such as wait time and customer satisfaction.
- 2.Introduce customised and affordable call plans for boh day and night calls
- 3.Proactive Customer Outreach: Regularly reach out to customers to gather feedback and address concerns
- 4.Security Measures: Implement stringent security measures ensure customer privacy and data protection.