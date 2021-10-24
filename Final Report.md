# Introduction

# Amazon represents one of the largest marketplaces on the Internet. People use its services daily to order groceries, books, laptops, and even web hosting services. The aim of this project is to scrape laptop data from the amazon website then build a regression model to predict an approximate price for the laptop.

#


#


# Design

# The data set in this project is taken from the Amazon Online website. This data set presents the specifications of a laptop. However, data analysis was used to price predict.

#


# Algorithm

# The steps to analyse the data set are gathering data from the website within the needed URL. After that, Request the URLs to return the HTML code and save the collective data from the website within a CSV file. In addition, exploring data by using all the functions like info and describe. Then cleaning data by removing null values and duplicates as well as, removing any irrelevant data. After that, plot the graphs using seaborn modules from python. Finally, find the correlation between features and fit the Gradient Boosting Regressor model in order to find the best model that fits our data and also generalize on unseen data.

#


# Data set

#

|
# Brand
 |
| --- |
|
# Standing screen display size
 |
|
# Processor Brand
 |
|
# Processor Speed
 |
|
# RAM Size
 |
|
# Hard Drive Size
 |
|
# Hard Disk Description
 |
|
# Operating System
 |
|
# Item Weight
 |

This project will use a scraped data set from the amazon website then build a regression model to predict an approximate price for the laptop. We scrap around 500 pages from amazon then we merge it with the dataset from Kaggle.
#


#


#


# Used tools

The we will used tools provided as a module in pythons such as Pandas, Matplotlib, Seaborn NumPy, Beautiful soup, and Excel. The python libraries support multiple data analysis and cleaning methods to ensure the data is clean and ready to visualize.

**Result:**

| Linear Regression | Forest Regression | Gradient Boosting | Polynomial | Lasso | Ridge | ElasticNet |
 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 0.646 | 0.954 | 0.862 | 0.865 | 0.626 | 0.626 | 0.626 | **Training** |
| 0.582 | 0.738 | 0.710 | -26\*10^12 | 0.534 | 0.534 | 0.534 | **validation** |
|
 | 0.948 | 0.865 |
 |
 |
 |
 | **Feature Engineering-Training** |
|
 | 0.723 | 0.710 |
 |
 |
 |
 | **Feature Engineering- validation** |
|
 | 0.834 | 0.803 |
 | 0.543 | 0.545 | 0.559 | **Testing** |

# Conclusion

# After building different models Random Forest Regressor has the highest r^2 in both validation stage and testing stage removing unneeded columns has increased r^2 in Gradient Boosting Regressor but not in Random Forest Regressor.

# 
