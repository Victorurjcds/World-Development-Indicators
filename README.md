# World-Development-Indicators
The World Development Indicators from the World Bank contain over a thousand annual indicators of economic development from hundreds of countries around the world.

life_expectancy_prediction.py: Analysis of Spain life expectancy over 54 years from 1960 till 2013. This variable fits with a linear model. Error in testing samples is lower than 2%. Finally I estimate life expectancy in 2015 based on http://www.worldlifeexpectancy.com/spain-life-expectancy data as testing value. Error metric is lower than 0.3%.
Archive prediction shows model.


life_expectancy_relationships.py: Find out feature relationships between World Bank dataset over Spain life expectancy. Accuracy model is up to 97%. Archive estimation shows regresion in a scatter plot. r2_cv and r2_test show R2 metric over cross validation and testing phase, respectively.


