# MELI_scraper
Web Scraping Mercado Libre Listings

This Python script is designed for web scraping data from Mercado Libre, an online marketplace in Argentina. The code uses various libraries and techniques to extract product information, including titles, prices, and URLs, from the search results pages.

Key Features:

Dynamic Page Crawling: The code begins by defining an initial URL based on a search query, allowing you to specify the items you want to scrape.

Data Accumulation: It maintains lists to store extracted data, such as product titles, URLs, and prices.

Pagination Handling: The script handles paginated search results by iteratively crawling through multiple pages using the "Next" button.

Data Cleaning: It cleans extracted data, such as replacing commas with spaces in titles and using regular expressions to extract numeric prices.

Error Handling: The code checks the HTTP response status code to ensure successful requests. It also handles scenarios where elements may not be found on the page.

CSV Output: The extracted data is written to a CSV file, allowing you to easily analyze and manipulate the information using other tools.

How to Use:

Set the item variable to your desired search query.

Run the script, and it will start scraping data from Mercado Libre.

The script will accumulate data from multiple search result pages, ensuring you capture a comprehensive dataset.

The extracted data will be saved to a CSV file named after your search query.

This script is a helpful tool for those interested in collecting product data from Mercado Libre for various purposes, such as market research, price monitoring, or building datasets for analysis.
