# Bank Customer Churn Predictive Modeling


We are developing a customer churn predictive modeling by applying weighted artificial neural network. With unbalanced data samples, we applied different weights to loss function to concentrate on churn customer.  Overall, we found that artificial neural network with weights achieved the highest accuracy and a good balance of recall and precision.  We also validate our algorithm using K fold cross validation to evaluate robustness of our models. Overall, we are comfortable with our algorithm. 

Steps for the implementation:

1.	Integrated data from multiple AWS SQL tables.  

2.	Preprocessing data and visualize data to understand relationships of features to customer churn rate. 

3.	Use logistic regression and correlation to select and rank feature importance

4.	Feature engineering of continuous variables and variables which don’t add much values.  

5.	Time to churn analysis using churn data.  

6.	Given the imbalanced nature of our sample data, we applied weighted ANN algorithm with adam adaptive learning rates. We effectively achieved 87% of accuracy and 70% of recall.  
7.	Overall, we achieved accuracy of 87% and balance of recall and precision on both training and test set. 


