# Drilling Rate of Penetration Prediction

## Overview
This project focuses on predicting the drilling rate of penetration (ROP) in the context of drilling operations. ROP is a critical parameter in drilling engineering that indicates the rate at which a drill bit penetrates the rock formations during drilling operations. By accurately predicting ROP, drilling operations can be optimized for efficiency and cost-effectiveness.

## Dataset
The dataset used in this project contains various drilling parameters along with the ROP. Here are the variables included in the dataset:
- DEPTH
- ROP
- WOB (Weight on Bit)
- CO2 (Carbon Dioxide)
- CH4 (Methane)
- H2S (Hydrogen Sulfide)
- TEMPIN (Temperature In)
- TEMPOUT (Temperature Out)
- FRACT
- MUDLOSS
- QUARTZIT
- CALCITE
- PYRITE
- HEMATITE
- EPIDOTAL
- CHLORITE
- ANHYDRIT
- SERICITE
- PP
- SPM1
- SPM2
- FLOWIN
- FLOWOUT%
- GAINLOSS
- RPM (Rotations Per Minute)
- TORQUE
- PITVOL (Pit Volume)
- TUFFASH
- RHYOLITE
- BASALT
- VOLCAN
- ANDESITE
- DACITE
- TUFFCRYS
- VOLCSEDI
- CHERTARG
- MARL
- CLAYST%
- CLAY%
- SILTST%
- SANDST%
- SAND%
- MEDSAND%
- CRSSAND

## Tech Stack
- numpy
- pandas
- matplotlib
- seaborn
- datetime
- scikit-learn (for machine learning models)
- pprint
- math
- Bokeh for visualisation

## Machine Learning Models
This project utilizes the following machine learning models for ROP prediction:
- Random Forest Regressor
- Support Vector Regressor
- Multi-layer Perceptron Regressor

## Evaluation Metrics
The performance of the models is evaluated using various metrics including:
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R-squared (R2) Score
- Explained Variance Score
