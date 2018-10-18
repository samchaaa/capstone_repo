# Capstone: Predicting Solar Irradiance with LSTMs

*Note: Notebook saves data to pickle for easier local access.*

[Notebook 1: EDA and Cleaning](https://github.com/samchaaa/capstone_repo/blob/master/1_EDA%20and%20Cleaning.ipynb)

[Notebook 2: Modeling and Predictions](https://github.com/samchaaa/capstone_repo/blob/master/2_Modeling%20and%20Predictions.ipynb)

## Summary
The project predicts future solar irradiance based on past data and current weather, using LSTMs.

## Background
Unlike most forms of energy, solar irradiance cannot be turned on and off, or stored in barrels or reservoirs. Unfortunately this makes solar energy risky for producers, users, and investors. Underpredicting results in a loss of upfront users and investment, while overpredicting means loss of energy for users and income for producers. De-risking solar is vital for achieving mainstream viability.

## Data
The data used was solar irradiance measurements from [Loyola Marymount University](https://midcdmz.nrel.gov/apps/go2url.pl?site=LMU_) from April 06, 2010 to May 05, 2016, collected from a rotating shadowband radiometer (RSR). This dataset was found via the National Renewable Energy Laboratory's (NREL) list of Measurement and Instrumentation Data Centers (MIDC).

## Metrics
The metric used for predictions was Direct Normal Irradiance (DNI), in W/m2. This is the amount of irradiance on a surface perpendicular to the sun. For reference, a square meter near the equator receives about 1 kW/m2 on a clear day.

## Findings


## Limitations
LMU's SOLRMAP dataset website warns to use the data between December 2014 and July 9th, 2015 with caution. During this period the RSR was not taking a full charge, leading to some gaps in data.

## Statistical analysis

### Implementation
Predictions were made using an LSTM (long short-term memory) model. Data was lagged by 24 hour, 1 week, and 30 day periods. Specific predictor features used were day of year, time of day, hour, DNI, air temperature, and humidity.

### Evaluation


### Inference


**Dataset Citation:**
Andreas, A., Wilcox, S.; (2012). Solar Resource & Meteorological Assessment Project (SOLRMAP): Rotating Shadowband Radiometer (RSR); Los Angeles, California (Data); NREL Report No. DA-5500-56502. http://dx.doi.org/10.5439/1052230
