# Data Science & AI (CZ1115)-Project
Data Science Project using the Olist dataset from kaggle

# Description
This is a small Data Science university project done on the the Olist Market Dataset in a group of 3.

<h3> The Team Consist of: </h3>
<ol> 
  <li>Terrence</li>
  <li>[Yan Shiun](https://github.com/ys-c)</li>
  <li>[Titus](https://github.com/titim789)</li>
</ol>

# How we approached this project
<h3> Step 1: Picking Dataset</h3>
We were given a five different datasets with the freedom to conduct our analysis on either one. We divide and conquer studying different datasets individually within a span of 3 days to look for the dataset we find the most interesting. We then came together and discuss our findings and unanimously settled for the Olist Market dataset from Kaggle.
<h3> Step 2: Data Exporation</h3>
In this step we created graphs, charts and even plotted on the map of Brazil of based on the amount of purchases made from the city. We did this step so as to better understand the data that we are handling and create a strong foundation of the dataset to tackle our problems we would later define.
<h3> Step 3: Problem Formulation </h3>
Based on all the data we have explored, we decided to use the data to predict/project sales of a seller based given 6 months of sales from the seller.
<h3> Step 4: Data Preparation </h3>
According to our problem and the data we have explored, we narrowed down those variables which we felt were correlated to the sales of the seller This includes, number of photos posted by the seller of all time, the ratings of a seller, the number of product sold by the seller and the number of days the seller was on the platform. Since we do not have this data in hand, we had to do some data preparation.
<h3> Step 5: Statistical Description </h3> 
With the cleaned data we then do some statistical plots to visualise the the correlation between the varibles we have and the sales.
<h3> Step 6: Exploratory Analysis </h3>
In this section, we want to observe the correlation of the 5 selected variables with Total Sales. So that we can consider which variables are suitable as a preditors of total sales.
Update: We learnt that even if a variable has a bad correlation with the variable to predict, we can still include it as it would still help the models just not as much as those highly correlated varibles.
<h3> Step 7: Machine Learning </h3>
We split the dataset into 3 (Training, Validation & Testing) splitting them by time period. We tried to create a few models as we are not very sure which is the best to predict the Sales.
<h5> We Used </h5>
<ol>
  <li>Linear Regression</li>
  <li>Random Forest Regression (4 Forests)</li>
  <li>Log Transformed Linear Regression</li>
</ol>
<h3> Step 8: Using our Model on the Test Data </h3>
In this step we used the test data to guage how good our model was.

# Build With:
<ol>
  <li> Jupyter </li>
  <li> Python </li>
