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

Using the four most promising treatments and calculate the final tumor volume for each mouse. Calculate the quartiles and IQR and determine if there are any outliers across the four treatments. 

Create a box and whisker plot of the final tumor volume for the previous four treatment regimens, highlight the potential outliers by changing their color. 

Using one more treated with Capomulin, create a line plot of time points versus the tumor volume of that mouse.

Generate a scatter plot of mouse weight vs the average tumor volume for the Capomulin treatment.

Calculate the correlation coefficient and linear regression model of mouse weight and average tumor volume for the Capomulin regimen. Plost the linear regression model on the previous scatter plot. 

## Analysis
Ramicane and Capomulin as treatments were successful in reducing the volume of the tumor size during the trial period. Running these regimens under a longer study could prove even more success.

Ramicane and Capomulin also had a smaller Standard Deviation of their tumor size. This shows that the regimens produced more consistent results among the mice that they tested. The higher Standard Deviation numbers of the other regimens show a more sporadic result range amongst the mice in those groups.

In the Capomulin test group, the size of tumor strongly correlated with weight of mouse. Do larger mice produce larger tumors? Or, more then likely, the larger tumors will ultimately add to the total weight of their mice. Running these computations against the other regimen groups would help sus out this information

