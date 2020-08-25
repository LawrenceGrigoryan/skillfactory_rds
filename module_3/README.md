# Project 3 - TripAdvisor Rating Forecast

One of TripAdvisor's possible problems is restaurants which make fake reviews for higher rating. Creating a ML model to forecast restaurant's rating is a feasible solution.

If a restaurant has a rating score which significantly differs from the predicted one, it probably plays unfairly and deserves to be verified.

The main idea of this project is to clean messy dataset, create new features and get the lowest possible **Mean Absolute Error**.

The initial dataset contains the following columns:

The initial version of dataset consists of 10 columns containing the following information:

* Restaurant_id — id of a restaurant / restaurant chain;
* City — restaurant's location (city);
* Cuisine Style — cuisine which a dish can be related to;
* Ranking — restaurant's place in the ranking of all the cities' restaurants;
* Rating — the rating of a restaurant according to TripAdvisor (this is the target variable);
* Price Range — the price range of the restaurant;
* Number of Reviews — number of reviews for a restaurant on TripAdvisor;
* Reviews — info about two first reviews that are displayed on TripAdvisor;
* URL_TA — URL of restaurant's web-page on TripAdvosor;
* ID_TA — restaurant's id in TripAdvisor's Database.
