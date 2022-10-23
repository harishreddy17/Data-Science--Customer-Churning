
# CUSTOMER CHURN PREDICTION




## PURPOSE: 
There is a bank who wants to retain their existing customers who may churn but for that bank has to know which customer has highest probability of leaving company and which customers has Lowest probability of leaving the company.
The rate of churning is very important for bank as churning play’s important role to get funding from big investors.
For that bank has to build machine learning model which can predict whether a particular customer will churn or not.

## WORKING:
I have dataset of 10,000 rows with 13 features and 1 target variable. Every row tells us different customer details and whether they have churned or not.
First, I have trained model to pre
dict if a customer churn or not. For that I did EDA (Exploratory data analysis) to get important features and scaling to normalise the data.
Firstly, I have trained and tested data on different algorithms. Then I have chosen the model which gave the best accuracy.


## TOOLS USED:
Pandas: Pandas is a software library written for the Python programming language for data manipulation and analysis

NumPy: NumPy is a library for the Python programming language, adding support for large, multi-dimensional arrays and matrices, along with a large collection of high-level mathematical functions to operate on these arrays

Seaborn: Seaborn is a library that uses Matplotlib underneath to plot graphs. It will be used to visualize random distributions 

Sci-kit learn: Sci-kit Learn is a free software machine learning library for the Python programming language.[3] It features various classification, regression and clustering algorithms including support-vector machines, random forests, gradient boosting, k-means and DBSCAN, and is designed to interoperate with the Python numerical and scientific libraries NumPy and SciPy

Some of the algorithms I have used:

1.	KNN: The k-nearest neighbours’ algorithm, also known as KNN or k-NN, is a non-parametric, supervised learning classifier, which uses proximity to make classifications or predictions about the grouping of an individual data point. While it can be used for either regression or classification problems.
2.	Logistic Regression: Logistic regression is a classification algorithm. It is used to predict a binary outcome based on a set of independent variables.
3.	SVM (Support vector Machine): SVM or Support Vector Machine is a linear model for classification and regression problems. It can solve linear and non-linear problems and work well for many practical problems.
4.	Decision tree: A decision tree is a type of supervised machine learning used to categorize or make predictions based on how a previous set of questions were answered
5.	Random Forrest: The random forest is a classification algorithm consisting of many decisions trees. It uses bagging and feature randomness when building each individual tree to try to create an uncorrelated forest of trees whose prediction by committee is more accurate than that of any individual tree


## CODE:
![image](https://user-images.githubusercontent.com/89855623/197407959-9a150056-2811-4e40-918f-85d3b8b3c097.png)
![image](https://user-images.githubusercontent.com/89855623/197408023-69a19586-149b-4175-a18c-a728961095db.png)
![image](https://user-images.githubusercontent.com/89855623/197408048-0f05565c-50cf-4a29-a31e-ec4ab4848af9.png)
![image](https://user-images.githubusercontent.com/89855623/197408069-9a7fb742-ba5b-4490-be60-897b3524d4bd.png)
![image](https://user-images.githubusercontent.com/89855623/197408090-82ab0f79-9f3a-4f59-96cb-5b62010d4a39.png)
![image](https://user-images.githubusercontent.com/89855623/197408111-982fb130-7364-4bd0-8294-6107366d08a5.png)
![image](https://user-images.githubusercontent.com/89855623/197408126-09fa59e1-d6d0-4f23-b1f5-8fa4409a942e.png)

SCALING OF CATOGERICAL AND NUMERICAL FEATURE:

![image](https://user-images.githubusercontent.com/89855623/197408161-0652ea6a-f11a-4c0d-b93b-e70e27c5eff9.png)
![image](https://user-images.githubusercontent.com/89855623/197408173-88e31c7c-dfdc-4f58-a4db-67545136621a.png)

MODEL TESTING:

Below we are finding the accuracy for different algorithms by training and testing of model. I have to choose the model that gives best accuracy among others.
Models used for Testing:
1.	KNN
2.	Logistic Regression
3.	Support vector Machine
4.	Decision Tree
5.	Random Forest

![image](https://user-images.githubusercontent.com/89855623/197408215-e4c4cf5e-75cc-4e42-81f4-3c49905f5828.png)
![image](https://user-images.githubusercontent.com/89855623/197408250-95a761ff-1ec8-4d23-a043-8e8f3d34d12c.png)
![image](https://user-images.githubusercontent.com/89855623/197408272-aef2488c-9b9e-4c96-b876-d3c6cb6c3c09.png)
![image](https://user-images.githubusercontent.com/89855623/197408287-60f31f81-2711-4eb4-84a7-a6e06dd55c79.png)
![image](https://user-images.githubusercontent.com/89855623/197408322-e86c121b-8305-441c-a930-04784e89fee9.png)



## ACCURACY:
![image](https://user-images.githubusercontent.com/89855623/197408347-bcb24982-2a15-4990-943f-863e09d7b2dd.png)

## CONCLUSION:
The Conclusion we got from this project is I have used my machine learning algorithms KNN, Logistic Regression, SVM, Decision tree and Random Forest. I have trained and tested data in all the algorithms. And got different accuracy from different model. Random forest gave the best accuracy among all the other algorithms. So, I chose random forest as perfect model for band to predict the customer churning. 
