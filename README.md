# Crop-Yield-Prediction-Model
Predicted crop yield using NDVI time-series and meteorological parameters via regression models



In this project, I developed a crop yield prediction model using satellite-derived vegetation indices and meteorological data. I used NDVI time-series extracted from Sentinel-2 imagery and combined it with weather parameters like rainfall and temperature.

I processed the satellite data using Google Earth Engine to efficiently generate NDVI time-series. Then, I merged it with meteorological datasets and built regression models such as Linear Regression and Random Forest Regressor to predict crop yield.


# 2. Workflow (Step-by-Step)
# Step 1: Data Collection

Satellite data (Sentinel-2)
Weather data (rainfall, temperature)
Ground truth yield data

# Step 2: NDVI Calculation

NDVI formula 👇

NDVI=NIR+Red/NIR−Red
Extract NDVI for multiple dates (time-series)

# Step 3: Feature Engineering

Mean NDVI
Max NDVI
NDVI growth trend
Rainfall sum
Avg temperature

# Step 4: Model Building

Linear Regression
Random Forest Regressor

# Step 5: Prediction

Predict yield (kg/ha or ton/ha)
