# Car Price Prediction using Machine Learning

# Project Overview
This project focuses on predicting car prices using Machine Learning techniques.  
The model is trained on car-related features such as fuel type, transmission, kilometers driven, ownership, and other important attributes to estimate the selling price of a car.

The project demonstrates the complete Machine Learning workflow including:
- Data preprocessing
- Feature engineering
- Data visualization
- Model training
- Prediction
- Model evaluation
  
# Objectives
- Analyze car dataset features
- Clean and preprocess the dataset
- Train a regression model for price prediction
- Evaluate model performance using regression metrics
- Visualize actual vs predicted car prices
- Understand real-world applications of price prediction systems

# Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

# Dataset
The dataset contains information about cars such as:
- Car Name
- Year
- Present Price
- Selling Price
- Kilometers Driven
- Fuel Type
- Seller Type
- Transmission
- Owner

Dataset Source:
https://www.kaggle.com/datasets/hellbuoy/car-price-prediction

# Machine Learning Model
The following regression model is used:
- Random Forest Regressor

# Project Workflow

# 1. Import Libraries
Imported required Python libraries for data analysis and machine learning.

# 2. Load Dataset
Loaded the dataset using Pandas.

# 3. Data Preprocessing
- Checked missing values
- Encoded categorical columns
- Prepared feature and target variables

# 4. Train-Test Split
Split dataset into training and testing sets.

# 5. Model Training
Trained Random Forest Regressor model.

# 6. Prediction
Predicted car prices using test data.

# 7. Model Evaluation
Evaluated the model using:
- MAE
- MSE
- RMSE
- R2 Score

# 8. Visualization
Generated:
- Actual vs Predicted Price Plot
- Feature Importance Graph

# Results
The model successfully predicts car prices with good accuracy using regression techniques.

Example evaluation metrics:
- MAE: Low error value
- RMSE: Good prediction performance
- R2 Score: High accuracy

# Real-World Applications
- Used car price estimation
- Online automobile marketplaces
- Car resale valuation systems
- Insurance pricing systems
- Automobile dealership analytics

# How to Run the Project

# Install Required Libraries

pip install pandas numpy matplotlib seaborn scikit-learn


# Run the Python File

python car_price_prediction.py

# Project Structure

Car-Price-Prediction/
│
├── car data.csv
├── car_price_prediction.py
├── README.md
└── images/

# Future Improvements
- Use advanced regression algorithms
- Deploy model using Flask or Streamlit
- Improve prediction accuracy with hyperparameter tuning
- Add web interface for user input

# Conclusion
This project demonstrates how Machine Learning can be used to predict car prices effectively using regression models and data analysis techniques.

# Author
Kavita Godge
