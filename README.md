# Titanic Dataset Survival Analysis

![Titanic](https://upload.wikimedia.org/wikipedia/commons/thumb/f/fd/RMS_Titanic_3.jpg/800px-RMS_Titanic_3.jpg)

## Introduction and Objectives

This project aims to explore and gain insights from the Titanic dataset, which contains information about passengers who were on board the ill-fated Titanic. The primary objectives of this analysis are as follows:

1. **Data Exploration:** Understand the dataset's structure, examine missing values, and explore the distribution of key variables, such as age, gender, ticket class, and more.

2. **Survival Rate:** Calculate and visualize the overall survival rate of passengers on the Titanic.

3. **Ticket Class (Pclass) and Survival:** Investigate how the ticket class of passengers relates to their chances of survival.

4. **Gender and Survival:** Analyze the impact of gender on passenger survival, including correlation statistics.

5. **Age and Survival:** Determine the average age of survivors and non-survivors and visualize age distributions.

6. **Siblings/Spouses (SibSp) and Survival:** Explore whether the presence of siblings or spouses affected a passenger's survival rate.

7. **Port of Embarkation and Survival:** Investigate if the port from which passengers embarked had any influence on their chances of survival.

8. **Fare and Survival:** Examine the correlation between passenger fares and their likelihood of survival.

9. **Age and Ticket Class Correlation:** Explore whether there is a correlation between a passenger's age and their ticket class.

10. **Linear Regression Model:** Attempt to build a linear regression model to predict passenger survival based on various features.

This analysis provides valuable insights into the factors that influenced the survival of Titanic passengers and helps us better understand this historical event.

## Project Overview

This project involves data analysis and modeling tasks to explore the Titanic dataset. Here's an overview of the project's structure:

1. **Data Preparation:** Reading the dataset, handling missing values, and encoding categorical features.

2. **Exploratory Data Analysis (EDA):** Analyzing the dataset to understand its characteristics, visualize distributions, and discover patterns.

3. **Data Visualization:** Creating informative visualizations to illustrate key findings and relationships in the data.

4. **Data Modeling:** Building machine learning models, including linear regression and K-Nearest Neighbors (KNN), to predict passenger survival.

5. **Model Evaluation:** Assessing the performance of the predictive models and interpreting their results.

6. **Model Deployment:** Saving the KNN model for deployment and making predictions on new passenger data.

## Repository Structure

The project's repository is organized as follows:

- `data/`: Directory containing the Titanic dataset (train.csv and test.csv).
- `notebooks/`: Jupyter notebooks with detailed code and analysis for each project phase.
- `images/`: Images and visualizations generated during data analysis.
- `titanic_survival_model.joblib`: Saved KNN model for survival prediction.
- `README.md`: This readme file summarizing the project.

## Usage

To explore this project, you can follow these steps:

1. Clone this GitHub repository to your local machine.

2. Open and run the Jupyter notebooks in the `notebooks/` directory to see the detailed analysis, code, and visualizations.

3. Load the saved KNN model (`titanic_survival_model.joblib`) if you want to make predictions on new passenger data.

## Conclusion

This project provides a comprehensive analysis of the Titanic dataset, offering insights into the factors that influenced passenger survival. Whether you're interested in data analysis, machine learning, or historical events, this project offers valuable knowledge and code that you can explore and learn from.

Feel free to reach out if you have any questions or suggestions for improvements. Happy exploring!

*Note: This readme file provides a high-level overview of the project. For in-depth analysis and code, please refer to the Jupyter notebooks in the `notebooks/` directory.*
