# Predicting Heart Disease using Machine Learning

## Overview

This project aims to predict whether a person is vulnerable to heart disease based on their attributes like age, sex, heart rate, etc. It employs machine learning techniques and data science concepts to classify individuals into categories of having or not having heart disease.

## Datasets

The dataset used for this project is sourced from the following repositories:

- [Heart Disease Dataset (UCI)](https://archive.ics.uci.edu/ml/datasets/Heart+Disease): This dataset is available from the UCI Machine Learning Repository and contains various clinical parameters of patients, including age, sex, chest pain type, resting blood pressure, serum cholesterol levels, and other relevant features.

- [Heart Disease Classification Dataset (Kaggle)](https://www.kaggle.com/datasets/sumaiyatasmeem/heart-disease-classification-dataset): This dataset, available on Kaggle, provides a formatted version of the heart disease dataset from the UCI repository, making it convenient for analysis and modelling.

## Machine Learning Modelling Framework

The project follows a 6-step machine learning modelling framework:

1. **Problem Definition:** The task is framed as a binary classification problem where the goal is to predict whether a patient has heart disease or not based on their clinical attributes.

2. **Exploratory Data Analysis (EDA):** The dataset is explored to gain insights and understand the distribution of features, identify correlations, and handle missing or inconsistent data.

3. **Model Training:** Various machine learning models are trained using the dataset to learn patterns and make predictions about heart disease status.

4. **Model Evaluation:** The performance of the trained models is assessed using problem-specific evaluation metrics to determine their accuracy, precision, recall, and other relevant measures.

5. **Model Comparison:** Different models are compared to identify the most effective one in terms of predictive accuracy and generalization.

6. **Model Fine-Tuning:** Techniques such as hyperparameter tuning and feature selection are applied to improve the performance of the chosen model further.

## Features

The features used for predicting heart disease include:

- Age
- Sex (1 = male; 0 = female)
- Chest pain type
- Resting blood pressure
- Serum cholesterol levels
- Fasting blood sugar
- Resting electrocardiographic results
- Maximum heart rate achieved
- Exercise-induced angina
- ST depression induced by exercise relative to rest
- The slope of the peak exercise ST segment
- Number of major vessels colored by fluoroscopy
- Thalium stress resul

## Environment Setup

To replicate the environment for running this project, follow these steps:

1. **Download and Install Miniconda:**
   - Go to the [Miniconda Downloads page](https://docs.anaconda.com/free/miniconda/index.html).
   - Download the appropriate version (32- or 64-Bit) of Miniconda for your operating system.
   - Double click on the downloaded `.exe` file and follow the installation prompts.
   - Read and agree to the licensing terms.
   - Select the installation location. By default, Anaconda should try to install in your home directory. It's recommended to accept this default.
   - Do not add Anaconda to the PATH environment variable unless necessary, as it can interfere with other software.
   - Complete the installation process.

2. **Create a Conda Environment:**
   - Open the Anaconda Prompt (miniconda3) from the Start Menu or search for it.
   - Create a new Conda environment by running the following command:
     ```
     conda create --name heart-disease-env
     ```
   - Activate the environment using the following command:
     ```
     conda activate heart-disease-env
     ```

3. **Install Jupyter Notebook:**
   - In the activated Conda environment, install Jupyter Notebook by running:
     ```
     conda install jupyter
     ```
   - When prompted with 'Proceed ([y]/n)?', type `y` and hit Enter to confirm.

4. **Install Required Packages:**
   - Install necessary Python packages using pip. Run the following commands one by one:
     ```
     pip install pandas
     pip install scikit-learn
     pip install matplotlib
     pip install seaborn
     pip install nltk
     pip install beautifulsoup4
     ```

5. **Verify Installation:**
   - You can check if the packages are installed correctly by starting Python in your Anaconda Prompt:
     ```
     python
     ```
   - Import each package on a separate line or take a shortcut and import them all at once:
     ```
     import pandas
     import sklearn
     import matplotlib
     import seaborn
     import nltk
     import bs4
     ```

6. **Run Jupyter Notebook:**
   - Once all packages are installed, launch Jupyter Notebook by running:
     ```
     jupyter notebook
     ```
   - A Jupyter Notebook interface will open in your default web browser, allowing you to navigate to the project directory and start working on the project.

By following these steps, you'll have set up a virtual environment with all the necessary dependencies to run the heart disease prediction project.

## Conclusion

This project demonstrates the application of machine learning techniques in healthcare for predicting heart disease risk based on patient attributes. By leveraging a comprehensive dataset and following a systematic modelling framework, it provides insights into the factors influencing heart health and facilitates informed decision-making in clinical settings.