# Yahoo Finance Stocks Data Scraper

This project is a simple web scraper designed to extract data from Yahoo Finance's "Most Active Stocks" page. It fetches information about the most active stocks and saves it into a Pandas DataFrame for further analysis.
I did this project to test my skills on web scraping .

## How it Works

The scraper is built using Python and utilizes the following libraries:

- Pandas: For data manipulation and storage.
- BeautifulSoup (bs4): For parsing HTML content.
- Requests: For making HTTP requests to fetch web pages.

The script iterates over multiple pages of the "Most Active Stocks" section on Yahoo Finance. It extracts relevant information such as stock symbol, name, price, change, % change, average volume, market cap, PE ratio, and 52-week range. This data is then structured into a DataFrame for easy analysis.

## Modification

Originally, the script was designed to scrape data from a single page. However, it was later modified to handle pagination and scrape data from multiple pages. This ensures a more comprehensive collection of stock information.





