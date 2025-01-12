# ForestFire_RiskPrediction
FireWatch : Forest Fire Risk Prediction System
Overview
This project implements machine learning models to predict forest fires in two regions of  (Bejaia and Sidi Bel-abbes) using meteorological and environmental data. The system analyzes various weather conditions and Fire Weather Index (FWI) components to classify the fire risk.

Dataset Description
Time Period: June 2012 to September 2012
Regions: Bejaia (Northeast) and Sidi Bel-abbes (Northwest)
Total Instances: 244 (122 per region)
Class Distribution:
Fire: 138 instances
No Fire: 106 instances
Features
Weather Data:

Temperature (°C): 22-42
Relative Humidity (%): 21-90
Wind Speed (km/h): 6-29
Rainfall (mm): 0-16.8
FWI Components:

Fine Fuel Moisture Code (FFMC): 28.6-92.5
Duff Moisture Code (DMC): 1.1-65.9
Drought Code (DC): 7-220.4
Initial Spread Index (ISI): 0-18.5
Buildup Index (BUI): 1.1-68
Fire Weather Index (FWI): 0-31.1
Models Implemented
Linear Regression
Lasso Regression (with Cross Validation)
Ridge Regression (with Cross Validation)
Elastic Net Regression (with Cross Validation)
Model Performance
Best performing models:

Linear Regression: MAE = 0.547, R² = 0.985
Ridge Regression: MAE = 0.564, R² = 0.984
Lasso CV: MAE = 0.620, R² = 0.982
Elastic Net CV: MAE = 0.658, R² = 0.981
