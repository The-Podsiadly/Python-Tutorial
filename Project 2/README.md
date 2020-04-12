# Stock Market Data Webscraping & Analysis
In this project, you are assigned a task to webscrape Yahoo! Finance for information about all the ticks in the stock market. The ticks can be found in the `Data.zip` file. So download that file and extract the content.

Scenario:
>  You are a junior Quant for a Hedge Fund. Your manager sends you a zip file with all the ticks your company manages. You are required to pull the ticks out of the zip into a single file for future use. After that, you're manager tasked you with scraping Yahoo! Finance to get the properties outlined in an email sent to you (they are stated in **Task**).

## How to begin
Begin by creating a folder for this project, extracting the files into a folder labeled **Symbols**, and open up a new window in Atom to begin coding.

Testing is the same as in the previous project.

For anything you don't know how to do, use Google. The answers should be hard to find. Trial and error is the best method to learn.

## Task
The program you will create must do the following:
1. Open up each file **regardless of their name** in the folder `Symbols`
1. Extract only the **Tick** from each file and remove duplicates
1. Save the ticks to a `.csv` file labeled `Managed-Ticks.csv`
1. Webscrape Yahoo! Finance using the following url convention: `"http://finance.yahoo.com/quote/" + tick + "/key-statistics?p=" + tick`
   1. I recommend using BeautifulSoup (BS4) for webscraping
   1. Webscraping begins with *parsing*
1. Collect the following information for **EACH** tick:
   1. Market Cap (intraday)
   1. Trailing P/E
   1. Price/Book
   1. Total Debt
   1. Current Ratio
   1. Forward Annual Dividend Yield
1. Save the data into a `.json` file that has the naming convention: `Data-[today's date].json`

Figure out how long it took the program to run.

**Currently, my program ran the fastest at: #**

## Requirements
In the program, you should have done the following:
1. Commented your code
1. Used a `try/except` method
1. Used `json.dump()`
1. Used *BeautifulSoup*
