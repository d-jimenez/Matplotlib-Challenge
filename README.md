# **Matplotlib-Challenge: Pymaceuticals**

## Overview

As a senior data analyst with Pymaceuticals Inc., an anti-cancer pharmaceutical company screening for potential treatments for a commonly occurring form of skin cancer, you are tasked with analyzing the complete data for the most recent animal study. The study consists of a total of 249 mice who were administered a veriety of drug regimens over the course of 45 days. The company is interested in Capomulin and its affect on tumor volumes as compared to other drug regimens. The **Pymeceuticals** analysis leverages python to merge, clean-up and visualize the data results.

## File Structure

The **Pymaceuticals** folder has the following structure:

Pymaceuticals:
- data
    - Mouse_metadatacsv
    - Study_result.csv
- main.ipynb

## Running the Script

1. Verify that the folder and file structure being used on your local directory matches that of the outlined file structure.

2. Open local machine Terminal/GitBash

3. Navigate to the appropriate **Pymaceuticals** directory where all of the folders and files are stored. 

4. Input the **jupyter notebook** command and execute in order to bring up the jupyter notebook online computational tool.

## Output

The final report includes each of the following:

### Observations and Insights
- A merged data frame of the mouse metadata and study results csv files.
- A count of the number of unique Mice IDs in the full data set: 249.
- A cleam data frame that removes any mice idea with inconsistent/duplicate data. 
- A count of the bumber of unique Mice IDs in the clean data set: 248.

### Summary Statistics
- A summary statistics table for the results study merged data frame using the groupby approach.
- A summary statistics table for the results study merged data frame using the aggregation methon.

### Bar and Pie Charts
- A bar chart showing the total number of measurements for wach drug regimen in the study using pandas .plot.
- A bar chart showing the total number of measurements for wach drug regimen in the study using matplotlib plt.bar.
- A pie chart showing the distribution of female and male mice in the study using pandas .plot.
- A pie chart showing the tdistribution of female and male mice in the study using matplotlib plt.pie.

### Quartiles, Outliers and Boxplots
- A data frame consistening of only the final timepoint measurement for each mouse on Capomulin, Ramicane, Infubinol or Ceftamin.
- A printout of the potential outliers for Capomulin, Ramicane, Infubinol or Ceftamin using a for loop method to calculate quartiles, IQR, lower bounds and upper bounds. 
- A boxplot of the final Tumor Volume for Capomulin, Ramicane, Infubinol or Ceftamin drug regimens.

### Line and Scatter Plots
- A line plot showing the change in Tumor Volume over time for mouse ID b128.
- A scatter plot showing the relationship of average Tumor Volume and average Weight for the time series data of Mice on the Capomulin Drug Regimen.

### Correlation and Regression
- A scatter plot showing the relationship of average Tumor Volume and average Weight for the time series data of Mice on the Capomulin Drug Regimen.
- A linear regression was performed on average Tumor Volume and average Weight to measure the correlation between the two variables. 
- A linear line as well as the line equation and correlation coefficient plotted on the same scatter plot. 

## Observations
Based on the Pymaceuticals script the following obervations were determined:
- Observation 1: Out of the 10 drug regimens, Capomulin outperformed all but one other druf within the study with nearly the lowest final average tumor volume and and standard deviation. Ramicane appears to be the most effective drug regimens, resulting in the smallest average tumor size with the sample also having the smallest standard deviation.
- Observation 2: Infubinol was the only data set that had an outlier falling below the lower bound, while the remaining three drug regimens produced results within the lower and upper bounds.
- Observation 3: There is a positive correlation between the mouse weight and the size of the tumor (the heavier in weigh the mouse is, the larger the tumor).
