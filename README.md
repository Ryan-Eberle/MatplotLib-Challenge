# MatplotLib-Challenge
Pymaceuticals Matplotlib visualization 
Background
What good is data without a good plot to tell the story?
So, let's take what you've learned about Python Matplotlib and apply it to a real-world situation and dataset:

## Overview

Well defined plots can vastly improve the story that data can tell. By plotting the results of a treatment regime of cancer tumors on a set of test mice, pharmaceutical companies can adjust their treatments to improve efficacy. The task is to provide detailed tables and figures for the technical report of the study. 

## Method
Before the analysis, check data for any dulipcate time points for any of the mouse ID's. Remove any data associated for any duplicates
Generate a summary statistics table of mean,median,variance,standard deviation, and SEM of the tumor volume for each drug treatment.
Generate a bar plot that shows the total number of mice for each treatment regimen throughout the course of the study. 
Generate a pie plot that shows the distribution of female and male mice in the study.

## Analysis


Calculate the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Calculate the quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens.


Using Matplotlib, generate a box and whisker plot of the final tumor volume for all four treatment regimens and highlight any potential outliers in the plot by changing their color and style.
Hint: All four box plots should be within the same figure. Use this Matplotlib documentation page for help with changing the style of the outliers.


Select a mouse that was treated with Capomulin and generate a line plot of time point versus tumor volume for that mouse.


Generate a scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen.


Calculate the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. Plot the linear regression model on top of the previous scatter plot.


Look across all previously generated figures and tables and write at least three observations or inferences that can be made from the data. Include these observations at the top of notebook.
