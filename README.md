# 🩺 Medical Insurance Premium Prediction

## 📌 Overview
This project predicts **medical insurance premiums** using **Machine Learning** based on demographic and health-related factors such as age, BMI, smoking status, and region.  
The model helps insurance companies, healthcare providers, and individuals estimate premium costs more accurately.

---

## 📂 Dataset
- **Source**: Commonly used `insurance.csv` dataset.
- **Features**:
  - `age` → Age of the person
  - `sex` → Gender of the person (`male`/`female`)
  - `bmi` → Body Mass Index
  - `children` → Number of dependents
  - `smoker` → Smoking habit (`yes`/`no`)
  - `region` → Residential area (`northeast`, `northwest`, `southeast`, `southwest`)
- **Target Variable**:
  - `charges` → Medical insurance premium in USD

---

## ⚙️ Technologies Used
- **Python** 🐍
- **Pandas, NumPy** → Data manipulation
- **Matplotlib, Seaborn** → Data visualization
- **Scikit-learn** → Machine learning algorithms
- **Jupyter Notebook** → Interactive development

---

## 🧪 Steps Involved
1. **Data Loading & Exploration**
   - Loaded dataset and checked for missing values.
   - Performed **Exploratory Data Analysis (EDA)** using statistical summaries and visualizations.

2. **Data Preprocessing**
   - Converted categorical variables into numeric using **Label Encoding**.
   - Checked feature correlations.
   - Split data into **Train (80%)** and **Test (20%)** sets.

3. **Model Building**
   - Applied multiple regression models:
     - Linear Regression
     - Decision Tree Regressor
     - Random Forest Regressor
     - Gradient Boosting Regressor
   - Selected **Random Forest** as the best-performing model.

4. **Model Evaluation**
   - Metrics used:
     - Mean Absolute Error (MAE)
     - Mean Squared Error (MSE)
     - R² Score
   - Example: Random Forest achieved **R² ≈ 0.89**.

5. **Prediction**
   - Created a function to predict charges based on user inputs.

---

## 📊 Example Visualizations
- Premium distribution by **smoking status**
- Relationship between **BMI** and **charges**
- Premium variation across **regions**
- Age vs Charges trend



