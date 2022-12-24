
# Credit Card Fraud Detection

The Credit Card Fraud Detection project is used to identify whether a new transaction is fraudulent or not by modeling past credit card transactions with the knowledge of the ones that turned out to be fraud. We will use various predictive models to see how accurate they are in detecting whether a transaction is a normal payment or a fraud.

# Problem Statement

In this project we want to identify fraudulent transactions with Credit Cards. Our objective is to build a Fraud detection system using Machine learning techniques. In the past, such systems were rule-based. Machine learning offers powerful new ways.

The dataset is taken from the Kaggle Website website and it has a total of 2,84,807 transactions, out of which 492 are fraudulent. Since the dataset is highly imbalanced, so it needs to be handled before model building.
The transactions were made by european credit card holders in September 2013. Our objective of this project is to fit the dataset into our machine learning models to predict precisely while dealing with the highly unbalanced issue of this dataset

# Defining Fraud

Credit card fraud is any dishonest act and behaviour to obtain information without the proper authorization from the account holder for financial gain. Among different ways of frauds, Skimming is the most common one, which is the way of duplicating of information located on the magnetic strip of the card. Apart from this, the other ways are:

* Manipulation/alteration of genuine cards

* Creation of counterfeit cards

* Stolen/lost credit cards

* Fraudulent telemarketing

# Techniques used in the project

* Machine learning techniques:

    * Random Forest
    A Random Forest is essentially a collection of Decision Trees. A decision tree is built on an entire dataset, using all the features/variables, whereas a random forest randomly selects observations (rows) and specific features/variables to build multiple decision trees from and then averages the results. After a large number of trees are built using this method, each tree "votes" or chooses the class, and the class receiving the most votes by a simple majority is the "winner" or predicted class.

# Variable Description

* Time: The seconds elapsed between each transaction and the first transaction in the dataset
* V1 to V28: Principle components
* Amount: Transaction amount in Euro
* Class: The actual classfication classes (0 = Normal transaction, 1 = Fraud) 

# Project Pipeline

The project pipeline can be briefly summarized in the following four steps:

* Data Understanding: Here, we need to load the data and understand the features present in it. This would help us choose the features that we will need for your final model.
* Exploratory data analytics (EDA): Normally, in this step, we need to perform univariate and bivariate analyses of the data, followed by feature transformations, if necessary. For the current data set, because Gaussian variables are used, we do not need to perform Z-scaling. However, you can check if there is any skewness in the data and try to mitigate it, as it might cause problems during the model-building phase.
* Train/Test Split: Now we are familiar with the train/test split, which we can perform in order to check the performance of our models with unseen data. Here, for validation, we can use the k-fold cross-validation method. We need to choose an appropriate k value so that the minority class is correctly represented in the test folds.
* Model-Building/Hyperparameter Tuning: This is the final step at which we can try different models and fine-tune their hyperparameters until we get the desired level of performance on the given dataset. We should try and see if we get a better model by the various sampling techniques.
* Model Evaluation: We need to evaluate the models using appropriate evaluation metrics. Note that since the data is imbalanced it is is more important to identify which are fraudulent transactions accurately than the non-fraudulent. We need to choose an appropriate evaluation metric which reflects this business goal.


##  About Me
I'm M.Sc student in Computer Science at Tehran-Polytechnic (AUT) and interested research in Machine Learning ,Natural Language Processing and Data Science.


## 🔗 Links
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/fatemeh-arab/)


