# IBM-Applied-Data-Science-Capstone
# Clustering Analysis of Korean Restaurants in NYC
Using New York City's neighborhood geographical information as well as venues data pulled from Foursquare API to find meaningful clusters of Korean Restaurants in NYC.

## Background
New York City is the most populated city in the United States. It is also one of the most ethnically, linguistically, and culturally diverse cities in the world. About 36% of the city’s population are foreign-born; 800 languages are spoken in the city; dozens of ethnic enclaves have developed throughout its neighborhoods - from Little Guyana, Koreatown, Little India, Little Odessa, Chinatown, Little Australia, Little Poland to Little Italy.

More specifically, the City is home to more than 100,000 ethnic Koreans, which contributes to the New York metropolitan area containing the second-largest population of Koreans outside of Korea. Given its dense Korean population and a growing interest in K-food business worldwide, there are ample opportunities to expand Korean restaurant business in New York City.

## Aim
This project aims to build machine learning models to identify meaningful clusters by the density of Korean restaurants in NYC. Then, I will recommend the best location to open a Korean restaurant, based on areas with relatively smaller density of Korean restaurants and their proximity to the city center.

## Target Audience
This project will provide great insight for anyone - entrepreneurs, business owners, investors - who are looking to start or expand their Korean restaurant business in New York City.

## Data
### Data 1: New York City Neighborhood Data
I will collect the New York City Neighborhoods Data from https://cocl.us/new_york_dataset. This data contains a total of 5 boroughs and 306 neighborhoods as well as the latitude and longitude coordinates of each neighborhood in New York City.
### Data 2: Foursquare Location Data
I will use the Foursquare API to get all the venues in neighborhoods of New York City. Then, I will filter venues to only show Korean restaurants for data visualization and analysis.
