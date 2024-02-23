# CodeClauseInternship_CustomerLifetimeValuePrediction
Predicting the lifetime value of customers for a business based on their historical interactions.

**Project Title:** Customer Lifetime Value Prediction

**Aim:**  
The aim of this project is to predict the lifetime value of customers for a business based on their historical interactions.

**Description:**  
The project involves the following steps:
1. **Data Loading:** The dataset containing information about customer interactions and lifetime value is loaded from the 'customer_data.csv' file.
2. **Data Preprocessing:** The dataset is preprocessed by selecting relevant features ('historical_interactions' and 'purchase_amount') as input variables (X) and the 'lifetime_value' as the target variable (y).
3. **Data Splitting:** The dataset is split into training and testing sets using the `train_test_split` function from the `sklearn.model_selection` module.
4. **Model Development:** A linear regression model is developed using the `LinearRegression` class from the `sklearn.linear_model` module. The model is trained using the training data.
5. **Model Evaluation:** The trained model is evaluated using the testing data. Mean Squared Error (MSE) and R-squared (R2) scores are calculated to assess the model's performance.
6. **Visualization:** The actual lifetime values versus the predicted lifetime values are visualized using a scatter plot.

**Technologies Used:**  
- Python: Programming language used for coding the project.
- Pandas: Library used for data manipulation and analysis.
- NumPy: Library used for numerical computations.
- Scikit-learn: Library used for machine learning tasks such as data splitting, model development, and evaluation.
- Matplotlib: Library used for data visualization.

This project provides regression modeling for predicting customer lifetime value based on historical interactions and purchase amount, thus helping businesses make informed decisions regarding customer engagement and marketing strategies.
