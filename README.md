# Video Game Sales Prediction

## Overview
This project aims to predict global sales of video games using regression models. It involves building a regression model based on features such as platform, genre, and publisher.

## Contents
- `Video_Game_Sales.ipynb`: Jupyter notebook containing the project.
- `Video_Game_Sales.csv`: Dataset used for analysis.

## Features
- `Rank`: Ranking of the video game.
- `Name`: Name of the video game.
- `Platform`: Gaming platform on which the game was released.
- `Year`: Release year of the game.
- `Genre`: Genre of the video game.
- `Publisher`: Publisher of the video game.
- `NA_Sales`, `EU_Sales`, `JP_Sales`, `Other_Sales`: Sales figures in different regions.
- `Global_Sales`: Total global sales of the video game.

## Preprocessing
- Handling missing values in `Year` and `Publisher` columns.
- Checking for and removing duplicates.
- Identifying and handling outliers.
- Reviewing and handling inconsistencies in categorical values.

## Data Exploration
- Descriptive statistics and distribution analysis of global sales.
- Visualization of global sales trends over the years.
- Analysis of global sales distribution by genre.

## Feature Engineering
- Logarithmic and Box-Cox transformations for target variable (`Global_Sales`).
- Encoding categorical variables.
- Splitting data into features and target variable.

## Model Building
- Preprocessing numerical and categorical features.
- Building pipelines for Random Forest and Gradient Boosting regression models.
- Training and evaluating models using cross-validation.

## Results
- Evaluation of models based on Mean Absolute Error, Mean Squared Error, and R-squared.
- Selection of the best performing model for prediction.

## Conclusion
- The selected model performs well in predicting global sales of video games.
- Further refinement and experimentation may improve model performance.
