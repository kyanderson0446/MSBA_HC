# HomeCredit Default Prediction Project
https://www.kaggle.com/competitions/home-credit-default-risk/overview
## Overview
This repository contains the files used for Exploratory Data Analysis (EDA) and modeling in the HomeCredit Kaggle project. The project goal was to identify **default** and **non-default** customers. The final result was to determine the **customers likelihood (%) of defaulting**.

The project was monitored by the University of Utah Master of Business Analytics program, in order to help graduate students practice modeling and cleaning data from a real company. I was assigned to a team of 4, where my contribution was mainly in the EDA and modeling portions of this project. Our main goal was to clean the data as much as possible before modeling. This took a lot of time but this is to be expected in any EDA. Once we had the confidence in the cleaning, we moved onto the modeling, with some reiterations of EDA.

### Business Context
By accurately predicting default probabilities, HomeCredit can make informed decisions about loan approvals and minimize financial losses. Achieving a high performing model on unseen data will allow HomeCredit to market and target customers directly and cut costs, dramatically.

## Project Description
Throughout, the task was to distinguish between default and non-default customers based on their credit history and other features. HomeCredit specializes in offering loans to individuals considered risky by traditional lenders but still capable of repayment.

Throughout the EDA process [EDA notebook](https://github.com/kyanderson0446/MSBA_HC/blob/549f5a8dc80ffc59d0ce85b6604465431d918afb/EDA/HC_EDA_code.ipynb), it became evident that handling missing values, imputing values, balancing the dataset through up/downsampling, and feature engineering were crucial to improving model performance.

## Visualizations
Numeric data types correlation plot to identify collinearity.

![Correlation Heatmap](https://github.com/kyanderson0446/MSBA_HC/blob/bfc2a49760c472eb364f95dbe361901256970488/EDA/EDA_heatmap.png)



## Findings
[Modeling notebook](https://github.com/kyanderson0446/MSBA_HC/blob/549f5a8dc80ffc59d0ce85b6604465431d918afb/Modeling/HC_Revised_Model.ipynb)

With preprocessing and feature engineering, the discrepancy between internal validation performance and Kaggle submission scores was obvious. The internal AUC achieved during model development was an impressive **0.97**. However, the Kaggle score, was considerably lower at **0.65**. This suggests that the model **may have overfit the training data or failed to generalize well to unseen data.**

## Repository Contents
    Notebooks: Contains Jupyter notebooks used for EDA, modeling, plots, and feature engineering
    Data: Read-in data from url
    Models: Random Forest and Gradient Boosting
    Visualizations: Commented out for performace, but heatmaps were used for correlation

## Technologies Used
    Python 3.11
    Pycharm Pro Jupyter Notebooks
    Pandas
    NumPy
    Scikit-learn
    Matplotlib
    Seaborn

# Next Steps and Conclusion
For this project, I would have liked to have had more collaboration with other teams as it became apparent that each team member was a **"Subject Matter Expert"**. This made collaboration difficult because each team member was working on their own part of the code and didn't get to see the full picture. Which is tough to ask but I ended up being that person. So for next time, I think having everyone work through the code together instead of chunks, would be helpful so everyone has the same base level understanding.
## Steps to improve model
To improve model performance and address the gap between internal validation and Kaggle scores:

    Tuning model hyperparameters
    Experimenting with different modeling techniques
    Feature engineer on a more granular level
    Gathering additional external data for better generalization, i.e. different joins
    Introducing more plots to visualize distributions and performance

### Contact Information
    Email: andersonkyle099@gmail.com
    LinkedIn: https://www.linkedin.com/in/kyleandersonopis2020/
