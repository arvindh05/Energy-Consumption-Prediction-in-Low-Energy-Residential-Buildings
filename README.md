# Energy Consumption Prediction in Low-Energy Residential Buildings
This repository contains the code and resources for predicting energy consumption in a low-energy residential building using a dataset with over 19,000 records measured every 10 minutes. Our objective is to identify the most relevant predictors of energy consumption and develop robust regression models for accurate prediction.

## Overview
Drawing from two notable studies on energy prediction, this project focuses on utilizing Random Forest (RF) and Long Short-Term Memory (LSTM) models due to their demonstrated effectiveness. The dataset includes internal temperature, humidity, and external weather data.

## Key Components:
* **Random Forest and LSTM Models:** Implemented based on proven success in previous studies.
* **Feature Selection:** Utilized Boruta and Pearson correlation methods to identify key predictors.
* **Performance Evaluation:** Assessed using metrics such as MSE, RMSE, MAE, and R².
## Dataset
The dataset encompasses a diverse range of environmental and energy-related indicators, providing valuable insights into factors that influence energy consumption. Data exploration, preprocessing, and feature engineering steps are included to ensure the dataset is well-prepared for model training.

## Methodology
### Random Forest:
* **Baseline Model:** Initial model performance evaluation.
* **Feature Selection:** Using Boruta algorithm.
* **Hyperparameter Tuning:** Randomized and Grid Search techniques to optimize the model.

## LSTM:
**Data Preparation:** Scaling and reshaping for CNN-LSTM models.`<br>`
**Baseline Model:** Univariate model for initial performance.`<br>`
**Feature Selection and Parameter Tuning:** Identifying optimal features and parameters for improved model accuracy.`<br>`

## Results
Both models were evaluated using a range of performance metrics to ensure robustness and accuracy. Detailed results and comparisons with the referenced studies are provided.

## References
**Paper 1:** [Energy use prediction using regression models](https://www.sciencedirect.com/science/article/abs/pii/S0378778816308970?via%3Dihub)`<br>`
**Paper 2:** [Household appliance energy consumption prediction](https://www.researchgate.net/publication/339680663_Prediction_model_of_household_appliance_energy_consumption_based_on_machine_learning)`<br>`

## How to Use
Clone the repository.
Install required dependencies.
Run the Jupyter notebooks provided for data preprocessing, model training, and evaluation.
