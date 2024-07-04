# stack_overflow_salary_prediction
<h1 id= "top doc"> Description </h1>

---




1. General info

Software developers are in high demand, and salaries can vary depending on several factors, including experience, location, and skillset. As a result, it can be challenging for software developers to know what to expect when negotiating their salaries. In this write-up, we will present a salary predictor web app using Stack Overflow’s developer survey dataset, which contains information about developers’ salaries and various factors that could influence them.

Data Collection and Preparation: Stack Overflow conducts an annual developer survey that collects data on various aspects of developers’ work, including demographics, employment status, education, experience, and salary. We will use the 2021 survey dataset, which is available on their website.

Link for this dataset:
[dataset](https://insights.stackoverflow.com/survey) 

Data Preprocessing:

Before we can build the model, we need to preprocess the data to prepare it for training. The Stack Overflow dataset contains information about software developers’ skills, experience, location, and salary. We will clean the dataset by removing any missing or irrelevant data. We will also convert categorical variables into numerical values using Label encoder.

Model Building:

We will use three different algorithms to build our salary predictor model:

Linear Regression: We will start by building a simple linear regression model. Linear regression is a straightforward algorithm that uses a linear equation to predict the target variable. We will use the scikit-learn library to implement this algorithm.
Random Forest: Random Forest is a more complex algorithm that uses multiple decision trees to make predictions. It is known for its high accuracy and ability to handle large datasets. We will use the scikit-learn library to implement this algorithm.
Decision Trees: Decision Trees are another popular algorithm for regression problems. They are easy to interpret and can handle both categorical and numerical data. We will use the scikit-learn library to implement this algorithm. 

2. Used methods

we used ***Grid search*** to find the best parameters of the most famous **XGBoost** algorithm, we also used the following methods and libraries

- Pycaret

- XGBoost



# Highlights



 ```python

from pycaret.regression import *
s = setup(data = df,target = 'Salary',session_id = 85)

 ```





- link to some where <a href= "#top doc"> go to up </a>
