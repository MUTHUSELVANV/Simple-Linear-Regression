# Simple-Linear-Regression
Performed Simple Linear Regression on salary dataset. The ML algorithm can predict salary based on the years of experience. The python code approaches Linear Regression by performing all the 6 jars of ML.
- 1st JAR: Data - 
  - Data Cleaning:
    - Import Data
    - Check for any outliers (iqr method)
    - Check for missing value, check for data type of each column of dataframe
    - Check for Linear Relationship between each Feature and Target
    - Checking for duplicates in the Dataset
  - Splitting:
    Split all the features and target dataset into two: Train Data & Test Data
    we would get 4 subsets:
      - Features - Training Dataset
      - Features - Testing Dataset
      - Target - Training Dataset 
      - Target - Testing Dataset
    Have allocated 75% of data for Training and 25% of data for Testing
- 2nd JAR: Task - 
  Linear Regression comes under Supervised learning since we are predicting a target.
  From sklearn library, under linear_model module, we are importing LinearRegression
  Then we are assigning an object to LinearRegression
  Later, we fit the object on the training dataset
- 3rd JAR: Model -
  We arrive at a mathematical formula containing features and target from the calculated parameters 
- 4th JAR: Loss - 
  We are calculating Mean Squared Error on test data to numerically understand how well the model works.
- 5th JAR: Learning -
  Generally, to find the best parameters which could fit the model, ML algorithm performs a method called gradient descend.
  This Jar has been performed in the 3rd Jar itself. So, there is no specific code to perform gradient descent.
- 6th JAR: Evaluation Metric -
   We are calculating an evaluation metric called r-squared which shows how well the data fit the regression model (the goodness of fit).
   
Once we are with a good model, we can predict the Salary of an employee based on the Year of Experience.
It is also interesting to note that the model is limited to predict salary only if the Years of Experience lies inside the three sigma interval.
