# How to Price Your Listing and Get High Rating on Airbnb in NYC

## Background: 
Airbnb is one of the most popular global online marketplaces to provide hospitality services to both guests and hosts. It not only provides opportunities for hosts to determine price and other details for their listings, but also offer guests a place to rate and write comments for each listing.

## Objectives:
Give suggestions and predictions on price to Airbnb hosts given following scenarios:

Group A: People considering about getting  a new house/apt and put it on Airbnb

Group B: People having specific listings already

## Dataset Overview
Source: http://insideairbnb.com/get-the-data.html

Data Size: 49748; Number of Variables:106

## Strategy
### 1. Data Preprocessing & Feature Engineering: 
Remove rows with NaN, get dummy variables on categorical features, and add new features

### 2. Data Visualization
Give suggestions on purchasing a new property in NYC

### 3. Prediction
Perform linear regression and random forest on features related to price and rating

### 4. Feature Selection
Select important features to consider for improvements

### 5. Text Mining
Sentimental analysis and word cloud on 4 price&rating groups

### 6. Conclusion & Suggestions
Give suggestions on pricing and rating to be a Superhost


## Conclusions
### For people in group A, we have following 3 suggestions:
1. Location: in midtown or lower town Manhattan or brooklyn area that is near to Manhattan

2. Property types: loft or serviced apartment

3. Unit types: 2b2b, 3b2b, etc. (The ratio of number of bathroom to number of bedroom should be greater than or equal to ½)

### For people in Group B, we can give them suggested prices of their listings based on our models before and after having rating data.
If they want to get a higher price and rating, they have to be careful about accommodates, number of available days, distance to Time Square and whether it's entire house or not. 

Also, they can include “beautiful”, “neighborhood”, “home”, “spacious”, “great location”, etc. in summary to make their listings more attractive.



