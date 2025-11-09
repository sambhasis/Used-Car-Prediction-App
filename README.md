# Used-Car-Prediction-App
# 🚗 Car Price Prediction using Machine Learning

This project predicts the **selling price of used cars** using machine learning algorithms based on real-world data from CarDekho. It helps estimate car prices using various features like brand, mileage, engine, fuel type, transmission, and age of the vehicle.

---

## 📘 Overview
The program cleans raw car data, visualizes relationships between features and price, and trains multiple ML models to find the most accurate predictor.  
All steps — data preprocessing, visualization, model training, evaluation, and prediction — are automated in a single Python file.

---

## ⚙️ Features
✅ Cleans and preprocesses real-world car data  
✅ Handles missing values and converts categorical features  
✅ Compares multiple ML models (Linear Regression, Random Forest, Gradient Boosting, XGBoost)  
✅ Automatically saves the best-performing model  
✅ Predicts price for any new car input  
✅ Generates visualizations for better understanding  

---

## 🧠 Algorithms Used
| Model | Description |
|--------|-------------|
| **Linear Regression** | Baseline model for linear price relationships |
| **Random Forest** | Ensemble model capturing non-linear patterns |
| **Gradient Boosting** | Sequential model improving over weak learners |
| **XGBoost** | Optimized gradient boosting with fast training and high accuracy |

---

## 🧰 Libraries Used
- pandas  
- numpy  
- matplotlib  
- seaborn  
- scikit-learn  
- xgboost  
- joblib  

---

## 🗂️ Folder Structure
Car-Price-Prediction/
│
├── cardekho_dataset.csv # Dataset file
├── car_price_prediction.py # Main Python script (PyCharm)
├── test_set_predictions.csv # Model predictions
├── XGBoost_best_model.pkl # Saved model (if XGBoost is best)
└── README.md # Documentation

yaml
Copy code

---

## 🚀 How to Run
1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/Car-Price-Prediction.git
Navigate to the folder:

bash
Copy code
cd Car-Price-Prediction
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Run the Python script in PyCharm or terminal:

bash
Copy code
python car_price_prediction.py
📊 Output
Visualizations (distribution, scatter plots, box plots)

Model performance metrics (RMSE, MAE, R²)

Comparison chart of all models

Saved .pkl file for best model

Test predictions in CSV file

Example price prediction for a sample car

🧩 Example Output
yaml
Copy code
Training XGBoost ...
XGBoost -> RMSE: 1.23, MAE: 0.87, R2: 0.94
Best model by RMSE: XGBoost
Predicted price for sample car: 5.45 lakhs
💡 Future Enhancements
Integrate with Flask or Streamlit for a web interface

Add live car resale data scraping

Improve accuracy using hyperparameter tuning

👨‍💻 Developer
Sambhasis Jena


