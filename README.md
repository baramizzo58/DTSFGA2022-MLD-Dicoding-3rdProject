# DTSFGA2022-MLD-Dicoding-Development-2ndProject
2nd Project of Machine Learning Developer (Learn Machine Learning Development Stage) Training in Fresh Graduate Academy Program (Digital Talent Scholarship 2022).

## Project Explanation
Creating Machine Learning Models with Time Series Data.

## Dataset
Using `data_gold_price.csv` that consist of 10,787 rows & 2 columns.

## Exploratory Data Analysis & Data Preparation
* Missing value check: not found
* Data Visualization
![image](https://github.com/baramizzo58/DTSFGA2022-MLD-Dicoding-Development-2ndProject/assets/119744134/780c879e-5bca-4ac3-a0a0-e7379a9abdee)
* Splitting 80:20
* Scaling: MinMaxScaler

## Modelling
* Using model architecture with CNN
* Model is compiled with `MAE` loss function & `adam` optimizer with `learning rate = 0.001`.
* Epochs: 100

## Result
* loss: 0.0116
* mae: 0.0116
* val_loss: 0.0601
* val_mae: 0.0601
