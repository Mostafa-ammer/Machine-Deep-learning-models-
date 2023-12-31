# TELECOM CUSTOMER CHURN Defination
Telco customer churn refers to the loss of subscribers in telecommunications,
either through service cancellations or switching to other providers, posing a
significant challenge by leading to revenue loss and impeding potential growth

# OBJECTIVE
1- Implement a set of machine and deep learning models, compare the results, and choose the best model.

2- Address the problem of imbalanced datasets using different techniques.

3- Create visualizations and extract a set of insights to understand the reasons that led users to leave the company.

# DataSet 
The dataset contains twenty one columns (independent variables) that indicate the characteristics of the clients of a fictional telecommunications corporation. The Churn column (response variable) indicates whether the customer departed within the last month or not. The class No includes the clients that did not leave the company last month, while the class Yes contains the clients that decided to terminate their relations with the company.


# DATA EXPLORATION

1- The percentage of male in data is :50.48%  and The percentage of female in data is :49.52% 

2- The percentage of Customers who their age less than 65 is :83.79%  and The percentage of Customers who their age less than 65 is :16.21% 

3- The percentage of customers that have Dependents :29.96%  , The percentage of customers that have no Dependents :70.04% 

4- The percentage of customers using phone services is : 90.32% and The percentage of customers not using phone services is : 9.68% 

5- The percentage of customers have left the company after one year of usage is : 31.04 %  and The percentage of customers have left the company after two year of usage is : 45.58 %

6- The percentage of customers have left the company after three year of usage is : 57.39 % and The percentage of customers have left the company after four year of usage is : 68.21 %


# WHY THEY LEFT..

1- suggests that having a partner may contribute to greater customer stability within the company because 17% of customers who do not have partners left the company, out of the total 26% of customers who left

2- The company should review its phone services as 24% of users who utilize these services have left out of the total 26% of customers who left

3- The company should investigate its internet services, especially for customers using 'Fiber optic', as 18.4% of users with this service left the company out of the total 26% who left

4- The company should emphasize the importance of security services to customers, as we've observed that 21% of customers who do not use security services left the company

5-  The company should emphasize the importance of device protection services to customers, as we've observed that 17.2% of customers who do not use device protection services left the company

# Models 

1- Deep Learning Model : I built a deep neural network with an input layer of 26 nodes and ReLU activation, followed by two hidden layers with 30 and 15 nodes, both using ReLU activation, and an output layer with 1 node and sigmoid activation for binary classification .

2-Enhancement of Deep Learning Model: I enhanced the performance of the deep learning model by addressing the imbalance in the dataset using techniques such as oversampling, undersampling, and SMOTE.

3- Machine Learning Model : I constructed a set of machine learning models, including logistic regression, KNN, SVM, Decision Tree, and Random Forest.

# Result 

1- The first trial achieved an overall accuracy of 78%, and the model demonstrated good generalization on unseen data. However, precision, recall, and F1-score for class 1 were suboptimal due to dataset imbalance, with class 1 being the minority class. To address this issue, I enhanced the model's performance by employing various imbalance-solving techniques, including Oversampling, Undersampling, SMOTE, and Ensemble methods.

2- After applying undersampling, we observed improvements in recall and F1-score for class 1; however, the overall accuracy has not improved and decrease to 76%.

3- After applying Oversampling, we observed improvements in recall , precision and F1-score for class 1; and the overall accuracy improved and increase to 87%.


4- After applying SMOTE technique, we observed improvements in recall , precision and F1-score for class 1; and the overall accuracy improved and increase to 85%.

5- After applying Ensemble methods, we found that the model did not improve, and the overall accuracy decreased to below 78%.

6- I applied a set of machine learning models with tuning  ; (DecisionTree: Accuracy - 0.7904) - (RandomForest: Accuracy - 0.8296) - (KNeighbors: Accuracy - 0.8049) - (SVM: Accuracy - 0.8170)

7- We found that the results improved after addressing the imbalance issue, and the best model is the deep learning model with imbalance resolution using oversampling. The overall accuracy reached 87%.









