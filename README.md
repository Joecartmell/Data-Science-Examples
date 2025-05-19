# Data-Science-Examples
This repository contains various files from the data science bootcamp I took part in with University of Manchester (Hyperion Dev)

**Multiple Linear Regression Analysis of Ames Dataset:**
Within this jupyter notebook file I perform exploratory analysis of a dataset with house sale prices in Iowa with a variety of other factors. This dataset is 
*De Cock, D. (2011). "Ames, Iowa: Alternative to the Boston Housing Data as an End of Semester
Regression Project," Journal of Statistics Education, Volume 19, Number 3.*

Libraries:
Within this file I use numpy, pandas, matplotlib and seaborn for exploratory analysis of this dataset.
I used sklearn for LinearRegression analysis including scaling the data.
I use scipy.stats for some statistics analysis.

Brief Summary:
In this Jupyter notebook file i performed exploratory analysis of various factors within the dataset that could affect a houses sale price. I then choose two indepdendent variables (Ground living rea and Garage Area and one dependent variable (Sale price). I split the data into a train/test split with a ratio of 75:25. I create a multiple linear regression model that predicts sale price from my independent variables. I then plot these predictions graphically and assess the performance of the model. Following this I assess the colinearity of my indepdent variables to ensure the accuracy of the model.

**Decision Tree Analysis of Titanic Dataset**
In this Jupyter notebook I perform the machine learning technique of classification trees to predict categorical dependent variables. I use the sklearn library to create decision trees that predict the probability of survival using the Titanic dataset. I prune the trees to the optimum depth levels. I then use techniques of bagging, boosting and random forests, I compare the accuracy of these models.
Libraries:
Within this file I use numpy, pandas and matplotlib. I use sklearn for the majority of the decision tree analysis.

