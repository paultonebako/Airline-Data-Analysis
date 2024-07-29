# Flight Fare Prediction Project and Analysis using Power BI

This project focuses on predicting flight fares using machine learning techniques and analyzing the flight dataset using Power BI for valuable insights. The dataset has been meticulously cleaned, transformed, and prepared to ensure optimal performance of predictive models. Various techniques have been applied to enhance accuracy, including the implementation of a Linear Regression model, a Random Forest Regressor, and hyperparameter tuning.

## Data Cleaning and Transformation

The flight dataset underwent comprehensive preprocessing to ensure data quality and suitability for model training:

- **Data Cleaning**: Missing values, duplicates, and irrelevant columns were removed to enhance the integrity of the dataset.
- **Feature Engineering**: New features such as day of the week, month, and time of day were derived from date-time features to capture temporal patterns.
- **Categorical Variable Encoding**: Categorical variables were encoded into numerical format using techniques such as one-hot encoding or label encoding to facilitate model training.
- **Feature Scaling**: Numerical features were scaled to a similar range to prevent bias in model training and to improve convergence speed.

## Models Implemented

### Linear Regression Model

An initial Linear Regression model was deployed to establish a baseline for predicting flight fares. While simplistic, this model provided insights into linear relationships between features and target variables.

### Random Forest Regressor

To further enhance prediction accuracy, a Random Forest Regressor was implemented. This ensemble learning technique harnesses the power of multiple decision trees to capture complex interactions within the data, leading to improved predictive performance.

### Hyperparameter Tuning

Hyperparameter tuning was conducted on the Random Forest Regressor to optimize model performance. Techniques such as grid search or random search were employed to identify the optimal combination of hyperparameters, resulting in a remarkable accuracy of 88.01%.


## Power BI Dashboard and Analysis

In addition to model building, a dynamic Power BI dashboard was developed to conduct in-depth analysis of the flight dataset:

- **Summary Statistics**: Provides an overview of key metrics such as average fare, route popularity, and distribution of fares.
- **Trend Analysis**: Visualizes fare trends over time, by route, and other relevant factors to identify seasonal variations and market trends.

Some snaps of the dashboard are attatched below-
![Screenshot 2024-03-08 035016](https://github.com/Sniperex/FLIGHT_FARE_PREDICTION/assets/52499633/1281c216-f404-449d-b6bc-797eb451d0f1)

![Screenshot 2024-03-08 034944](https://github.com/Sniperex/FLIGHT_FARE_PREDICTION/assets/52499633/e2ba9756-4de7-4c27-bfd3-14e7454f15f4)

## Contributors

- [Kashish Kumar Singh](https://github.com/Sniperex)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
