# Energy-Prediction---ASHRAE
ASHRAE, the American Society of Heating and Air-Conditioning Engineers founded in 1894 focuses on building systems, energy efficiency, indoor air quality, refrigeration, and sustainability within the industry.
ASHRAE has conducted three competitions so far on Energy Consumption.
The main goal of these competitions is to predict the energy consumption of the coming years for better investments in energy efficiency.
Recently launched its third competition in October 2019. In this competition, they provided hourly consumption of four different energies of 1449 buildings in 16 different sites in a year.
They asked contestants to predict the hourly consumption of these energies for the next two years.

Energy prediction of buildings 
ashraeenergyprediction-eda1.ipynb : Performs EDA on dataset
energy-feature-engineering-2.ipynb : preprocessing on dataset and feature Engineering
models.ipynb : Performs different models on the dataset
kfold3-ashrae.ipynb : Kfold using LGBM 
meter-type-training1.ipynb : Trained LGBM on each meter(4 models)
site-meter-reading-lgb.ipynb : Trained LGBM on each site(16 models)
training-15modelsforstacking.ipynb : Stacking of 16 Models using LGBM by sampling the data
testing-15models-1.ipynb : Prediction of the first eight models
addtest15-1.ipynb : Prediction of last seven models
deeplearning-energyprediction.ipynb : Trained FFNN on data
deeplearning_without_lagfeatures.ipynb : Trained FFNN without lag features 
deeplearning-lstm.ipynb : Trained LSTM on data
ensembling-ashrae.ipynb : Ensemble of best models
