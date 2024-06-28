# Linear_Regression_Project1
### This is a linear regression project.
### Ecommerce Linear Regression Analysis
#### This project involves analyzing customer data for an Ecommerce company based in New York City. The company sells clothing online and provides in-store style and clothing advice sessions. The objective is to determine whether the company should focus on improving their mobile app experience or their website to increase customer spending.

## Project Overview
The project consists of several key steps:

### Data Import and Preparation: Importing necessary libraries and reading the Ecommerce customer data.
### Exploratory Data Analysis (EDA): Visualizing and analyzing the relationships between different features and the target variable, Yearly Amount Spent.
### Model Training and Testing: Splitting the data into training and testing sets, training a linear regression model, and evaluating its performance.
### Model Interpretation: Interpreting the coefficients of the trained model to provide actionable insights for the company.
## Dataset
The dataset contains the following columns:

### Email: Customer's email address
### Address: Customer's physical address
### Avatar: Customer's avatar color
### Avg. Session Length: Average session length of in-store style advice sessions (in minutes)
### Time on App: Average time spent on the company's mobile app (in minutes)
### Time on Website: Average time spent on the company's website (in minutes)
### Length of Membership: Number of years the customer has been a member
### Yearly Amount Spent: Amount of money spent by the customer in a year
### Repository Structure
## The repository is structured as follows:

data/: Contains the Ecommerce Customers.csv file.
notebooks/: Jupyter notebooks used for analysis and model training.
scripts/: Python scripts for data processing and model training.
README.md: This file, providing an overview of the project.
### Installation
To run the project locally, follow these steps:

### Clone the repository:

sh
Copy code
git clone https://github.com/your-username/ecommerce-linear-regression.git
cd ecommerce-linear-regression
Install the required packages:

sh
Copy code
pip install -r requirements.txt
Launch Jupyter Notebook:

sh
Copy code
jupyter notebook
Open and run the notebooks in the notebooks/ directory to see the analysis and results.

# Analysis Steps
Data Import and Preparation:

Import libraries: pandas, numpy, matplotlib, seaborn.
Read the dataset into a DataFrame.
# Exploratory Data Analysis (EDA):

Use seaborn to create jointplots and pairplots to explore relationships between features and the target variable.
Identify the most correlated feature with Yearly Amount Spent.
## Model Training and Testing:

Split the data into training and testing sets using train_test_split from sklearn.
Train a linear regression model on the training data.
Evaluate the model using Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE).
## Model Interpretation:

Interpret the coefficients of the linear regression model to understand the impact of each feature on the target variable.
Provide recommendations based on the coefficients.
## Results
The analysis reveals that the Length of Membership is the most correlated feature with Yearly Amount Spent.
The company should focus on improving the mobile app experience, as the Time on App feature has a significant positive impact on yearly spending.
## Conclusion
The project provides valuable insights into customer behavior and spending patterns, helping the company make informed decisions about where to focus their efforts for maximum impact.
