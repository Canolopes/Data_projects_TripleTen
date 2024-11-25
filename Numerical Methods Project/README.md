# Numerical Methods Project

Another one of my favorites, this project involved testing with more advanced models like gradient boosting. I was tasked with helping a car dealership create an app that could provide the market value for a car. The grading for this project was not only model accuracy, but also the speed of training and prediction.

## Data Description

__Features__

DateCrawled — date profile was downloaded from the database

VehicleType — vehicle body type

RegistrationYear — vehicle registration year

Gearbox — gearbox type

Power — power (hp)

Model — vehicle model

Mileage — mileage (measured in km due to dataset's regional specifics)

RegistrationMonth — vehicle registration month

FuelType — fuel type

Brand — vehicle brand

NotRepaired — vehicle repaired or not

DateCreated — date of profile creation

NumberOfPictures — number of vehicle pictures

PostalCode — postal code of profile owner (user)

LastSeen — date of the last activity of the user

__Target__

Price — price (Euro)

## The Process

There was much EDA that needed to be done for this data, such as removing values that made no sense (some cars had 0 horsepower or over 1000), removing columns that made no sense (like postal code), and replacing missing values. We tested linear regression, decision tree, random forest, LightGBM, and CatBoost. Based on our metrics of speed and quality, LightGBM was the best model for our project with its lightning quick training and prediction times, along with the lowest RMSE of all models.

See the attached Jupyter Notebook if you would like to further dive into the steps I took on this project.
