# Protein_Family_Prediction
The aim of the current project consists in predicting which families different proteins belong starting from features available in the Protein Data Bank (PDB). In the first part, this task has been accomplished using an LSTM trained on protein amino acids sequences, while in the second part, machine learning classification models, trained on a dataset including protein biophysical properties, were implemented. 

The project code is available in the file Protein_Family_Prediction.ipynb

## Dependencies
A list of the packages used for this project is included in the file Requirements.txt

## Dataset
Two public datasets from the Protein Data Bank are used for this project (see the folder Dataset). One of the two datasets (METTERE NOME.csv) includes different protein biological properties as features (part 2), while the other one (METTERE NOME.csv) includes the sequence of aminoacids that make up proteins (part 1).

## Models -> ASPETTO A VEDERE QUANTO CI IMPIEGO A CARICARLI SUL CLOUD
All the models implemented were saved in the folder Models. These models include linear regression models (Vanilla, Ridge, Lasso) and ensemble models (Bagging, Random Forest, XGBoost). The Model folder also includes a Random Forest Classifier (RFC) trained on the dataset before exploratory data analysis was conducted, in order to show the impact of EDA on the results obtained.

## Results -> ANCHE QUI LI FAREI ALLA FINE
EDA has significally improved the performances of the models (Random Forest MSE on the test set dimished by 12%).
Ensemble models showed much better performances with respect to linear regression. The best ensemble model (XGBoost) allowed to reduce MSE on the test set up to 31% with respect to the best regression model (Ridge).

A complete report of the project is presented in the file Protein Family Prediction using Classical Machine Learning and Deep Learning.pdf
