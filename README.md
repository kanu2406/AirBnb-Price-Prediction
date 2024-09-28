# Airbnb Price Prediction in NYC (2019)

## Project Overview
This project aims to predict the prices of Airbnb listings in New York City (NYC) using various regression techniques. We employ a dataset from 2019 that contains listings, host details, geographical information, and other metrics relevant to pricing. By exploring the relationships between these features and the listing prices, we hope to develop accurate predictive models and identify the most influential factors affecting Airbnb pricing.

## Dataset
The dataset used in this project consists of Airbnb listings for New York City, covering various boroughs and neighborhoods. The dataset contains **48,895 rows** and **16 columns** with detailed information on:

- **Listing ID**: Unique identifier for each Airbnb listing.
- **Host Information**: Including host ID and host name.
- **Location Data**: Neighborhood group (borough), neighborhood, latitude, and longitude.
- **Room Type**: The type of room (e.g., private room, shared room, or entire home/apt).
- **Price**: The target variable we aim to predict (price per night in USD).
- **Other Metrics**: Minimum nights, number of reviews, review dates, availability, etc.

### Dataset Columns:
- `id`: Unique identifier of the Airbnb listing.
- `name`: Name of the listed property.
- `host_id`: Unique ID of the host.
- `host_name`: Name of the host.
- `neighbourhood_group`: Region or borough in NYC (e.g., Brooklyn, Manhattan).
- `neighbourhood`: Specific neighborhood where the property is located.
- `latitude`: Latitude of the property.
- `longitude`: Longitude of the property.
- `room_type`: Type of room offered (Private room, Shared room, Entire home/apt).
- `price`: Price per night in USD.
- `minimum_nights`: Minimum number of nights required for a booking.
- `number_of_reviews`: Total number of reviews received.
- `last_review`: Date of the most recent review.
- `reviews_per_month`: Average number of reviews per month.
- `calculated_host_listings_count`: Number of properties listed by the host.
- `availability_365`: Number of days the listing is available in a year.

## Project Aim
The goal of this project is to predict Airbnb listing prices using features such as neighborhood, room type, availability, and more. Additionally, we aim to analyze which features are the most significant in determining Airbnb prices. 

To achieve this, we will:
1. Apply different regression algorithms to model and predict listing prices.
2. Compare the performance of these algorithms based on evaluation metrics.
3. Investigate the most influential features affecting price prediction.

## Techniques Used
The project utilizes various regression techniques to predict the prices:

1. **Linear Regression**: A basic linear approach to model the relationship between features and price.
2. **Ridge Regression**: A variation of linear regression with L2 regularization to prevent overfitting.
3. **LASSO Regression**: A variation of linear regression with L1 regularization to enforce feature sparsity.
4. **Decision Trees**: A non-linear algorithm that models decisions based on feature splits.
5. **AdaBoost**: An ensemble learning technique that improves performance by combining weak learners.
6. **XGBoost**: An advanced gradient boosting algorithm known for its performance in predictive tasks.
7. **Neural Networks**: Deep learning-based models to capture complex non-linear relationships in the data.

## Performance Evaluation
We will evaluate the performance of each regression model using the following metrics:
- **Mean Absolute Error (MAE)**
- **Mean Squared Error (MSE)**
- **Root Mean Squared Error (RMSE)**
- **R-squared (R²)**

These metrics will help us compare the effectiveness of each model and assess how well the predicted prices align with the actual Airbnb listing prices.

## Dataset
This dataset was taken from [Kaggle](https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data). 

