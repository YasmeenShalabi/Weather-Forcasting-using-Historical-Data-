🌦️ Weather Forecasting Using Historical Data (Linear Regression)
📌 Overview
This project demonstrates a simple weather forecasting model using historical weather features such as temperature, humidity, wind speed, and precipitation.
A Linear Regression model is trained to predict the next day's temperature based on these inputs.

The project includes:

Data preparation

Model training & evaluation

Visualization of actual vs. predicted temperatures

Predicting temperature for new weather conditions

📂 Dataset Description
The dataset is manually created and contains 10 days of weather observations with the following features:

Temperature — Current day's temperature (°C)

Humidity — Percentage humidity

Wind Speed — Wind speed (km/h)

Precipitation — Binary indicator (0 = no rain, 1 = rain)

Next Day Temperature — Target variable to predict

Each row represents one day of weather conditions.

⚙️ Modeling Workflow
1. Load and Prepare Data
The dataset is converted into a pandas DataFrame.
Features (X) include:

Temperature

Humidity

Wind Speed

Precipitation

Target (y):

Next Day Temperature

2. Train/Test Split
Data is split into:

80% training data

20% testing data

3. Train Linear Regression Model
A LinearRegression model from scikit‑learn is trained on the historical data.

4. Evaluate Model
Two evaluation metrics are used:

Mean Squared Error (MSE) — Measures average squared difference between actual and predicted values

R² Score — Indicates how well the model explains variance (closer to 1 = better)

5. Visualization
A Matplotlib plot compares:

Actual temperatures

Predicted temperatures

This helps visualize model performance.

6. Predict New Temperature
The model predicts next‑day temperature using new weather inputs.

📈 Visualization Example
The script generates a line plot showing actual vs. predicted temperatures for the test set, helping you visually assess model accuracy.
