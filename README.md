
# RainVision AI 🌧️

### AI-Based Rainfall Prediction Using Deep Learning (LSTM)

## Project Overview
RainVision AI is a deep learning-based rainfall prediction project that uses Long Short-Term Memory (LSTM) neural networks to estimate rainfall using historical weather observations.

The project includes a Gradio dashboard for rainfall visualization, prediction and model performance analysis.

## Technologies Used
- Python
- TensorFlow / Keras
- LSTM Deep Learning
- Pandas and NumPy
- Scikit-learn
- Plotly
- Gradio
- Google Colab

## Dataset
Historical daily weather data for Hyderabad, Telangana, covering 2015–2025.

Features:
- Temperature
- Humidity
- Atmospheric Pressure
- Wind Speed
- Rainfall

## Model
The LSTM model uses the previous seven days of weather observations to predict rainfall.

An experimental recursive forecasting approach is used to generate seven consecutive rainfall estimates.

## Model Evaluation

### One-day test evaluation
- MAE: 2.198 mm
- RMSE: 5.06 mm

### Seven-day recursive backtest
- MAE: 2.705 mm
- RMSE: 5.917 mm

Persistence baseline:
- MAE: 3.902 mm
- RMSE: 8.090 mm

## Dashboard Features
- Historical rainfall visualization
- Seven-day rainfall prediction
- Actual vs predicted rainfall analysis
- Model performance metrics
- Confusion matrix visualization

## Important Limitations
The seven-day forecast is experimental and recursively uses the model's own rainfall predictions. Future temperature, humidity, pressure and wind speed are held at their last observed values. It is not a verified operational weather forecast.

## How to Run
1. Open the `RainVision_AI.ipynb` notebook in Google Colab.
2. Upload or load the required dataset and model files.
3. Execute the notebook cells in order.
4. Launch the Gradio dashboard.

## Project Type
Academic Deep Learning Project

