# Uber and Lyft Price Prediction

** by Yijia Xue, Data Science Initiative, Brown University

## Overview

This research project presents a detailed comparative analysis of Uber and Lyft's pricing models in Boston, using a dataset of 693,071 rideshare instances. The study's motivation stems from understanding these models' dynamics for informed decision-making in urban transportation. Key features analyzed include weather conditions, ride details, and temporal factors, with 'price' as the target variable. Extensive Exploratory Data Analysis (EDA) reveals patterns in ride frequency, geographical distribution, and price variations. The project employs machine learning techniques, including Ridge, Elastic Net, Random Forest, and XGBoost regressions, with XGBoost showing the best performance in terms of R2 and RMSE. Feature importance analysis identifies distance and luxury ride categories as significant predictors. The research suggests future work integrating real-time data and exploring other models like KNN regression for improved accuracy. This comprehensive study aids in understanding the intricate factors influencing ride-sharing prices and assists in selecting cost-effective transportation options.

## Repo Intro

The project is built in Python 3.9.13 and repository organization is as follows:

*** Project Directory Structure ***

- `data/`
  - Stores all raw and preprocessed data files.

- `figures/`
  - Stores all visualizations, from EDA to model result comparisons.

- `results/`
  - Contains trained models and comparison results.

- `report/`
  - Reports on development pipeline, methodology, and model results.

- `src/`
  - Contains all the code:
    - `Project`: Data wrangling, EDA, and feature engineering.
    - `Project_phase2.ipynb`: Splitting, preprocessing, and model development; model evaluations; result visualization; and feature importances.


## Environment and Required Packages
The requirement is stated in the environment.yml file. You can now use this file to create a conda environment with all the necessary packages by running: conda env create -f environment.yml
