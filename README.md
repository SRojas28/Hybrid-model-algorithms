# Hybrid-model-algorithm

<img src="https://user-images.githubusercontent.com/62435332/221739474-0175618c-684a-4836-acd3-2d6b34513c96.png" alt="Logo" width="250" height="250">

![GitHub stars](https://img.shields.io/github/stars/SRojas28/Hybrid-model-algorithm?style=social)
![GitHub forks](https://img.shields.io/github/forks/SRojas28/Hybrid-model-algorithm?label=Fork&style=social)

![GitHub repo size](https://img.shields.io/github/repo-size/SRojas28/Hybrid-model-algorithm?label=Repo%20Size)
![GitHub language count](https://img.shields.io/github/languages/count/SRojas28/Hybrid-model-algorithm?label=Languages)
![License](https://img.shields.io/github/license/SRojas28/Hybrid-model-algorithm)
![GitHub contributors](https://img.shields.io/github/contributors/SRojas28/Hybrid-model-algorithm)
![GitHub last commit](https://img.shields.io/github/last-commit/SRojas28/Hybrid-model-algorithm)
![Made from](https://img.shields.io/badge/From-Colombia-Yellow)

This porject was created to develop a hybrid model algorithm based on machine learning to predict production, demand and dispatch energy microgrid or renewable energies, using [CAISO database](https://www.caiso.com/TodaysOutlook/Pages/supply.html). The database we are using is available on [Google Drive](https://drive.google.com/drive/folders/1cqqMndQwIuejJy_SCzBmd7CK1Xg8SMLS?usp=share_link).

# Requirements
Make sure you have these dependencies latest versions installed:

- [Scikit-learn](https://scikit-learn.org/stable/)
- [XG-Boost](https://xgboost.readthedocs.io/en/stable/)
- [Pandas](https://pandas.pydata.org/)
- [Matplotlib](https://matplotlib.org/)
- [Seaborn](https://seaborn.pydata.org/)

# Running the code
- ```1_Data_Acquisition.ipynb``` contains the code related the creation of the CSV (the code is cleaned and debugged).
- ```2_Exploratory_Data_Analysis.ipynb``` shows the analysis of input and output variables.
- ```3_Database.csv``` represents final database with relevant variables.
- ```4a_PV_Model_Training.ipynb``` Those are the algorithms to predict photovoltaic energy (XG-Boost, KNN, DT and Neuronal Networks).
- ```4b_Demand_Model_Training.ipynb``` Those are the algorithms to predict demand energy (XG-Boost, KNN, DT and Neuronal Networks).
- ```4c_Wind_Model_Training.ipynb``` Those are the algorithms to predict wind energy (XG-Boost, KNN, DT and Neuronal Networks).

# Screenshots

This a graph made with seaborn to identify which are the representative variables for the training of the algorithms.

<img src="https://user-images.githubusercontent.com/62435332/221738410-26d337e3-7b81-4fa9-9cbb-a0df4c6ced1a.png" alt="Logo" width="500" height="500">

# Authors
- [Paola Castro](https://github.com/C-Paola)
- [Sebastian Rojas](https://github.com/SRojas28)
- [Sergio Sepúlveda](https://github.com/serg-sepulveda)
- [Jhon Castro](https://github.com/jcastro295)
