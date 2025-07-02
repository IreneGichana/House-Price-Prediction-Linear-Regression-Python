# Linear-Regression
Linear regression is a supervised learning technique that models the relationship between a dependent variable and one or more independent variables. This project focuses on implementing a simple linear regression model using Python to predict house prices based on features such as area, number of bedrooms, and the age of the house. The goal of the project is to understand how house characteristics affect their prices and to build a simple predictive model.

## Dataset
The dataset has 6 observations and 4 features. Features namely:
-	Area
-	Bedrooms
-	Age
-	Price
  
## Load Data
Loaded the data and viewed it

![image](https://github.com/user-attachments/assets/13ed5cc5-f276-4107-8e69-edcd746889f4)

## Prepare Data
#### Check for missing values and handling them
The bedrooms column had one missing value. Handled the missing value by imputing it with the median.

![image](https://github.com/user-attachments/assets/4b092afb-e4b0-44c6-ab28-ca1a6167cc73)

#### Split the dataset
Split the dataset such that 80% was for training and 20% for testing the model.

![image](https://github.com/user-attachments/assets/5fd2bd9f-144e-49d2-8028-1a71d6f4da73)

## Build the model
A linear regression model was trained using scikit-learn.

![image](https://github.com/user-attachments/assets/b05986b3-772e-48a7-9335-5a6f6be375e3)

## Evaluate the Model
Evaluation metrics were calculated, and the results are:
MAE: 39608.21
MSE: 1713617314.55
RMSE: 41395.86
R² Score: -29.46

![image](https://github.com/user-attachments/assets/5ba7cf6e-0bce-482f-97c1-9aa9db6c47be)

## Visualize the Results
A regression line was plotted against the actual data.

![image](https://github.com/user-attachments/assets/9e56c162-dafe-491b-9e3f-fec041535e80)

## Conclusion
This project demonstrated the practical application of linear regression in predicting house prices based on quantitative features such as area, number of bedrooms, and property age. After cleaning and preparing the small dataset, a simple linear regression model was trained using scikit-learn. The model’s evaluation on the test data returned a negative R² score of -29.46, indicating it performed worse than a simple average-based prediction. This outcome is expected due to the small dataset, which limits the model’s ability to learn meaningful patterns and generalize effectively. Despite the poor predictive performance, the project was valuable in reinforcing practical skills in data preparation, model development, metric interpretation, and understanding the influence of data size on model reliability




