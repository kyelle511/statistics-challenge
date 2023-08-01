# statistics-challenge
Module 5 Challenge Assignment
Matplotlib &amp; Pandas statistics and plotting methods
## Contributor: Katy Yelle
### Overview
For this challenge there is 'Pymaceuticals' folder which contains a data folder with two csv files (Mouse_metadata and Study_results) and a Jupyter Notebook script (pymaceuticals_working.ipynb). The Jupyter Notebook script prepares and cleans the data from the two csv files; generates summary statistics; creates bar charts and pie charts using both pandas and matplotlib; calculates quartiles, outliers and creates boxplots; creates a line plot and scatter plot; and calculates correlation and regression for a scatterplot for a anti-cancer drug study.

When preparing and cleaning the data I used (https://www.geeksforgeeks.org/find-duplicate-rows-in-a-dataframe-based-on-all-or-selected-columns/) to help find duplicated data and (https://www.shanelynn.ie/pandas-drop-delete-dataframe-rows-columns/) for the method of removing the duplicated data from the dataframe. 

Summary statistics were calculated two different ways and (https://pandas.pydata.org/pandas-docs/version/0.22/generated/pandas.core.groupby.DataFrameGroupBy.agg.html) was a useful resource for producing the summary statistics using the aggregation method. 

When calculating the quartiles and outliers, special thanks goes to Learning Assistant Mark (no last name provided) for helping me figure out the correct configurations on my dataframe merge. I found (https://pandas.pydata.org/pandas-docs/version/1.0.2/getting_started/intro_tutorials/03_subset_data.html) to be a helpful resource for creating the dataframe that focused on particular treatments. And additional thanks go to Learning Assistant Roberto Salaza for helping me understand the starter code notes which helped get the quartile and outlier calculations where they needed to be. 


#### Analysis
In our most recent study we were comparing the performance of Capomulin to 8 other drug regimens as well as a placebo over 45 days of treatment.  The 5 drugs with lowest average tumor volume (mm3) over the course of the study were: Ramicane (40.21),Capomulin (40.68), Propriva (52.32), Ceftamin (52.59) and Infubol (52.88). After comparing the number of Timepoints, we decided to focus our compairson on Ramicane, Capomulin, Ceftamin and Infubol since Propriva had much fewer data points than the other drug regimens. Of all the mice in the study, there were slightly more males (51%) than females (49%).  Of the top 4 identified treatments we compared box plots of the final tumor volumes (mm3) which showed that Capomulin and Ramicane were the two most promising treatments based on final tumor size. In graphing tumor size over the course of the study, we see that a Capomulin mouse had large decreases in size after day 20 and day 30. There is a strong positive correlation between mouse weight and tumor volume (mm3). 
