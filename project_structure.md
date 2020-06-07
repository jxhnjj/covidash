# COVID-19 Exploratory Data Analysis

## Data Preprocessing and Collection

- Data from the John Hopkins University Dataset on GitHub
- https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data/csse_covid_19_time_series

## Data Visualization

- Global outbreak analysis

- Showing worst affected countries side by side for a direct comparison 

- Plotting chloropleths of the world map, for a nice interactive visualization (show details on hovering over the country)

- Data for each of the top 5 countries to be analyzed
    - Plot number of confirmed cases each day - 1 graph
    - Plot number of deaths each day - 1 graph
    - Percentage growth - 1 graph
    - Recovery rate - 1 graph
    - Clickable chloropleth ( if possible )

## Predictions

- Software to be used - Tensorflow, keras, sklearn

- Predictions for each country
    - Predict confirmed cases
    - Predict confirmed deaths
    - Recovery rate
    - Percentage growth

- Models we can use:
    - Decision tree regressor
    - Random forest regressor
    - XGBoost regressor

- For each model, we must do these stuff
    - Plot predictions against actual values
    - Hyperparameter tuning for each model using GridSearchCV

- Artificial Neural Network
    - Try and maximize the accuracy for each country

## Plotly Dash

- To make an interactive dashboard, and display everything we analyzed, and everything we predicted

### Notes
- Add screenshots of the project taken at different times (to prove values are not hard coded)
