# CokeQualityPrediction
Methodology for estimating the M80 durability parameter for foundry coke.

## Problem Description

The aim of this project is to develop a predictive model capable of forecasting the M80 strength parameter for foundry coke. Modelling is based on the quality parameters of the raw materials used (coal and coke dust) and on the parameters related to the coking process.

## Input Data

The training set consists of independent variables that can be divided into two parts:

Data describing the parameters of the batch mixture:

- 'Wrt_34', 'Ad_34', 'Vdaf_34', 'RI_34', 'T1_34', 'T2_34', 'T3_34', 'a_34', 'b_34', 
- 'Wrt_35', 'Ad_35', 'Vdaf_35', 'RI_35', 'T1_35', 'T2_35', 'T3_35', 'a_35', 'b_35', 
- 'Wrt_37', 'Ad_37', 'Vdaf_37', 'RI_37', 'T1_37', 'T2_37', 'T3_37', 'a_37', 'b_37',
- 'Wrt_K', 'Ad_K', 'Vdaf_K', '<0,2>_K', '0,2-0,5_K', '0,5-1,0_K', '1,0-3,15_K', '>3,15_K'.

Data describing the coking process:

- 'Number_of_ovens', 'Coking_time', 'Temp_min', 'Temp_max', 'Temp_avg', 'Temp_sd', 'Pressure_avg', 'Pressure_sd'.

The dependent variable is 'M80', the most crucial strength parameter of foundry coke, tested using the Micum method.

## Requirements

To run Jupyter notebooks, you need a Python environment with the appropriate libraries installed. The [Anaconda](https://www.anaconda.com/products/distribution) distribution is recommended.

To execute this project, you will need the following libraries:

- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn
- xgboost
- tensorflow
- keras
- sys
- os
- pickle
- time

## Usage

The project consists of Jupyter Notebook files, which can be run locally on your own computer. Simply clone this repository, install the required libraries, and open the notebooks in Jupyter.

## Authors

The project is author's original work.

# License
All rights to this project are reserved. The code is available for demonstration purposes only and its further use, distribution, or modification is not allowed without the explicit consent of the author.
