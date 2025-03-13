# House-Price-Prediction

### Overview
This project builds a machine learning model to predict house prices using the California Housing dataset. The model is trained using Random Forest Regressor and evaluates performance using RMSE, MAE, and R² metrics.
## Project Structure
house-price-prediction/
│── notebooks/
│   ├── house_price_prediction.ipynb   # Jupyter Notebook with full implementation
│── src/
│   ├── train.py                       # Python script for training & saving the model
│   ├── preprocess.py                   # Data preprocessing pipeline
│   ├── model.pkl                      # Trained model file
│── requirements.txt                    # List of dependencies
│── README.md                           # Project description and setup instructions

## Setup Instructions
### 1. Clone the Repository
git clone https://github.com/your-username/house-price-prediction.git
cd house-price-prediction

### 2. Install Dependencies
pip install -r requirements.txt

### 3. Train the Model
python src/train.py

### Features
Data preprocessing (handling missing values, scaling, encoding)

Model training using Random Forest

Performance evaluation with RMSE, MAE, and R²

Saves trained model for future predictions
### Model Evaluation Metrics
MAE (Mean Absolute Error) - Measures the average absolute difference between actual and predicted values.

RMSE (Root Mean Squared Error) - Penalizes larger errors more than MAE.

R² Score (Coefficient of Determination) - Indicates how well the model explains variance in the target variable.

### Contributors
Ajay Jarupula

## License
This project is licensed under the MIT License.
Note: This project uses RandomForestRegressor from sklearn.ensemble.
