# 🚢 Titanic Survival Prediction using Machine Learning

This project builds a machine learning model to predict survival outcomes of passengers on the Titanic based on features such as age, gender, passenger class, fare, and other demographic information. It is a classic binary classification problem used to demonstrate data preprocessing, exploratory data analysis, and supervised machine learning techniques.

---

## 📌 Project Overview

The objective is to analyze Titanic passenger data and build a predictive model that determines whether a passenger survived or not.

The project covers:
- Data cleaning and handling missing values  
- Exploratory Data Analysis (EDA)  
- Feature engineering and encoding categorical variables  
- Model building and training  
- Model evaluation  
- Making predictions on unseen data  

---
## 🎯 Objective

To predict passenger survival based on key features such as:
- Age  
- Sex  
- Passenger Class (Pclass)  
- Fare  

This is a binary classification problem:
- 0 = Did not survive  
- 1 = Survived
- 
## 📊 Dataset

The dataset contains information about Titanic passengers, including:

- Passenger class (Pclass)  
- Name, Sex, Age  
- Number of siblings/spouses aboard (SibSp)  
- Number of parents/children aboard (Parch)  
- Ticket fare  
- Cabin and Embarked location  
- Survival status (target variable: 0 = did not survive, 1 = survived)  

---

## 🧠 Machine Learning Approach

The workflow followed in this project:

1. Load and inspect the dataset  
2. Handle missing values  
3. Perform exploratory data analysis (EDA)  
4. Encode categorical variables  
5. Feature selection and engineering  
6. Train machine learning models  
7. Evaluate model performance  
8. Generate predictions  

---

## ⚙️ Technologies Used

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

## 🧠 Machine Learning Workflow

This project follows a structured machine learning pipeline:

### 1. Data Import
The dataset is loaded using pandas for exploration and preprocessing.

### 2. Data Understanding
Initial inspection of the dataset is performed to understand structure, missing values, and distributions.

### 3. Data Cleaning & Preparation
- Missing values in Age are filled using the median  
- Categorical variable (Sex) is encoded into numerical format  
- Irrelevant columns such as Name and PassengerId are removed  
- Features are selected for modeling  

### 4. Exploratory Data Analysis (EDA)
Data visualizations are used to understand survival patterns:
- Survival distribution  
- Survival by Sex  
- Survival by Passenger Class  

### 5. Feature Selection
Selected features:
- Age  
- Sex  
- Pclass  
- Fare  

Target variable:
- Survived  

### 6. Train-Test Split
The dataset is split into training and testing sets to evaluate model performance fairly.

### 7. Feature Scaling
StandardScaler is used to normalize feature values for better model performance.

### 8. Model Training
A Logistic Regression model is trained due to its simplicity and interpretability.

### 9. Model Evaluation
Model performance is evaluated using:
- Accuracy score  
- Precision, recall, and F1-score  

Final test accuracy: **79%**

---

## 📈 Model Performance

The Logistic Regression model achieved:

- **Accuracy: 0.79**
- Strong performance in predicting non-survivors (Class 0)
- Reasonable performance in predicting survivors (Class 1)

---

## 🔍 Key Insights

- Gender (Sex) is the strongest predictor of survival  
- Passenger class significantly influenced survival chances  
- Simpler models can still produce meaningful and interpretable results  
- Proper data preprocessing has a major impact on model performance  

---

## ⚙️ Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Scikit-learn  

---

## 📁 Project Link

GitHub Repository:  
https://github.com/bismarkosei0810/Titanic-Survival-Prediction-using-Machine-Learning

---

## 📌 Conclusion

This project demonstrates an end-to-end machine learning workflow, from data cleaning to model evaluation. Despite using only four features, the model achieved a solid performance of 79% accuracy.

It confirms that:
- Data quality matters more than model complexity  
- Simple models can still deliver strong insights  
- Feature selection is critical in predictive modeling  

---

## 👤 Author

**Bismark Osei-Bonsu**  
Machine Learning / Data Analytics 
