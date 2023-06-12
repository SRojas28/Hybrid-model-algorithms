# Hybrid-model-algorithm

![GitHub stars](https://img.shields.io/github/stars/SRojas28/Hybrid-model-algorithms?style=social)
![GitHub forks](https://img.shields.io/github/forks/SRojas28/Hybrid-model-algorithms?label=Fork&style=social)

[![DOI](https://zenodo.org/badge/633191595.svg)](https://zenodo.org/badge/latestdoi/633191595)
![GitHub repo size](https://img.shields.io/github/repo-size/SRojas28/Hybrid-model-algorithms?label=Repo%20Size)
![GitHub language count](https://img.shields.io/github/languages/count/SRojas28/Hybrid-model-algorithms?label=Languages)
![License](https://img.shields.io/github/license/SRojas28/Hybrid-model-algorithms)
![GitHub contributors](https://img.shields.io/github/contributors/SRojas28/Hybrid-model-algorithms)
![GitHub last commit](https://img.shields.io/github/last-commit/SRojas28/Hybrid-model-algorithms)
![Made from](https://img.shields.io/badge/From-Colombia-Yellow)

This project was created to develop a hybrid model algorithm based on machine learning to predict production, demand and dispatch energy microgrid or renewable energies, using [CAISO database](https://www.caiso.com/TodaysOutlook/Pages/supply.html) and [NREL database](https://nsrdb.nrel.gov/data-viewer). The database we used is available on [Mendeley Data](https://data.mendeley.com/datasets/fdfftr3tc2/1).

# Requirements
Make sure you have these dependencies latest versions installed:

- [Scikit-learn](https://scikit-learn.org/stable/)
- [XG-Boost](https://xgboost.readthedocs.io/en/stable/)
- [Pandas](https://pandas.pydata.org/)
- [Matplotlib](https://matplotlib.org/)
- [Seaborn](https://seaborn.pydata.org/)

# Running the code
- ```1_Data_Acquisition.ipynb``` contains the code related the creation of the CSV (the code is cleaned and debugged).
- ```2a_Forecast_Regressor_Graphs.ipynb``` shows the analysis of input and output variables.
- ```3a_Forecast_Regressor_PV.ipynb``` Those are the algorithms to predict photovoltaic energy (XG-Boost, KNN, DT and Neuronal Networks).
- ```3b_Forecast_Regressor_Demand.ipynb``` Those are the algorithms to predict demand energy (XG-Boost, KNN, DT and Neuronal Networks).
- ```3c_Forecast_Regressor_Wind.ipynb``` Those are the algorithms to predict wind energy (XG-Boost, KNN, DT and Neuronal Networks).
- ```4a_Ensemble_PV.ipynb``` This is the ensemble model of PV using AdaBoost and other estimators.
- ```4b_Ensemble_Demand.ipynb``` This is the ensemble model of Demand using AdaBoost and other estimators.
- ```4c_Ensemble_Wind.ipynb``` This is the ensemble model of Wind using AdaBoost and other estimators.
- ```5_Dispatch_Algorithm.ipynb``` This is the dispatch algorithm that uses the predictions from previous sections.

# Screenshots

<img src="https://user-images.githubusercontent.com/62435399/234739728-abc5c0c8-2c83-487b-886a-bb325ce8c17e.svg" alt="Logo" width="720">

<img src="https://user-images.githubusercontent.com/62435399/234739734-1a57e886-2d3f-4e68-8f71-b040c89b169b.svg" alt="Logo" width="720">

<img src="https://user-images.githubusercontent.com/62435399/234739746-6fed05cf-24a6-43b0-b9aa-7fb250d567ea.svg" alt="Logo" width="720">

# Authors
- [Paola Castro](https://github.com/C-Paola)
- [Sebastian Rojas](https://github.com/SRojas28)
- [Sergio Sepúlveda](https://github.com/serg-sepulveda)
- [Jhon Castro](https://github.com/jcastro295)
