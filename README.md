# Analyze-NYSE-Data-Project


Kaggle's New York Stock Exchange S&P 500 dataset

### Introduction

In this project we will analyze real life data from the New York Stock Exchange. You will be drawing a subset of a large dataset provided by Kaggle that contains historical financial data from S&P 500 companies. We have created a smaller subset of the data that you will be using for the project.

### Cleaning Up the Data

Change all the column names to have no spaces, but still be informative. This isn't necessary, but just a recommendation. Depending on what you do with the data in the future having spaces or special characters in the column names may not work nicely. You will see this in the next content on SQL.

The following information is included in the Project data NYSE file:
*	Ticker symbol: Stock symbol
*	Years: Number of years for which data is provided
*	Period ending
*	Total revenue
*	Cost of goods sold
*	Sales, General and Administrative expenses
*	Research and Development expenses
*	Other Operating expense items
*	Global Industry Classification Standard (GICS) Sector: Industry sector the company is categorized under (e.g., American Airlines with the ticker symbol AAL is categorized under Industrials.)
*	GICS Sub Industry: Sub-industry sector the company is categorized under (e.g., AAL is further categorized under the sub-category of Airlines industry.)

### Project Goals:
Here are the three tasks that you will complete in the final project.

#### Task 1:
a. Identify the question about the data that you will answer based on your data analysis, and include this in your slide presentation.

*	Your question should include at least one categorical variable (GICS Sector or GICS Sub Industry) and one quantitative variable (one of the financial metrics) and require the use of at least one of the summary statistics.
*	A tab within the Excel spreadsheet that you submit should include the summary statistics [measures of central tendency (e.g., mean, median) and measures of spread (standard deviation and range)] you used to answer your question.
*	Deliverable: Slide presentation, Spreadsheet with tab for Summary statistics

b. Your slide presentation should provide at least one visualization to help with your answer.

*	This visualization might be a bar chart, histogram, scatterplot, box-plot or other visual that you learned to make. Include your insights from the measures of center and spread and at least one numeric summary statistic in the description.
*	Deliverable: Slide presentation (includes visualization)

#### Task 2:

* Create a dashboard for a Profit and Loss Statement that calculates the Gross Profit, Operating Profit or EBIT for a company selected from a drop-down list.
*	Your drop-down list should pull historical fundamentals data to create the P&L Statement.
*	The P&L statement should include the Gross Profit, Operating Profit or EBIT values for all the years there is historical data available for that company in the dataset.
*	Deliverable: Spreadsheet with tab for Dynamic P&L statement

#### Task 3:

*	Create a financial model for a company (different from Task 2) of your choice that forecasts out the Gross Profit, Operating Profit or EBIT for two more years using three scenarios (Best case, Weak case and Base case).
*	Your assumptions for revenue growth, gross margin and operating margin should change for each scenario.
*	The forecasting model should be dynamic for the selection of the case (Weak, Base, Strong). However, the forecasting model can be static for the chosen company sticker symbol.
*	Deliverable: Spreadsheet with tab for Forecasting Model
