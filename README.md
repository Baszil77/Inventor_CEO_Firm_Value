# Inventor CEOs and Firm Value Analysis

## Overview
This repository documents my MSc Financial Technology project on how inventor CEOs impact firm value (Tobin’s Q). The analysis uses:
- **Stata** for summary statistics (results are in the final dissertation)
- **MATLAB's Regression Learner** for machine learning regressions (models saved as .mat files)
- The complete project for full details.

## Repository Structure
This repository is organized into several folders to keep all the components of my project clear and easy to navigate:

MATLAB_Code/
This folder contains the machine learning models I built using MATLAB’s Regression Learner. The models are saved as .mat files:

GPRModel.mat – Contains the Gaussian Process Regression model (the best performer).
EnsembleModel.mat – Contains the Ensemble Learning model.
NNModel.mat – Contains the Neural Network model.
SVMModel.mat – Contains the Support Vector Machine model.
Data/
This folder includes the data files used in the analysis:

master_file.csv – The raw dataset containing firm-level variables (e.g., R&D, Inventor CEO status, Total Assets, etc.).
result_table.csv – The CSV file with summary statistics and regression outputs.
Paper/
This folder holds the final written dissertation/report:

Final_Thesis.pdf – The complete dissertation detailing the methodology, analysis, and conclusions.
README.md
This file (what you’re reading now) explains the purpose of the repository, describes each folder and file, and provides instructions on how to use the project.


## MATLAB Models
Load a model in MATLAB with:
```matlab
load('MATLAB_Code/GPRModel.mat');  % Loads the GPR model (example)

Data Files
master_file.csv: Contains the raw firm-level data.
result_table.csv: Contains summary statistics and regression results.
Additional Notes
Summary statistics and correlations were generated in Stata (original code not available).
Refer to the Final_Thesis.pdf in the Paper/ folder for complete methodology and results.
How to Use
Clone or download this repository.
Open MATLAB and load the .mat files from MATLAB_Code/ to view the regression models.
Review the data in the Data/ folder and read the full report in the Paper/ folder.
