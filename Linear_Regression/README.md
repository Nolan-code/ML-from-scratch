#  Linear Regression - Bike Count Prediction

## Project Description
First implementation of linear regression from scratch to predict bike rental counts based on environmental features. This project includes feature selection, model training, and comprehensive visualization. The model is first implemented using libraries and then manually from scratch. The goal of the manual implementation is to deepen my understanding of linear regression.

## Key Features
- Feature Selection: from multiple environmental factors
- Linear Regression: implementation with sklearn library and manual implementation
- Performance Comparison between different feature sets
- Data Visualization with matplotlib and pandas

## Selected Features
| Feature       | Description           | Impact |

| `Bike_count`  | Target variable       | 
| `Temp`        | Temperature           |  High impact 
| `Humidity`    | Humidity level        |  Moderate 
| `Dew_pt_temp` | Dew point temperature |  Moderate 
| `Radiation`   | Solar radiation       |  Moderate 
| `Rain`        | Rainfall              |  Moderate 
| `Snow`        | Snowfall              |  Moderate 

## Results Summary with sklearn library
- R² score of 0.44 with only the temperature as a feature
- R² score of 0.34 with all the selected features
The other features might reduce the performance of the trained model

## Results Summary with manual implementation
- R² score of 0.42 with only the temperature as a feature
- R² score of 0.44 with all the selected features
This time, unlike the first implementation, the result seems to be quite similar (when considering only the temperature as a feature or all the selected features) even after multiple tries to find the best learning rate and number of iterations on average.
