### Comparison-of-Automobile-Insurance-Fraud-Detection-of-Decision-Tree-KNN-SVC-Neural-Network ###

* As an actuary one of our duties is to minimize the occurrence of insurance claim fraud. So, we are using machine learning methods that are used to predict the data of prospective insurance policy holders in order to find out whether there is a possibility of fraudulent insurance claims. 

* We use 4 methods to predict insurance claim fraud as follows :
    - Decision Trees
    - K-Nearest Neighbors
    - Support Vector Machines
    - Neural Network
    
* Feature importance refers to techniques that assign a score to input features based on how useful they are at predicting a target variable.
![image](https://user-images.githubusercontent.com/91950433/218220422-a7564968-c7d5-420a-9d51-768ff11fbb6d.png)

![image](https://user-images.githubusercontent.com/91950433/218220466-929969f4-b635-4b37-b74f-48d6b085383e.png)

* First, we choose 3 features namely claim_amount, months_since_last_claim, and annual_income. We choose these three features because they have the top 3 importance score, which means the most useful at predicting a target variable.

* In the revision step, we add more features to 4, 5, and all features except cust_ID (16 features) and then reduce it to 2 and 1 feature and finally compare the accuracy, AUC, and running time to find the most accurate and efficient model.

* Model evaluation
![image](https://user-images.githubusercontent.com/91950433/218220302-fce9d905-db27-42cb-8907-1b62403fc03a.png)

* Decision Tree
![image](https://user-images.githubusercontent.com/91950433/218220819-45c8dcc2-07f0-43d2-8812-e39256c9f09d.png)

* K-Nearest Neighbor
![image](https://user-images.githubusercontent.com/91950433/218220888-47071401-5290-46ac-988a-a3704309c629.png)

* Support Vector Machine
![image](https://user-images.githubusercontent.com/91950433/218220914-96f3fa2d-0085-4fdf-8a63-c29252ed34ea.png)

* Neural Network
![image](https://user-images.githubusercontent.com/91950433/218220962-03e292af-02fe-4ba0-b725-8387add1e79e.png)

* Comparing 4 graph above we find the best model with optimum accuracy and efficiency which is using K-Nearest Neighbors with 16 features selected. 
![image](https://user-images.githubusercontent.com/91950433/218220210-b2b8467f-6fc7-4817-87ff-075d2541c793.png)



