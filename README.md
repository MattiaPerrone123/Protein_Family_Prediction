# Protein_Family_Prediction
The aim of the current project consists in predicting which families different proteins belong starting from features available in the Protein Data Bank (PDB). In the first part, this task has been accomplished using an LSTM trained on protein amino acids sequences, while in the second part, machine learning classification models, trained on a dataset including protein biophysical properties, were implemented. 

The project code is available in the file Protein_Family_Prediction.ipynb

## Dependencies
A list of the packages used for this project is included in the file Requirements.txt

## Dataset
Two public datasets from the Protein Data Bank are used for this project (see the folder Dataset). One of the two datasets (pdb_data_no_dups.csv) includes different protein biological properties as features (part 2), while the other one (pdb_data_seq.csv) includes the sequence of aminoacids that make up proteins (part 1).

## Images
This folder includes all the images that are given in output when the colab notebook is run. 

## Models
All the four classification machine learning models implemented were saved in the folder Models (ML_models.zip). These models include Knn, Decision Trees, Bagging and XGBoost. The LSTM model has not been saved in the folder Models because of its size. 

## Results 
The LSTM model performed better than the best machine learning classification model (XGBoost), with an increase of F1-score from 0.66 to 0.75 on the test set.

<p align="center">
  <img src=https://user-images.githubusercontent.com/98240588/209311410-da40a208-49ba-43b2-a741-c897dc3a183c.png>
</p>

A complete report of the project is presented in the file Protein_Family_Prediction_using_Classical_Machine_Learning_and_Deep_Learning.pdf
