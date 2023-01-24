# CHURN PREDICTION


**BUSINESS OBJECTIVE** - In the telecom industry, customers can choose from multiple service providers and actively switch from one operator to another. In this highly competitive market, the telecommunications industry experiences an average of 15-25% annual churn rate. Given the fact that it costs 5-10 times more to acquire a new customer than to retain an existing one, customer retention has now become even more important than customer acquisition.
For many incumbent operators, retaining high profitable customers is the number one business goal.

To reduce customer churn, telecom companies need to predict which customers are at high risk of churn.

Here we are predicting if the customer will switch to a different operator or not based on various factors.

Visalized the effect of multiple factors like tenure, total amount, number of dependents etc on the churn probablity of the customer.





![image](https://user-images.githubusercontent.com/24591039/214369892-eedcd3d2-0280-4c07-91b4-671b2354d111.png)

Fig 1 : Corelation of various vactors on the churn probablity

Performed recursive feature elimination and analysed the vif value to reduce the number of features required for prediction

![image](https://user-images.githubusercontent.com/24591039/214372540-aa5c1904-fa4d-4d56-b89e-7ff2ce42102a.png)

Fig 2 : False positive rate ~ True positive rate for various probablity thresholds


![image](https://user-images.githubusercontent.com/24591039/214372733-10fd7039-2415-4b80-b203-cdc82b12f6e3.png)

Fig 3 : Analysing metrices to find the optimum threshold for this usecase
