# web-Scraping
Web Scraping Flipkart Products Data.
This project is a web scraping tool to extract product data from Flipkart's search results for a specific search query.
It retrieves product information, such as product URLs, names, prices, ratings, and the number of reviews from multiple pages of search results.
It uses Python with libraries like requests and BeautifulSoup for web scraping.
Also incorporates Selenium for handling dynamic content, such as "Read More" buttons and other hidden details.
Built With
Python
BeautifulSoup
requests
Selenium
pandas
Features
Scrape product data from Flipkart search results.
Extract product URLs, names, prices, ratings,review counts,description,FSN,Product Description and Manufacturer details.
Supports scraping multiple pages of product listings.
Utilizes Selenium for handling dynamic content and hidden details.
Provides a basic framework for further data extraction from product detail pages.
Exports the basic product data to a CSV file.
Extract additional product details (e.g., description, FSN, manufacturer) from each product URL.
Updates the CSV file with the additional product details.
Prerequisites
Before running the application, make sure you have the following prerequisites installed on your system:

Python (version 3.x recommended)
Required Python libraries: requests, beautifulsoup4, selenium, pandas
   pip install requests beautifulsoup4 selenium pandas
Installation
Clone the repo
Navigate to the project directory.
Install Required Python libraries.
Run First web_scraping_1.py then Run web_scraping_2.py
Usage
Open the web_scraping_1.py file.
In the url variable, update the search query (e.g., bags) to the desired product category you want to scrape.
In the Pages_to_scrape variable, update the number of pages you want to scrape (e.g., 20).
Run the web_scraping_1.py script using Python.
This script will scrape product data from the specified number of pages and save the basic product data (name, price, URL) to a CSV file named Products_1.csv.
Now Open the web_scraping_2.py file.
Run the web_scraping_2.py script using Python.
The script will read the basic product data from the Products_1.csv file, visit each product URL, fetch additional product details (e.g., description, FSN, manufacturer), and update the CSV file with the additional information to a CSV file named Product_2.csv
