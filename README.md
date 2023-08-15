Title that recommends an action
Subtitle describing the analysis
Author: Lidivine Kengne 
Business problem:
The business problem here is improve outlet sale
Data:
Sale prediction 2023 from project data coding Dojo: with 8523 rows and 12 columns
Methods
Data preparation 
Load and inspect data 
Clean data : duplicate , identify missing value , find and fix any inconsistent data 
Exploration data 
Results
Here are examples of how to embed images from your sub-folder
Exploratory Data Analysis
During the exploratory data analysis, a boxplot and histogram was visualized for each numeric datatype column.
Also, a barplot was visualized for each categorical column.
This gave a good baseline for all of the numeric and categorical columns for univariate EDA.

This histogram shows that we have more sale on OUT027.
Explanatory Data Analysis
To visualize the data for explanatory purposes, bar graphs were chosen and one linegraph was chosen.
The bargraphs were chosen to show how the categories compare to each other. 
Finally, a linegraph was chosen to show the trend of sale 










The shop sell more fruits and vegetable 14.46%


Machine Learning Using the Following Models:
Linear Regression Model
Random Forest Regressor Model
Tuned Random Forest Regressor Model Models Evaluated & Results Linear Regression Model (Testing Set):


Models Evaluated & Results
Linear Regression Model (Testing Set):
R^2: 0.5671
MAE: 804.1117
RMSE: 1095.8843


Random Forest Regressor Model (Testing Set):
R^2: 0.5587
MAE: 767.1537
MSE: 1,217,517.82106161
RMSE: 1103.4119


Tuned Random Forest Regressor Model (Testing Set):
MAE = 738.360
MSE = 1,118,064.645
RMSE = 1,057.386
R^2 = 0.595


The Final Model Chosen was a Random Forest Regressor Model with the n_estimators tuned to 50.
For the testing set on the model, 56.3% of the variance in y was explained by x.
The Mean Absolute Error was off by about $31,998.94.
The Mean Squared Error was $2,044,264,641.83.
The Root Mean Squared Error had a calculation of $45,213.55.




Tuned Random Forest Model Observations
Using this model to make predictions about the best outlet sale to choose to earn the most money would not be a very reliable. Considering the previous regression metrics from how the model performed, there is a disparity between the R^2 score and also the Root Mean Squared Error that cannot be ignored.
Here, we see the best results as far as the regression metrics and the model's performance.
This model still has some bias. However, this model has the best performance on the testing set.
For the R^2 score 59.3% of the variance is explained.
For the MAE the testing score is off by about 738.360
Overall Recommendation
Data Science Insights


For those who have an interest in Data Science:


Data Analytics Leads & Principal Data Engineers earn the most amount of money. However, this are usually not entry level careers and I would recommend going through a program, like Coding Dojo, where you can earn your data science certificate and then map out your career to these positions.


Data Engineers & Data Scientists have the most 100% remote positions. So, if you are wanting to work from home, or work from anywhere in the world, choosing one of the top five remote positions would be a good choice to build your career upon.


Lastly, the trend for the last three years show that data science and related fields are increasingly earning more money each year. So, choosing a career in one of these fields can be very lucrative.


Model Performance


Overall, the best model is definitely the tuned Random Forest Regressor Model. There was still some bias in the model, but by far it outperformed the linear regression model.


Limitations & Next Steps 
From here, a student could use the insights from the visuals on how to tailor their path for their career. As mentioned before, Coding Dojo has a fantastic program that prepares inspiring data scientists for the field of data science.
For Further Information For any additional questions, please contact:
Lidivine Kengne: lidiviaKeng@gmail.com
