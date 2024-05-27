# Car Price Prediction Model

## Objective
The goal of this project is to build the best possible price prediction model using the provided car pricing dataset. This task simulates a "data challenge" for an analytics position, showcasing how to work with data and construct a regression prediction model.

## Data
The dataset contains thousands of records representing actual cars and their attributes. The target variable of interest is the **Manufacturer Suggested Retail Price (MSRP)**. The dataset can be found in the file `car_pricing_data.csv`.

## Project Structure
This project is divided into two main parts:

### Part 1: Data Preparation and Exploration

#### Background Information
- **Problem Definition:** The problem is to predict the MSRP of cars based on their attributes.
- **Interested Parties:** Potential employers, car manufacturers, dealerships, and data scientists.
- **Outline of Tasks:**
  1. Data cleaning and preparation.
  2. Feature selection and engineering.
  3. Data visualization.
  4. Model training and evaluation.

#### Data Preparation
- **Duplicate Records:** Check for and remove duplicate records.
- **Outlier Detection:** Identify and treat outliers.
- **Missing Values:** Handle missing values appropriately.
- **Categorical Variables:** Convert categorical variables to binary variables.
- **Feature Selection:** Identify the best features for predicting MSRP.

#### Train/Test Split
Split the data into training and testing sets to evaluate model performance.

#### Data Visualizations
Include multiple plots (histograms, bar charts, box plots, scatter plots) to explore the data. Three interesting graphs will be highlighted with explanations.

### Part 2: Model Training and Evaluation

#### Simple Regression Model
- Train and test a model with one explanatory variable.
- Calculate the r^2, adjusted r^2, Mean absolute error (MAE), Mean Absolute Percentage Error (MAPE) for training and test data.
- Check for over-fitting and interpret the model parameter.

#### Two-Feature Regression Model
- Train and test a model with one continuous numerical feature and one categorical variable.
- Calculate the r^2, adjusted r^2, Mean absolute error (MAE), Mean Absolute Percentage Error (MAPE) for training and test data.
- Check for over-fitting and interpret two model parameters.

#### Final Regression Model
- Train and test a model with multiple features.
- Explore transformations and interactions between features.
- Calculate the r^2, adjusted r^2, Mean absolute error (MAE), Mean Absolute Percentage Error (MAPE) for training and test data.
- Check for over-fitting.

### Conclusion
Answer the following questions:
- Satisfaction with the final model's performance.
- Proposed next steps.
- Changes for future iterations.
- Insights for business leadership in the automotive industry.

## Installation
To run this project, you will need the following libraries:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- statsmodels
- plotly
