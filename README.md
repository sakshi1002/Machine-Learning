Titanic Survival Prediction Model 


This project focuses on building a predictive model to determine the survival of passengers aboard the Titanic using Logistic Regression. The model uses historical data about passengers to predict whether they survived or not.

 Project Overview
The Titanic dataset is one of the most famous datasets for beginners in machine learning and data science. This project involves:

Exploratory Data Analysis (EDA)

Data Cleaning and Preprocessing

Feature Engineering

Building a Logistic Regression model

Model Evaluation and Interpretation

🔧 Technologies Used
Python 

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

📂 Dataset
The project uses the Titanic dataset available directly from Seaborn (sns.load_dataset('titanic')). It includes the following features:

Passenger class (pclass)

Sex (sex)

Age (age)

Fare (fare)

Embarkation town (embark_town)

And more...

The target variable is:

survived: 1 (survived), 0 (did not survive)

📊 Steps Performed
Data Loading: Loaded Titanic dataset using Seaborn.

Exploratory Data Analysis (EDA): Visualized key trends and relationships in the data (age, gender, class, survival rate).

Data Preprocessing:

Handled missing values

Converted categorical variables into numeric using encoding

Model Building: Applied Logistic Regression from scikit-learn.

Model Evaluation:

Accuracy Score

Confusion Matrix

Classification Report

📈 Results
The model outputs predictions on survival along with performance metrics to evaluate its effectiveness.
