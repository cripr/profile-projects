# FIFA World Cup 2026 Prediction Model

## Overview

This project is developed by a four-member team from the **Michigan Data Science Team (MDST)** at the University of Michigan. Our goal is to use historical international soccer data and statistical modeling to predict team performance in the 2026 FIFA World Cup.

We explore how factors such as possession, goals, assists, defensive discipline, and player statistics relate to a national team's performance.

## Data Collection

We analyze historical team statistics from major international tournaments, including:

- **FIFA World Cup:** 2018 and 2022
- **UEFA European Championship:** 2020 (played in 2021) and 2024
- **Copa América:** 2021 and 2024

Our dataset includes variables such as:

- Average player age
- Ball possession percentage
- Goals and assists per 90 minutes
- Non-penalty goals
- Yellow and red cards
- Matches played and playing time

## Methodology

### 1. Data Cleaning and Preprocessing
We organize historical tournament statistics into a consistent dataset, handle missing values, and normalize performance metrics to make comparisons across teams and tournaments more meaningful.

### 2. Exploratory Data Analysis
We use visualizations and correlation heatmaps to identify relationships between team statistics and tournament performance. We also examine multicollinearity to understand which features may contain overlapping information.

### 3. Predictive Modeling
We use **multiple linear regression** to examine how different team statistics contribute to performance and generate predictions for the 2026 World Cup.

### 4. Model Evaluation
We evaluate our model using historical data and compare predictions with actual outcomes to understand its accuracy, limitations, and potential improvements.

## Technologies

- **Python:** Data processing and statistical analysis
- **Pandas and NumPy:** Data cleaning and numerical computation
- **Matplotlib and Seaborn:** Data visualization and correlation analysis
- **Scikit-learn:** Regression modeling and evaluation

## Project Goals

- Identify statistical factors associated with international soccer success.
- Build an interpretable model for predicting national team performance.
- Compare teams using historical tournament data.
- Explore how data science can support sports analytics and forecasting.

## Limitations

Soccer outcomes are influenced by factors that historical statistics cannot fully capture, including injuries, tactical changes, team chemistry, and unexpected match events.

Our predictions are statistical estimates rather than guaranteed tournament outcomes.



## Project Status

In development. Model results and 2026 World Cup predictions will be added as the project progresses.
