# HomeCredit Default Prediction Project

## Overview
This repository contains the files used for Exploratory Data Analysis (EDA) and modeling in the HomeCredit Kaggle project. The project goal was to identify default and non-default customers to help HomeCredit make decisions about offering loans to risky individuals. The final result was to determine their percentage likelihood of defaulting.

## Project Description
In the HomeCredit Kaggle project, the task was to distinguish between default and non-default customers based on their credit history and other relevant features. HomeCredit specializes in offering loans to individuals considered risky by traditional lenders but still capable of repayment.

Throughout the EDA process, it became evident that handling missing values, imputing values, balancing the dataset through up/downsampling, and feature engineering were crucial to improving model performance.

## Findings
With preprocessing and feature engineering, the discrepancy between internal validation performance and Kaggle submission scores was obvious. The internal AUC achieved during model development was an impressive 0.97. However, the Kaggle score, was considerably lower at 0.65. This suggests that the model may have overfit the training data or failed to generalize well to unseen data.

## Repository Contents
    Notebooks: Contains Jupyter notebooks used for EDA, preprocessing, feature engineering, and model training.
    Data: Includes the dataset(s) used in the project.
    Models: Optionally, this directory can contain saved models or scripts for model deployment.
    Visualizations: Contains visualizations generated during the EDA process.

## Technologies Used
    Python 3.11
    Pycharm Pro Jupyter Notebooks
    Pandas
    NumPy
    Scikit-learn
    Matplotlib
    Seaborn

## Next Steps
To improve model performance and address the gap between internal validation and Kaggle scores:

    Tuning model hyperparameters
    Experimenting with different modeling techniques
    Feature engineer on a more granular level
    Gathering additional external data for better generalization, i.e. different joins
    Introducing more plots to visualize distributions and performance

### Contact Information
    Email: andersonkyle099@gmail.com
    LinkedIn: https://www.linkedin.com/in/kyleandersonopis2020/
