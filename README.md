House Price Classification Using Latitude and Longitude
Project Description

This project aims to classify house prices into categories based on their geographical location. By using Latitude and Longitude as input features, we attempt to predict the price group of a house. The goal is to explore whether the location is a good indicator of house unit prices.

The dataset contains information about transaction year, house age, distance to MRT stations, number of convenience stores nearby, latitude, longitude, and house unit prices.

The project demonstrates practical skills in data preprocessing, categorization, classification, model training, prediction, evaluation, and visualization.

Dataset

Source: house_prices.csv

Number of columns: 7 (plus additional classification columns added in preprocessing)

Fields:

Transaction: Year of sale

House age: Age of the house in years

Distance to MRT station: Distance from nearest MRT station

Number of convenience stores: Number of stores nearby

Latitude and Longitude: Geographical coordinates

House unit price: Price per unit area

Derived columns:

Class: Price category bins (15 bins)

Class id: Numerical code for the price category

Key Features

Price Binning: House prices divided into 15 categories to simplify classification.

Geographical Prediction: Latitude and Longitude used to predict house price category.

Machine Learning Model: K-Nearest Neighbors (KNN) classifier to assign price groups.

Evaluation Metrics: Accuracy score for classification and R-squared score for predicted unit prices.

Visualization: Scatter plots and heatmaps to visualize predictions and price distribution.

Python Implementation: Uses pandas, scikit-learn, and matplotlib for analysis and visualization
Conclusion

From this project, we observed that the geographical location of a house moderately influences its price.

The KNN classifier achieved approximately 40% classification accuracy, indicating that location alone provides some predictive power but is not sufficient for perfect classification.

The R-squared score of 0.66 shows that latitude and longitude explain a significant portion of price variation, but including additional features such as house age, distance to MRT, and nearby stores would improve prediction.

Visualizations reveal that higher-priced houses cluster in certain areas, while lower-priced houses are spread differently.<img width="613" height="702" alt="ad3" src="https://github.com/user-attachments/assets/d41dbb2b-08dd-4564-ba76-d9cd9d90a06f" />
<img width="645" height="365" alt="ad4" src="https://github.com/user-attachments/assets/419f8d2e-0247-4663-a09e-2aef3017a5c1" />
