# Pymaceuticals-Analysis

## Matplotlib - The Power of Plots

## Background

Pymaceuticals specializes in anti-cancer pharmaceuticals. In its most recent efforts, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer. In this study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. 

## Observable Trends
* In our first chart(bar chart) we can observe that among all the drug regimens tested on the **248** mice, **Capomulin** (230) and **Ramicane** (228) were tested on more mice as compared to drug regimen like Propiva(148). In addition, the pie chart shows that there are more male (125) than female (124) mice in the study.
* If we take a look at the correlation coefficient between mouse weight and tumor volume, we notice that **0.84** is a strong correlation which means that if a mouse gains weight, there is most likely going to be a increase in tumor volume for that mouse.This can be further observed on the scatter plot that compares average tumor volume and mouse weight for mice on Capomulin regimen
* Also, if we look at the line chart, we can notice that tumor volume of mouse **b742** which was treated with Capomulin considerably decreases as time (Timepoint) goes by therfore showing that the treatment is working.

## Table of Contents
* Data cleaning
* summary statistics
* Bar and Pie Charts
* Quartiles, Outliers and Boxplots
* Line and Scatter Plots
* Correlation and Regression

### Data cleaning
In this process, the two csvfiles were imported, combined abd duplicates were removed to have a clean Dataframe for the rest of the analysis.

### Summary Statistics
The summary statistics was generated using two methos, one using the groupby method and statistical funtion to generate the mean, median, variance, standard deviation, and SEM and the other usinng the aggregation method on single line.

### Bar and Pie Charts

Two identical bar charts were generated showing the total number of mice for each drug regimen during the study. This was done using DataFrame.plot and DataFrame.pyplot

Two identical pie charts were generated showing distribution of female versus male mice in the study. This was done using DataFrame.plot and DataFrame.pyplot

### Quartiles, Outliers and Boxplots

The final tumor volume of each mouse across four of the most promising treatment regimens was created: Capomulin, Ramicane, Infubinol, and Ceftamin. Afterward the quartiles, IQR, and potential outliers across all the four treatment regimens was quantitatively determined.

### Line and Scatter Plots
The line chart was generated for a selected mouse (b742) treated with Capomulin analyzing tumor volume vs. time point.

The scatter plot scatter plot of average tumor volume vs. mouse weight for the Capomulin regimen

#### A Box and Whiskers Plot
A box and whisker plot of the final tumor volume for all four treatment regimens was generated.

### Correlation and Regression
A correlation coefficient, and linear regression analysis was conducted between mouse weight and average tumor volume for the Capomulin treatment. A Plot of the linear regression model created on top of the previous scatter plot.




