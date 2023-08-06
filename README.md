# Retail-Sales-Data-Analysis-Project

### Introduction

** Please see the Jupyter Notebook for the code and analysis

This project involves an in-depth analysis of a retail dataset that contains weekly sales data from various stores and departments over several years. The aim of the project is to uncover key insights that could help retailers make data-driven decisions to improve their performance and increase profits.


### Libraries Used

This project uses Python along with several data analysis and visualization libraries:

* pandas: Used for data manipulation and analysis.
* numpy: Used for mathematical operations.
* matplotlib: Used for creating static, animated, and interactive visualizations.
* seaborn: Used for statistical data visualization based on matplotlib.

I've included a requirements.txt file for using the same libraries. 

#### Acknowledgements
This dataset was obtained from Kaggle and used in this analysis. 
Link: https://www.kaggle.com/datasets/manjeetsingh/retaildataset

### Files in the Repository

There are three original files used for this project:

#### Features
Contains additional data related to the store, department, and regional activity for the given dates.
* Store - the store number
* Date - the week
* Temperature - average temperature in the region
* Fuel_Price - cost of fuel in the region
* MarkDown1-5 - anonymized data related to promotional markdowns. MarkDown data is only available after Nov 2011, and is not available for all stores all the time. Any missing value is marked with an NA
* CPI - the consumer price index
* Unemployment - the unemployment rate
* IsHoliday - whether the week is a special holiday week
#### Stores
* Anonymized information about the 45 stores, indicating the type and size of store

#### Sales
Historical sales data, which covers to 2010-02-05 to 2012-11-01. Within this file you will find the following fields:
* Store - the store number
* Dept - the department number
* Date - the week
* Weekly_Sales -  sales for the given department in the given store
* IsHoliday - whether the week is a special holiday week


#### Udacity - Retail Data Project.ipynb 
* This is the Jupyter notebook that contains the code for the data analysis and visualization.


### Results Summary

The analysis revealed several interesting insights:

Markdowns, which represent promotional activities, showed a moderate positive correlation with store size, suggesting that larger stores tend to run more promotions.
Sales varied significantly by store type. Store type 'A' had significantly higher total sales than store types 'B' and 'C'.
Sales were found to increase during holidays and at the end of the year.
Some departments significantly outperformed others in terms of average weekly sales.
Factors like unemployment rate and temperature did not seem to have a significant impact on sales.

These insights can help retailers make informed decisions about store operations, inventory management, and promotional activities.
