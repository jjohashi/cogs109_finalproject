# Predicting Housing Values in California

#### Dataset
https://www.kaggle.com/harrywang/housing 
- This dataset has a total of 9 features; however, we are planning on using 8 of the features as predictors. There are 8 quantitative features: longitude, latitude, housing_median_age, total_rooms, total_bedrooms, population, households, median_income. We will be using the column titled “median_house_value” as the predicted (y) value. The dataset also has a total of 20640 observations. 
- Excluding one qualitative variable: ocean_proximity. We are not including this variable since it is qualitative and from initial correlation test has a pearson's r correlation of less than 0.05. 
- Features are created based on the value according to the district. The districts are just different areas in California. 

#### Goal
- Our goal is to find out what information about districts can help in predicting the median housing value of different districts in California. 

#### Modeling Method
- We will be using multiple linear regression since we have multiple variables that might effect the median housing values. 

#### Model Selection Plan
- We will be using forward stepwise feature selection which will allow us to fine tune our model to best predict the median housing value of different districts in California. A forward stepwise feature selection will allow us to see which combination of the 9 variables contribute most to median housing values.
