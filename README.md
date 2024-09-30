# Housing Price Prediction
This project aims to predict housing prices using various machine learning algorithms. The dataset includes features such as area, number of bedrooms, bathrooms, stories, and more. The project explores multiple models and uses a range of data preprocessing and evaluation techniques to identify the best model for price prediction.

## Project Overview
## 1. Dataset Understanding
The dataset contains information about housing properties, including features like price, area, number of bedrooms, bathrooms, stories, and more. The first step involved understanding and exploring the dataset to identify key insights.

## 2. Data Preprocessing
Several preprocessing steps were applied to prepare the dataset for modeling:
- **Data Cleaning**: Handled missing values and corrected any data inconsistencies.
- **Feature Encoding**: Categorical features like 'mainroad', 'guestroom', and 'furnishingstatus' were converted into numerical values using techniques such as one-hot encoding.
- **Data Scaling**: Feature scaling was applied to normalize the values for better model performance.
- **Data Correlation**: Analyzed correlations between features to identify strong predictors for price.
- **Outlier Detection and Removal**: Outliers were detected and removed to improve model accuracy.
## 3. Model Building
The dataset was split into training and testing sets using train_test_split. Various machine learning algorithms were applied, including:
- **Linear Regression**
- **Decision Tree Regressor**
- **Random Forest Regressor**
- **Support Vector Regressor (SVR)**
- **KNeighbors Regressor**
- **XGBoost**
## 4. Model Evaluation
The models were evaluated using the following metrics from sklearn:
- **Mean Squared Error (MSE)**
- **Mean Absolute Error (MAE)**
- **R² Score**
## 5. Hyperparameter Tuning
Hyperparameter tuning was performed using **GridSearchCV** to optimize the models. Several models were tuned, and their performance was evaluated. The best-performing model was **KNeighbors Regressor**, achieving a score of **99%**.

## Installation
To run this project locally, follow these steps:
Clone the repository
git clone https://github.com/Waseem2212/House_Price_Prediction
   
## Results
- The KNeighbors Regressor achieved a 99% accuracy score after hyperparameter tuning.
- The project demonstrates the importance of feature scaling and hyperparameter tuning in improving model performance.

## Conclusion
This project showcases the end-to-end process of building a machine learning model for housing price prediction. From data cleaning and preprocessing to model evaluation and hyperparameter tuning, the project highlights key steps in the data science.
   
