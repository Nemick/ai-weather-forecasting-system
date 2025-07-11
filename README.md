# AI-Weather-Forecasting-System

AI Weather Forecasting System uses machine learning to predict temperature, humidity, and precipitation for Nairobi, Kenya. It preprocesses historical weather data, trains a multi-output random forest model, and visualizes actual vs predicted results.

## Features

- Cleans and preprocesses historical weather data
- Predicts multiple weather variables (tempmax, tempmin, humidity, precip)
- Uses a Random Forest regressor for robust predictions
- Visualizes actual vs predicted values for easy comparison

## Requirements

- Python 3.x
- pandas
- matplotlib
- scikit-learn
- numpy

## Usage

1. Clone the repository:
   ```
   git clone https://github.com/Nemick/ai-weather-forecasting-system.git
   ```
2. Place your weather CSV file (e.g., `Nairobi Kenya 2024-05-14 to 2025-05-14.csv`) in the project directory.
3. Open and run the `weather_forecast.ipynb` notebook in Jupyter or VS Code.

## Project Structure

- `weather_forecast.ipynb` — Main notebook with data processing, modeling, and visualization
- `sampled_forecast_plot.png` — Example output plot

## Results

The model predicts temperature and humidity with good accuracy, but precipitation is more challenging. Visualizations help compare actual and predicted values.

## License

This project is for
