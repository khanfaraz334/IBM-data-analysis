# IBM-data-analysis
# House Sales in King County, USA
## About Dataset

This dataset contains house sale prices for King County, which includes Seattle. It includes homes sold between May 2014 and May 2015.

1. id	A notation for a house
2. date	Date house was sold
3. price	Price is prediction target
4. bedrooms	Number of bedrooms
5. bathrooms	Number of bathrooms
6. sqft_living	Square footage of the home
7. sqft_lot	Square footage of the lot
8. floors	Total floors (levels) in house
9. waterfront	House which has a view to a waterfront
10. view	Has been viewed
11. condition	How good the condition is overall
12. grade	overall grade given to the housing unit, based on King County grading system
13. sqft_above	Square footage of house apart from basement
14. sqft_basement	Square footage of the basement
15. yr_built	Built Year
16. yr_renovated	Year when house was renovated
17. zipcode	Zip code
18. lat	Latitude coordinate
19. long	Longitude coordinate
20. sqft_living15	Living room area in 2015(implies-- some renovations) This might or might not have affected the lotsize area
21. sqft_lot15	LotSize area in 2015(implies-- some renovations)

Download dataset from [here](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DA0101EN-SkillsNetwork/labs/FinalModule_Coursera/data/kc_house_data_NaN.csv)

## Steps followed - 

### Importing data

Import and deatils about data.

### Data Cleaning

Dropped the columns and replaced null values with mean. 

### Exploratory Data Analysis

Count, Box plot, Reg plot and correlation.

### Model Development

1. Fit a linear regression model to predict the price using different variables and measure R^2. 
2. Created pipelines also.

### Model Evaluation

1. Converted the data into train and test sets.
2. Fit a ridge regression to avoid overfitting and perform second order polynomial transform.

### Finally, Submitted the notebook after dealing with data cleaning and analyzing. You can find the notebook attached and here is the [link](https://github.com/khanfaraz334/IBM-data-analysis/blob/main/FINAL_PROJECT_House_Sales_in_King_Count_USA.ipynb)





