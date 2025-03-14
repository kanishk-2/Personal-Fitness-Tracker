# Personal Fitness Tracker

## Overview
The **Personal Fitness Tracker** is a machine learning-based web application designed to help users analyze and predict fitness-related metrics, such as calorie burn based on exercise details. The application uses **Streamlit** for an interactive interface and **scikit-learn** for model training and predictions.

## Features
- 📊 **Data Visualization**: Uses `Matplotlib`, `Seaborn`, and `Plotly` to provide visual insights.
- 🏋️ **Fitness Data Analysis**: Reads `calories.csv` and `exercise.csv` for training machine learning models.
- 🤖 **Machine Learning Models**: Implements `Linear Regression` and `Random Forest Regressor` for predictions.
- 🎯 **Model Optimization**: Uses `GridSearchCV` for hyperparameter tuning.
- 📈 **Performance Evaluation**: Evaluates models using `mean_squared_error` and other metrics.

## Installation
To set up the project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/personal-fitness-tracker.git
   cd personal-fitness-tracker
   
2. Install dependencies:
   ```bash
    pip install -r requirements.txt

3. Run the Streamlit app:
   ```bash
   streamlit run app.py

## Project Structure
📂 personal-fitness-tracker
│-- 📄 app.py               # Streamlit app for fitness tracking
│-- 📄 fitness_tracker.py   # Data processing and model training script
│-- 📄 fitness_tracker.ipynb # Jupyter Notebook for interactive analysis
│-- 📂 data
│   │-- 📄 calories.csv      # Dataset with calorie expenditure data
│   │-- 📄 exercise.csv      # Dataset with exercise details
│-- 📄 requirements.txt     # List of dependencies
│-- 📄 README.md            # Project documentation

## How It Works
1. Load the Data: The app reads calories.csv and exercise.csv containing user activity records.
2. Train the Model: The script trains LinearRegression and RandomForestRegressor models to predict calorie expenditure.
3. Visualize Insights: The app displays interactive plots and metrics to help users understand their fitness trends.
4. Predict Calories Burned: Users can input their activity details, and the model will predict calories burned.

## Contributing
Feel free to fork this repository and contribute by submitting a pull request.

## Output
<img width="1264" alt="output" src="https://github.com/user-attachments/assets/55cfb6e3-5a2c-4784-98ea-3106b3a556d7" />

## License
This project is licensed under the MIT License.


