# Seattle Weather Markov Forecast

This repository contains code and analysis for Project 2 (MATH 178) by Haydon Behl. My task was to develop, simulate, and validate Markov chain models to predict Seattle’s daily weather.

## Contents

- `data/`  
  - `seattle-weather.csv`: Daily weather observations (2012–2018) from Kaggle.

- `weather_model.ipynb`  
  - Loads and preprocesses the data.  
  - Performs EDA: summary statistics, correlation heatmap, monthly trends.  
  - Builds both basic and composite‑state transition tables.
  - Runs validation loops for:  
    1. First‑order Markov chain baseline  
    2. Composite (weather, month) Markov chain  
  - Reports accuracy for each model.

- `Project_Report.pdf`  
  - Written report with introduction, model intuition, code snippets, results, and interpretation.

## How to Run

1. Clone the repository.
2. Install the required dependencies to your environment.

`pip install -r requirements.txt`
2. Open weather_model.ipynb in a Jupyter Notebook server to view and execute code. 
