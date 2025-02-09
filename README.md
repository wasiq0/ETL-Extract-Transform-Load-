# ETL Pipeline for Countries by GDP
Overview
This project extracts GDP data from a Wikipedia page, transforms it into a structured format, and loads it into a SQLite database for analysis. The data is also saved as a CSV file for further use.

## Technologies Used
Python for scripting
BeautifulSoup for web scraping
Pandas & NumPy for data processing
SQLite for database storage
## Workflow
Extract: Scrapes GDP data from Wikipedia using BeautifulSoup.
Transform: Cleans and structures the data using Pandas.
Load: Stores the cleaned data in a SQLite database and CSV file.
## Files
script.py: The main ETL script.
Countries_by_GDP.csv: Extracted data in CSV format.
World_Economies.db: SQLite database storing the GDP data.
