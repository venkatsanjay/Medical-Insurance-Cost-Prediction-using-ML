# Medical-Insurance-Cost-Prediction-using-ML

Overview
This project demonstrates how to create a machine learning model that predicts medical insurance premiums based on customer profiles. The workflow covers dataset analysis, feature engineering, model training, evaluation, and deployment in a web application.


* Data Preparation: Cleaning and encoding categorical data, handling missing values, scaling features.
* Feature Selection: Variables typically include age, sex, BMI, number of children, smoking habits, and geographical region.
* Modeling: Building and training regression models (e.g.  Random forest Regressor) in Python using libraries like pandas, scikit-learn, numpy.
* Evaluation: Assessing performance using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R² score.
* Prediction Workflow: Using the trained model to make future premium estimates from sample input data.

🛠️ Tools & Libraries Used -
* 1- pandas for data manipulation
* 2- scikit-learn for machine learning utilities and RandomForestRegressor
* 3- matplotlib & seaborn for visualization 
* 4- numpy for numeric operations
* 5- streamlit for web application 
* 6- pickle (model serialization)


#steps followed to predict the insurance 
* 1)Load a dataset (e.g. insurance.csv).
* 2)Preprocess the data: encode categorical variables, scale numeric features.
* 3)Split data into training and test subsets.
* 4)Train a regression model (e.g. Random forest Regressor).
* 5)Evaluate on test set and interpret metrics.
* 6)Input new user data to make premium predictions.
for web application (streamlit) _ http://localhost:8501
