# Protein_Family_Prediction
The aim of the current project consists in predicting which families different proteins belong starting from features available in the Protein Data Bank (PDB). In the first part, this task has been accomplished using an LSTM trained on protein amino acids sequences, while in the second part, machine learning classification models, trained on a dataset including protein biophysical properties, were implemented. 

The project code is available in the file Protein_Family_Prediction.ipynb

## Dependencies
A list of the packages used for this project is included in the file Requirements.txt





## Dataset
The dataset used (Life_Expectancy_Data.csv) is a public dataset made available by the World Health Organization (WHO) for the purpose of health data analysis. 21 predictor variables for 193 countries from year 2000 to 2015 were considered to predict life expectancy. A description of the dataset features is included in the file Dataset_description.txt

## Models
All the models implemented were saved in the folder Models. These models include linear regression models (Vanilla, Ridge, Lasso) and ensemble models (Bagging, Random Forest, XGBoost). The Model folder also includes a Random Forest Classifier (RFC) trained on the dataset before exploratory data analysis was conducted, in order to show the impact of EDA on the results obtained.

## Results
EDA has significally improved the performances of the models (Random Forest MSE on the test set dimished by 12%).
Ensemble models showed much better performances with respect to linear regression. The best ensemble model (XGBoost) allowed to reduce MSE on the test set up to 31% with respect to the best regression model (Ridge).

A more detailed description of the project is presented in the file Life_Expectancy_Slides.pdf
