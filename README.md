# **Project Title: Churn Prediction**

### **Problem Statement:**

The goal of this project is to develop a machine learning model that can predict whether a customer will leave the bank based on various features provided in the dataset. This prediction will help the bank in identifying customers who are at risk of leaving, allowing them to take proactive measures to retain those customers.

Dataset:
The dataset contains information about bank customers, including their credit score, location, gender, age, tenure, balance, number of products, credit card status, activity status, estimated salary, and whether or not they have exited the bank.

Approach:
1. Data Preprocessing: Clean the dataset by handling missing values, encoding categorical variables, and scaling numerical features if necessary.
2. Exploratory Data Analysis (EDA): Analyze the distribution of each feature, identify correlations between features and the target variable (Exited), and visualize relationships using plots.
3. Feature Engineering: Create new features or transform existing ones to improve model performance.
4. Model Building: Train various machine learning models such as logistic regression, decision trees, random forests, and gradient boosting classifiers.
5. Model Evaluation: Evaluate the performance of each model using metrics like accuracy, precision, recall, F1-score, and ROC AUC score. Select the best-performing model for deployment.
6. Model Deployment: Deploy the selected model in a production environment to make real-time predictions on new data.

The ultimate objective is to develop a reliable churn prediction model that can assist the bank in reducing customer attrition and improving overall customer satisfaction and retention.

#### **Dataset**

- RowNumber: Corresponds to the record (row) number and has no effect on the output.
- CustomerId: Contains random values and has no effect on customer leaving the bank.
- Surname: The surname of a customer has no impact on their decision to leave the bank.
- CreditScore: Can have an effect on customer churn, as a higher credit score is associated with lower likelihood of leaving the bank.
- Geography: A customer’s location can affect their decision to leave the bank.
- Gender: Explore whether gender plays a role in customer churn.
- Age: Older customers are less likely to leave the bank compared to younger ones.
- Tenure: Number of years the customer has been a client of the bank; older clients are typically more loyal.
- Balance: Higher account balances indicate lower likelihood of leaving the bank.
- NumOfProducts: Number of products purchased through the bank.
- HasCrCard: Denotes whether the customer has a credit card, which may affect churn.
- IsActiveMember: Active customers are less likely to leave the bank.
- EstimatedSalary: Customers with lower salaries are more likely to leave the bank.
- Exited: Binary indicator of whether the customer left the bank (0=No, 1=Yes).

- ### **Summary:**

This project aimed to develop a machine learning model to predict customer churn for a bank based on various customer attributes. The dataset provided included features such as credit score, geography, gender, age, tenure, balance, number of products, credit card status, activity status, and estimated salary. Through comprehensive exploratory data analysis (EDA), it was observed that factors such as age, gender, tenure, balance, number of products, credit card status, and activity status played significant roles in predicting customer churn.

Insights from the EDA revealed that certain demographic groups, such as younger customers and those with lower account balances, were more likely to churn. Additionally, customers who were inactive or had fewer products were also at higher risk of leaving the bank. Geographic location also appeared to influence churn rates, with certain regions exhibiting higher rates of customer attrition.

A simple ANN was trained and evaluated using various classification algorithms, including logistic regression, decision trees, random forests, and gradient boosting classifiers. The selected model achieved an accuracy of approximately 86% on both the training and test sets, indicating robust performance in predicting customer churn. However, further analysis of the model's precision, recall, and F1-score revealed disparities in its ability to correctly identify churned customers, particularly in terms of recall for class 1 (customers who left the bank).

### **Conclusion:**

In conclusion, the developed machine learning model demonstrates promising performance in predicting customer churn for the bank. By leveraging insights gained from exploratory data analysis and utilizing advanced classification algorithms, the model provides valuable predictions that can assist the bank in identifying at-risk customers and implementing targeted retention strategies. However, there is room for improvement, particularly in accurately identifying churned customers to reduce false negatives and enhance the model's overall predictive power. Moving forward, continued refinement and optimization of the model, along with ongoing monitoring and validation against new data, will be essential to maintain its effectiveness in supporting the bank's efforts to mitigate customer churn and enhance customer retention.
