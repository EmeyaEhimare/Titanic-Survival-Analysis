## Titanic Dataset Survival Analysis

![Titanic Departure](Titanic%20au%20d%C3%A9part.jpg)

## Overview

This repository contains an in-depth analysis of the Titanic dataset, which includes information about passengers who were on board the Titanic during its ill-fated voyage. The analysis explores various aspects of the dataset, including survival rates, the influence of passenger attributes on survival, and the development of a linear regression model to predict survival. The project aims to provide valuable insights into the factors that affected passenger survival during this historic event.

## Table of Contents

1. [Introduction](#introduction)
2. [Project Objectives](#project-objectives)
3. [Data Exploration](#data-exploration)
4. [Key Findings](#key-findings)
5. [Additional Insights](#additional-insights)
6. [Linear Regression Model](#linear-regression-model)
7. [Usage](#usage)
8. [Contributing](#contributing)
9. [License](#license)

## Introduction

The Titanic Dataset Survival Analysis project explores and analyzes the Titanic dataset, which contains information about passengers on the Titanic. The analysis provides insights into factors influencing passenger survival and includes data visualization and a linear regression model for survival prediction.

![Titanic Departure](Titanic%20au%20d%C3%A9part.jpg)

## Project Objectives

The primary objectives of this analysis include:

- Data exploration and understanding of the dataset's structure.
- Calculation and visualization of overall survival rates.
- Investigation of the relationship between ticket class (Pclass) and survival.
- Analysis of the impact of gender on passenger survival.
- Exploration of age and its correlation with survival.
- Examination of the influence of siblings/spouses (SibSp) on survival.
- Investigation of the port of embarkation's effect on survival.
- Evaluation of the correlation between fare and survival.
- Assessment of the correlation between age and ticket class.
- Building a linear regression model for survival prediction.

## Data Exploration

The data exploration phase involves checking for missing values, exploring categorical and numerical data, and visualizing relationships between features. Key insights include:

- Survival rate: Approximately 38.38% of passengers survived.
- Ticket class: First-class passengers had a higher survival rate.
- Gender: Females had a higher survival rate than males.
- Age: The average age of survivors was around 28 years.
- Siblings/Spouses: Passengers with one sibling or spouse had the highest survival rate.
- Port of Embarkation: Passengers from Cherbourg had a higher survival rate.
- Fare: Paying a higher fare weakly correlated with better survival.

## Key Findings

This section provides a summary of the key findings from the analysis, including survival rates by ticket class and gender, average age of survivors and non-survivors, and the impact of siblings/spouses and port of embarkation on survival.

## Additional Insights

In addition to the main findings, the analysis uncovers additional insights, such as the age distribution of passengers and the higher survival rate of passengers embarking from Cherbourg. These insights provide a deeper understanding of the dataset.

## Linear Regression Model

The project includes the development of a linear regression model to predict passenger survival. The model incorporates features such as ticket class, gender, siblings/spouses, fare, and parents/children. However, the model's accuracy score is 0.35, indicating potential areas for improvement.

## Usage

To replicate this analysis or explore the code, follow these steps:

1. Clone the repository to your local machine using `git clone`.
2. Ensure you have Python and required libraries installed (NumPy, pandas, matplotlib, seaborn, scikit-learn).
3. Run the Jupyter Notebook file `Titanic_Survival_Analysis.ipynb` to reproduce the analysis.

## Contributing

If you would like to contribute to this project or suggest improvements, please feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
