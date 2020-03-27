# Financial Data Analysis
In this project, you are going to use the following data sheets that are provided to extract averages, totals, and comparisons to get better insight of the data.

Scenario:
> You are a data analyst at a Hedge Fund and your manager just handed you 4 excel sheets from different dates. The data sets contain stock symbols from across the major stock indexes. Each symbol contains some data points. You are asked to analyze, manipulate, and send them a new excel sheet containing the analyzed data.


## Task
The program you will create must do the following:
1. Open each file **regardless of name**
  1. This means that you are to figure out a way to open up all the files, without specifying the file names individually (*I've said too much*)
1. Pull all the data out
1. Put them into an array
1. From the data, get the following information for each item (relative to the symbol):
  1. The average change in data over the timeframe
  1. The average of each data point
1. Get rid of items that are incomplete
1. Get the total number of symbols
1. Alphabetically organize the data using the fastest sorting method
1. Save the analyzed data into a `.csv` file

## Requirements
In the program, you must achieve the following requirements:
1. Use a **generator expression**
1. Catch errors using **try & except**
1. Comment your code

## Watch Out For
Things to watch out for:
1. Type errors
1. Insufficient data
