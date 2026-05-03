📈 Stock Price Prediction System
🚀 Overview

This project is an end-to-end stock price prediction system that leverages both Machine Learning (XGBoost) and Deep Learning (LSTM) models to forecast stock prices using historical data.
It follows a complete pipeline including data preprocessing, feature engineering, model training, evaluation, comparison, and visualization.

✨ Highlights
Built dual-model system using XGBoost and LSTM
Implemented full ML pipeline from scratch
Compared models to identify best-performing approach
Focused on accuracy, performance, and scalability
Modular code structure for easy extension
🛠️ Tech Stack
Language: Python
Libraries: Pandas, NumPy, Scikit-learn, XGBoost, TensorFlow/Keras, Matplotlib
Concepts: Machine Learning, Deep Learning, Time Series Forecasting
📂 Project Structure
├── data_preprocessing.py        # Data cleaning & preprocessing
├── feature_engineering.py       # Feature creation & transformation
├── xgboost_model.py             # XGBoost model training
├── lstm_model.py                # LSTM deep learning model
├── compare_models.py            # Model comparison logic
├── visualize_predictions.py     # Graphs & visualization
├── X_train.csv / X_test.csv     # Training & testing features
├── y_train.csv / y_test.csv     # Target values
├── FEATURE_ENGINEERED_DATA.csv  # Final processed dataset
└── README.md
⚙️ Workflow
1. Data Preprocessing
Cleaned dataset and handled missing values
Split data into training and testing sets
2. Feature Engineering
Extracted meaningful features to improve prediction accuracy
3. Model Training
Trained XGBoost model for regression
Built LSTM model for time-series prediction
4. Model Evaluation
Evaluated models using RMSE and performance metrics
Compared XGBoost and LSTM results
5. Visualization
Plotted actual vs predicted values
Analyzed trends and model behavior
📊 Results
Successfully implemented and compared ML and DL models
Identified performance differences between XGBoost and LSTM
Improved accuracy using feature engineering techniques
# Install dependencies
pip install -r requirements.txt

# Run preprocessing
python data_preprocessing.py

# Train models
python xgboost_model.py
python lstm_model.py

# Compare models
python compare_models.py

# Visualize results
python visualize_predictions.py
📌 Future Enhancements
Integrate real-time stock data APIs
Tune hyperparameters for better accuracy
Deploy as a web app (Flask / FastAPI)
Add advanced models (GRU, Transformers)
👨‍💻 Author

Kappala Omnath
Java Backend Developer | Python & Machine Learning
