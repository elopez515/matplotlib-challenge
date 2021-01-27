# Matplotlib Homework - The Power of Plots

## Background
In this homework assignment I'm starting a new job at Pymaceuticals Inc., a pharmaceutical company based out of San Diego, that specializes in anti-cancer pharmaceuticals. It is currently screening for potential treaments for Squamous Cell Carcimona (SCC), a commonly occuring form of Skin cancer.  

As a senior data analyst at the company, I've been given access to the complete data from their most recent animal study. In this study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. My task as a Senior Data Analyst is to compare the performance of our company's drug of interest, Capomulin, against the other treatment regimens and generate tables and figures neccessary for the technical report of the study.

## Analysis
* The first step was to clean our data by checking for any mouse ID with duplicate timepoints and if found to remove any associated data. 

* Using the cleaned data we: 
    
    * Generated a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.

    * Generated two identical bar plots using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` showing the total number of measurements taken for each treatment regimen throughout the course of the study.

    * Generated two identical pie plots using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` showing the distribution of female or male mice in the study.

    * Calculated the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Calculated the quartiles and IQR and quantitatively to determine any potential outliers across all four treatment regimens.
    
    * Using Matplotlib, we generated a box and whisker plot of the final tumor volume for all four treatment regimens and highlight any potential outliers in the plot by changing their color and style.

    * Selected Mouse ID (s185) which was treated with Capomulin and generated a line plot of its tumor volume vs. time point.

    * Generated a scatter plot of average mouse weight versus average tumor volume for the Capomulin treatment regimen.

    * Calculated the correlation coefficient and linear regression model between average mouse weight and average tumor volume for the Capomulin treatment. We then plotted the linear regression model on top of our previous scatter plot.

    * Wrote three observations based on the information gathered from the data and included them at the top of notebook.

