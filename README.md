# Short term load forecasting, using HUE and UK-dale datasets

## Description
Welcome, this is where you will find Python scripts with machine learning models for energy consumption prediction on HUE and UK-dale datasets. Datasets include energy consumption of combined 33 domestic households. The forecast was done using three different machine learning algorithms - XGBoost, Random Forest and Recurrent Neural Networks. That combination of models provides comparisons of performance between classical and deep learning models, as well as normal decision trees versus gradient boosted trees. The forecast could possibly be improved by adding some additional well tought out features, by trying out additional models or by better optimizing the existing ones.

## How to Install and Run the Project
The project was developed and tested using Google Colaboratory, so you do not need to install it. You do need to install some dependencies onto your google drive to go along with the code though. Upon running the program, you will be prompted to connect your google account and give the program access to your google drive. All of the files needed to run the code are under **Dependencies** in the repository. **Note! You have to store the files in google drive in a way to complement the code or change the file locations at the start of the program.**

## How to use the project
There is a seperate program for each of the two datasets. To use the project you can just run the code. This will run through the entire program, which means it will create the dataset and all of its features and train and test every single model. To make it easier to find what you are looking for or if you want to make any changes, the code can be split in three parts, which are:
1. Preparation of data for training
2. Training and testing the models
3. Reviewing the results
