# 🚗 Car Price Prediction with Machine Learning

This project builds a machine learning model to predict used car prices based on features such as brand goodwill, year of manufacture, fuel type, transmission, mileage and more.

## 📌 Project Steps
- **Data Loading & Exploration**: Load car data, inspect missing values and unique features.
- **Data Preprocessing**: Convert categorical features (Fuel_Type, Selling_type, Transmission) into numeric form, derive `Age` from `Year`.
- **Feature Engineering**: Drop unnecessary columns, one-hot encode categorical variables.
- **Model Training**: Train a regression model (Random Forest Regressor) on the processed data.
- **Evaluation**: Use R² Score and RMSE to evaluate model performance.
- **Prediction**: Predict selling price of a new car given its attributes.
- **Visualization**: Scatter plot of actual vs. predicted prices to check model accuracy.

## 🛠️ Tech Stack
- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

## 🚀 Usage
1. Clone the repository.
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
