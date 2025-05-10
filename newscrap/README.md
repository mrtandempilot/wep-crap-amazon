# Amazon Product Scraper

This is a Python-based web scraper that extracts product information from Amazon product pages. The scraper collects data such as product title, price, rating, review count, availability, and description.

## Features

- Scrapes product data from Amazon product pages
- Saves data in both CSV and JSON formats
- Uses random user agents to avoid blocking
- Implements random delays between requests
- Error handling and data validation

## Requirements

- Python 3.7+
- Required packages (install using `pip install -r requirements.txt`):
  - beautifulsoup4
  - requests
  - fake-useragent
  - pandas

## Installation

1. Clone this repository or download the files
2. Install the required packages:
```bash
pip install -r requirements.txt
```

## Usage

1. Run the script:
```bash
python amazon_scraper.py
```

2. When prompted, enter the Amazon product URL you want to scrape
3. The script will:
   - Scrape the product data
   - Save it to both `amazon_products.csv` and `amazon_products.json`
   - Display the scraped data in the console

## Important Notes

- This scraper is for educational purposes only
- Be mindful of Amazon's terms of service and robots.txt
- Use appropriate delays between requests to avoid being blocked
- The scraper may need updates if Amazon changes their HTML structure

## Output Format

The scraper collects the following information:
- Title
- Price
- Rating
- Review Count
- Availability
- Description

## Disclaimer

This tool is meant for educational purposes only. Make sure to comply with Amazon's terms of service and robots.txt when using this scraper. The authors are not responsible for any misuse of this tool. 