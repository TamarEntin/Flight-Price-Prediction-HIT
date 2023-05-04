# Flight Price Prediction

This project is focused on building a machine learning model to predict the price of airline tickets. The data is collected from  airlines and online travel agencies (OTAs) and includes information about the airline, route, date of travel, and other relevant factors.

## Data Collection

For data collection, we used selenium to crawl data from the 'www.il.kayak.com' website. The crawling process involved purchasing data from different ticket categories such as Cheapest, Best, and Quickest.

## Data Preprocessing

Before building the machine learning model, the data was cleaned and preprocessed. This included removing any duplicates, handling missing values, and encoding categorical variables. The data was then split into training and testing sets to evaluate the performance of the model.

## Model Building

Several machine learning algorithms were tested for this project, including linear regression, random forest, and gradient boosting. After testing various models and hyperparameters, a gradient boosting model was selected as the best performing model. This model was trained on the training data and evaluated on the testing data using various metrics such as mean absolute error and root mean squared error.

## Conclusion

In conclusion, this project demonstrates the potential for machine learning in predicting airline ticket prices. By accurately predicting prices, airlines and OTAs can improve their pricing strategies and increase revenue. While this project focused on a single airline market, the methodology can be applied to other markets and industries as well.
