# Project Goals from QMD file for airport
## Goals/ Plans:
My goal is to see how passenger traffic has changed for 6 major airports around the world. I will create data visualizations to show how each airport increased/decreased in foot traffic throughout the years, and I will try to see if there are any trends for any of these airports.

The airports that I will be tracking:
1.Hartsfield-Jackson Atlanta International Airport (ATL)
2.Frankfurt Airport (FRA)
3.Beijing Daxing International Airport (PKX)
4.Dubai International Airport(DXB)
5.Dallas-Fort Worth Internation Airport (DFW)
6.Shanghai Pudong International Airport (PVG)

To do this:
I will collect data from the webpage
I will tidy the data with the columns airport, year, passengers
I will then create a comparison table having airport rows, year as the column 2020 - 2025 and then each cell will have the number of passengers in them.
Then I will create a plot to show the trend for each airport.

# Project Goals from QMD file for Monte Carlo Simulation:
## Goals:
Create a visualization that shows the different ways monte carlo numerical integration looks in different n =.

## Needs:

###Noun:
Function f(x)
R Script
ggplot
Random x and y values
Estimates
n - values
geom_point

###Verbs:
Define the function
Compute the area of rectangles
Generate the random samples for x
Look if point is above or below the area
Find the estimate
Do above steps for all n =
Create a plot with a curve

## Steps:
1. Gather the data
f(x) = -(x-4)^2 + 4
x bounded by 2 and 6
y bounded by 0 and 4
Rectangle area is (6-2) ( 4-0 = 16
2. generate the random points inside the bounded rectangle.
3. Using the seq function and the sample function we can generate decimal points for both y and x values.
4. after selecting n x and y values we can add it to a data frame.
5. We determine which values are under or over the curve.
6. Determine how much area is under the curve.
7. Multiply the area with the proportion to get the estimate
8. Repeat this experiment with different n values of 10, 100, 1000, 10000
9. Create the plots for this.
10. Add the estimate to each of the plots in the display
    
# Project Goals from QMD file for calcium.csv
## Goal The goal is to clean the calcium.csv dataset. We need to make it tidy. We then need to create a sumarry to get the mean. We finally compare the treatment group to the placebo group using a line plot.

## Needs

### Noun Rscript Calcium.csv pivotlonger tidyverse ggplot2 drop_na mean of each group on each year 

### Verb We will first remove the empty rows We will then tidy the data We will then summarize the dataset for each group during each year We will plot the mean ulnar calcium levels during each year for each group on a line plot

## Steps
Load the calcium dataset, calcium.csv Remove empty row of data Using pivot longer you can make it so that we create a column year and compare each result per person like that. Create column person number Create the treatment group and put the next 16 people in it. Do same thing with columns as the prior group for them Create a summary for this. Create a line plot to compare both groups to each other.

# Repo Goals
# GOALs:
The ultimate goal is to learn and practice basic things in Github. We want to be able to commit changes on a seperate branch, and then merge them onto the main branch. We want to be able to document our process via readme files.


# NEEDS:
Nouns:
Github account
QMD file
PDF file
Public repository
Dev branch
Create issues

Verbs:
Create issues
commit changes
Create detailed summaries for complex commits
Merge dev and main branches
upload qmd and pdf files
update the readme files


# STEPS:






Plans:
Create a branch called dev
Upload the files into the repo in the branch dev
Created a pull request for 4 ->
Merge dev with main
Commited the changes.
Updated the README in main to keep main up to date.

