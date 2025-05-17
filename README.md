# Data-Science-Examples
This repository contains various files from the data science bootcamp I took part in with University of Manchester (Hyperion Dev)

**Multiple Linear Regression Analysis of Ames Dataset:**
Within this jupyter notebook file I perform exploratory analysis of a dataset with house sale prices in Iowa with a variety of other factors. This dataset is 
*De Cock, D. (2011). "Ames, Iowa: Alternative to the Boston Housing Data as an End of Semester
Regression Project," Journal of Statistics Education, Volume 19, Number 3.*

Libraries:
Within this file I use numpy, pandas, matplotlib and seaborn for exploratory analysis of this dataset.
I used sklearn for LinearRegression analysis including scaling the data.
I use scipy.stats for some staistics analysis.

Brief Summary:
In this Jupyter notebook file i performed exploratory analysis of various factors within the dataset that could affect a houses sale price. I then choose two indepdendent variables (Ground living rea and Garage Area and one dependent variable (Sale price). I split the data into a train/test split with a ratio of 75:25. I create a multiple linear regression model that predicts sale price from my independent variables. I then plot these predictions graphically and assess the performance of the model. Following this I assess the colinearity of my indepdent variables to ensure the accuracy of the model.
