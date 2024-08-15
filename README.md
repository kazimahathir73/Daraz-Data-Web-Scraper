# Daraz Data Web Scraping Bot

This project is a web scraping bot designed to collect product data from Daraz, a popular online shopping platform. The bot extracts various details such as product name, brand, price, seller information, and ratings for a given search keyword. The scraped data is then saved into a CSV file.

## Table of Contents
- [Features](#features)
- [How to Use](#how-to-use)
- [Example Output](#example-output)
- [Dependencies](#dependencies)

## Features
- Scrapes product details including name, brand, price, seller information, and ratings from Daraz.
- Saves the scraped data into a CSV file, named based on the search keyword.
- Handles static content loading using Selenium.
- Customizable to scrape data for any search keyword and multiple pages.


### Setting Up Chromedriver
Chrome Driver is provided in the repository. Version- 127.0.6533.119

## How to Use

1. **Configure Search Parameters:**
   - Open the `daraz_web_scraping_bot.ipynb` file in Jupyter Notebook or Google Colab.
   - Update the search keyword and page number as required.

2. **Run the Notebook:**
   - Execute all cells in the notebook to start the web scraping process.
   - The script will scrape the data and save it into a CSV file named after the search keyword.

3. **Access the Output:**
   - The resulting CSV file will be saved in the same directory where the script is executed.

## Example Output
After running the bot with the search keyword `smart tv`, you might get an output CSV file named `smart_tv_pages_1_daraz_data.csv`. The CSV will include columns like:
- `Product Name`
- `Brand Name`
- `Price`
- `Seller`
- `Seller Rating`
- `Product Rating`
- `Number of Reviews`
- `Questions and Answers`

## Dependencies
- `Python 3.7+`
- `Selenium`
- `pandas`
- `webdriver_manager`
- `csv`
