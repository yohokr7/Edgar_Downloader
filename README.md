# Edgar_Downloader
Downloading Financial Statements and Storing onto a SQL server
## Background
This Repository is an new version of my original and updated SEC- EDGAR scrapers. 
The original was a Jupyter Notebook that would scrape and analyze Microsofts Financial Statements.
My [second version](https://edgar-easy.herokuapp.com/) was a serverless single-page React/Flask application that would scrape and analyze any company.
## Project Overview
This third iteration is meant to automatically Extract, Transform and Load the financial statements and stock price movement of every company in the S&P 500.
It will dynamically design and create the SQL server and databases to store the information for further analytical use in the future.