# House Price Prediction using advance regression algorithms
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. 



## General Information

- Analysing and building a regression model which predicts the sale price is core to find most influencing factors in price of house 
- This will help US housing company to purchase house when the price is down in their new venture of Australian market by studying the behavior of people and other factors that is documented in csv

## Conclusions
- Univariate conclusion:
    - Number of years ago Garage built in the data is around 15-45yr

    - Number of years ago House built in the data is around 15-58yr

    - Most people have garage cars from 1-2
- Bivariate conclusion:
    - Features representing the  Lot Frontage, Lot Area, Basement square feet, first floor sq ft, second floor sq ft, garage area shows a linear relation with the sale price . larger the area, larger the price, which is also clear from our business knowledge

    - Streets with pave (if a house has road access) has a higher price

    - KitchenQual Excellent has greater price

    - MSZoning shows Residential Low Density and Floating Village Residential have higher price than Commerical place

    - If home is very new "Home was not completed when last assessed" then price is higher found from SaleCondition feature

    - If house has Roof of shed it has higher price
- Multivariate conclusion:
  - GrLivArea ,GarageCars ,GarageArea, TotalBSMTSF, 1st Flr SF and Full Bath have greater influence on target variable Sale Price


- Multiple Linear Regression Model Not so ideal as it causes overfitting
- Built ridge regression model with regularization, which performs better than the multiple linear regression model 
- Built Lasso regression model with regularization,which performs sligtly better than the ridge regression model keeping the model simple

 ![Metrics](https://github.com/jenilChristo/HousingPricePrediction/blob/main/Metrics.png)

 ## Technologies Used
- NumPy - version 1.21.6
- Pandas - version 1.1.5
- Matplotlib - version 3.2.1
- Seaborn - version 0.12.2
- scikit-learn - version 0.22.1.