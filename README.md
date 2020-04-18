# House Price Prediction - King County Housing Dataset

This dataset contains house sale prices for King County, which includes Seattle. It includes homes sold between May 2014 and May 2015.


* id: This is unique identification number given to each house in the dataset.
* date: This is the date the house is added into the dataset and is in the format YYYY-MM-DD.
* price: Price of each house in US dollars.
* bedrooms: Number of bed rooms available in each house and the dataset has houses having number of bedrooms ranging from 0 to 33.
* bathrooms: Number of bed rooms available in each house and the dataset has houses having number of bedrooms ranging from 0 to 8.
* sqft_living: Area size of living room in square feet.
* sqft_lot: Total area of size of lot in square feet.
* floors: Number of floors available in house.
* waterfront: This is an indicator if the house is located on or beside a lake or beach. Possible values are 0 – indicating No and 1 – indicating Yes.
* view: Rating of view of city or lake or beach from house and is rated from 0 to 5.
* condition: Overall condition of house rated in the range 1 to 5.
* grade: Overall grade of house ranging from 1 to 12.
* sqft_above: The surface area of house in square feet above ground level.
* sqft_basement: The surface area of house in square feet below ground level or basement.
* yr_built: The year of house in which it is constructed.
* yr_renovated: Year in which house is renovated or remodeled.
* zipcode: It is a 5 digit zip code in which the house is located.
* lat: Geographical Latitude position of the house.
* long: Geographical longitude position of the house.
* sqft_living15: It is the average house square footage of the 15 closest houses.
* sqft_lot15: It is the average lot square footage of the 15 closest houses.


## Linear Regression

* Test MSE: 0.05734992205119554
* Test R2: 0.7940906065684659
* Cross Validation Score 0.05729623822771559

## Lasso

* Test MSE: 0.057354499503525475
* Test R2: 0.7940741716649995
* Cross Validation Score 0.05729320989719951

## Random Forest

* Test MSE: 0.03403000576598055
* Test R2: 0.8778185288640931
* Cross Validation Score 0.03331292331066567