# Short-term Solar Forecasting Using LSTMs
This project predicts solar irradiance one week in the future, based on current solar irradiance and local weather conditions using an LSTM (long short-term memory) model.

#### Methods Used
* Machine Learning
* Data Visualization
* Predictive Modeling

#### Technologies
* Python
* Keras
* Pandas, jupyter

## Description
Unlike most forms of energy, solar irradiance cannot be turned on and off, or stored in barrels or reservoirs. Unfortunately this makes solar energy risky for producers, users, and investors. Underpredicting solar output results in a loss of upfront users and investment, while overpredicting solar output means unreliability for users and loss of income for producers. De-risking solar is vital for achieving mainstream viability.

Can future solar output be predicted using current and past data?

One machine learning model suited to this problem is LSTMs (long short-term memory), a type of RNN (recurrent neural network). LSTMs used to predict future sequences in a time series based on past time steps.

Data used were solar irradiance measurements from [Loyola Marymount University](https://midcdmz.nrel.gov/apps/go2url.pl?site=LMU_) from April 06, 2010 to May 05, 2016, collected from a rotating shadowband radiometer (RSR). This dataset was found via the National Renewable Energy Laboratory's (NREL) list of Measurement and Instrumentation Data Centers (MIDC).

Metric used for predictions was Direct Normal Irradiance (DNI), in W/m2. This is the amount of irradiance on a surface perpendicular to the sun. For reference, a square meter near the equator receives about 1 kW/m2 on a clear day.

## Getting Started

1. Clone this repo (for help see this [tutorial](https://help.github.com/articles/cloning-a-repository/)).

2. See [Notebook 1: EDA and Cleaning](https://github.com/samchaaa/capstone_repo/blob/master/1_EDA%20and%20Cleaning.ipynb) to examine raw data, EDA, and preliminary cleaning steps.
    
3. See [Notebook 2: Modeling and Predictions](https://github.com/samchaaa/capstone_repo/blob/master/2_Modeling%20and%20Predictions.ipynb) for feature engineering, modeling, and evaluation of predictions.

4. See [Notebook 3: Technical Report](https://github.com/samchaaa/capstone_repo/blob/master/3_Technical_Report.ipynb) for an overview of the project.

## Featured Notebooks/Analysis/Deliverables
* [Slide Deck: Short-term Solar Forecasting Using LSTMs](https://docs.google.com/presentation/d/1AzhJZZMlhhHzTSzhDT9g5xVkLBVuIuJTVMbXXLKdAno/present?slide=id.p)

## Contact

**Contacts: [Sam Chakerian](https://github.com/samchaaa)**

* I am currently extending this project with satellite imagery. If you are experienced in this area or would like to help, shoot me an e-mail (see Github profile).
