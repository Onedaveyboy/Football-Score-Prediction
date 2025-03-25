# Football-Score-Prediction
# Score Prediction using Poisson Regression

This project implements a **Poisson regression model** to predict the outcome of football matches based on previous data. The model is trained to estimate the number of goals scored by each team in a match using features such as the home goals, away goals, match location (home/away), and more.

## Project Structure

`Score Prediction Poisson Regression Model.Rmd`: Main R Markdown file containing the code, explanations, and results.

## Overview

The main steps in the model development are:

1. **Data Loading & Cleaning**  
   Load historical premier league match data and prepare it for analysis (I get the data from here

2. **Exploratory Data Analysis (EDA)**  
   Visualize goal distributions and inspect home/away effects.

3. **Poisson Regression Modeling**  
   Fit a generalized linear model (GLM) with a Poisson family:
   - Model 1: Goals ~ Team + Opponent + Home/Away effect
   - Model 2: More refined versions with interaction terms or normalization

4. **Prediction & Evaluation**  
   Use the fitted model to predict goal probabilities and compute expected match outcomes (win/draw/loss probabilities).

## Key Features

- Models team strength and match dynamics using interpretable Poisson regression.
- Simulates match outcomes.
- Suitable for basic score prediction tasks or educational demonstration of statistical modeling in sports.

### Prerequisites

- R (>= 4.0.0)
- R packages:
  - `dplyr`
  - `ggplot2`
  - `tidyr`
  - `broom`
  - `MASS`
  - `knitr` (for rendering `.Rmd`)

### Run the Project

1. Open `Score Prediction Poisson Regression Model.Rmd` in RStudio.
2. Run all chunks or click "Knit" to render the document.
3. Adjust inputs or modify the model to fit other datasets.

## Notes

- This model assumes goal scoring follows a Poisson distribution.
- For real-world betting or forecasting, more features (like player injuries, weather, etc.) should be considered.

## Author

- **David William Shanks** – MSc Student, University of Bath  
  [GitHub Profile](https://github.com/Onedaveyboy)

---

*This project is independent research on statistical modeling in sports.*
