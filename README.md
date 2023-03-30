

House-sales-in-northwestern-county
Experimental Design 

 Business Problem
 
 Data Understanding
 
 Data Preparation
 
 Data Analysis
 
Regression

 Observations and Recommendations
 
PROBLEM STATEMENT

Investigate various features that affect the house sales in Northwestern County and develop a prediction model which can give us a good prediction on the price of the house based on other variables.

ANALYSIS OBJECTIVES

investigate the data and find out features that affect the prices of houses and come up with a prediction model for the house prices.
Develop a list of recommendations for residents of Northwestern County on what to consider while buying a house

DATA USED

kc_house_data.csv

DATA PREPARATION

The steps taken to prepare the data for analysis were:
Dropping the columns that are redundant and not required for the analysis.
Checking for null values.
Dropping the columns with null values

MOST COMMON HOUSE

3 bedroom houses are most commonly sold followed by 4 bedroom.
For a builder having this data , He can make a new building with more 3 and 4 bedroom’s to attract more buyers.

FACTORS AFFECTING HOUSE PRICES

square feet which increases the price of the house
 location of the house influencing the prices of the house like at longitude  -122.2 to -122.4 sells houses at much higher amount.
Number of bedrooms the more the number the higher the prices
Number of bathrooms the more the number the higher the prices

PRICE VS LOCATION
![image](https://user-images.githubusercontent.com/122718035/227875665-29b89258-ee9d-4619-84ab-065219cb69b2.png)
BEDROOM VS PRICE
![image](https://user-images.githubusercontent.com/122718035/227875958-9c262f59-788d-410e-a267-bd5d27d46f3c.png)
REGRESSION

Simple Linear Regression

1.‘bedrooms’ vs ‘price’
2.‘grade’ vs ‘price’

Multiple Regression

1.‘bedrooms’,’grade’, ‘sqft_living’, ‘sqft_above’
2.‘bedrooms’,’bathrooms’, ‘sqft_living’, ‘sqft_lot’, ‘floors’, ‘waterfront’, ‘view’, ‘grade’, ‘sqft_above’, ‘sqft_basement’, ‘lat’, ‘sqft_living15’

Polynomial Regression

1.degree=2
2.degree=3

OBSERVATIONS AND RECOMMENDATION

Complex model 1 gives R-squared testing: 0.555
Complex model 2 gives R-squared testing: 0.672
Complex  model 3 gives R-squared testing: 0.759

Complex Model_3 gives us R-squared (testing) score of 0.759. From above reports, we can conclude that Polynomial regression for degree=2, is best solution.








