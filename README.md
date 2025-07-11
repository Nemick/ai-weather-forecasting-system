#  AI Weather Forecasting System 🌦️

AI Weather Forecasting System uses machine learning to predict temperature, humidity, and precipitation for Nairobi, Kenya. It preprocesses historical weather data, trains a multi-output Random Forest model, and visualizes actual vs predicted results.

---

## 📁 Dataset

* Source: Collected from a weather monitoring service
* Period: **May 14, 2024 – May 14, 2025**
* File: `nairobi_weather_data.csv`

---

## 🔍 Objective

Predict the following weather parameters:

* Maximum Temperature (`tempmax`)
* Minimum Temperature (`tempmin`)
* Humidity (`humidity`)
* Precipitation (`precip`)

---

## 🧠 Model & Features

* **Algorithm**: Random Forest Regression with `MultiOutputRegressor`
* **Language**: Python 3
* **Libraries**: `pandas`, `scikit-learn`, `matplotlib`, `numpy`
* **Features Used**:

  * Dew Point (`dew`)
  * Wind Gust (`windgust`)
  * Wind Speed (`windspeed`)
  * Cloud Cover (`cloudcover`)
  * Solar Radiation (`solarradiation`)

---

## 🚀 Features

* Cleans and preprocesses historical weather data
* Predicts multiple weather variables (tempmax, tempmin, humidity, precip)
* Uses a Random Forest regressor for robust predictions
* Visualizes actual vs predicted values for easy comparison

---

## 📈 Results

| Metric       | tempmax | tempmin | humidity | precip  |
| ------------ | ------- | ------- | -------- | ------- |
| **R² Score** | 0.65    | 0.46    | 0.80     | -0.03   |
| **RMSE**     | 2.10°F  | 2.16°F  | 4.04%    | 0.12 in |

📌 Precipitation was challenging to predict due to dataset variability.

---

## 🖼️ Sample Output

![forecast\_plot](forecast_plot.png)

---

## 📂 Project Structure

* `weather_forecast.py` – Main ML script (for automation)
* `weather_forecast.ipynb` – Notebook version for step-by-step exploration
* `nairobi_weather_data.csv` – Cleaned historical weather data
* `forecast_plot.png` – Output graph of actual vs predicted results

---

## 💻 Requirements

* Python 3.x
* pandas
* scikit-learn
* matplotlib
* numpy

Install dependencies using:

```bash
pip install -r requirements.txt
```

---

## ▶️ Usage

1. Clone the repository:

```bash
git clone https://github.com/Nemick/ai-weather-forecasting-system.git
```

2. Place your weather CSV file (e.g., `nairobi_weather_data.csv`) in the project directory.
3. Open and run `weather_forecast.py` or `weather_forecast.ipynb`

---

## 📌 Future Improvements

* Integrate live weather API (e.g., OpenWeather)
* Add time series modeling (LSTM, ARIMA)
* Deploy via Flask/Django web API

---

## 👨‍💻 Author

**Nehemiah Kipkoech Kimutai**
GitHub: [@Nemick](https://github.com/Nemick)

---

## 📜 License

This project is for educational and demonstration purposes only.
