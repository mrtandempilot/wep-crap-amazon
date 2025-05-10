# Amazon Product Scraper

A Python-based web scraper that extracts product information from Amazon product pages. This tool collects data such as product title, price, rating, review count, availability, and description.

## ⚠️ Important Notice

This scraper is for educational purposes only. Please be mindful of Amazon's terms of service and robots.txt when using this tool. The authors are not responsible for any misuse of this scraper.

## 🚀 Features

- Scrapes product data from Amazon product pages
- Saves data in both CSV and JSON formats
- Uses random user agents to avoid blocking
- Implements random delays between requests
- Error handling and data validation
- Multiple selector fallbacks for robust scraping

## 📋 Requirements

- Python 3.7 or higher
- Required packages:
  - beautifulsoup4
  - requests
  - fake-useragent
  - pandas

## 🛠️ Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/amazon-scraper.git
cd amazon-scraper
```

2. Create a virtual environment (recommended):
```bash
# Windows
python -m venv venv
venv\Scripts\activate

# Linux/Mac
python3 -m venv venv
source venv/bin/activate
```

3. Install required packages:
```bash
pip install -r requirements.txt
```

## 💻 Usage

1. Run the script:
```bash
python amazon_scraper.py
```

2. When prompted, enter the Amazon product URL you want to scrape
3. The script will:
   - Scrape the product data
   - Save it to both `amazon_products.csv` and `amazon_products.json`
   - Display the scraped data in the console

## 📊 Output Format

The scraper collects the following information:
- Title
- Price
- Rating
- Review Count
- Availability
- Description

## 🔧 Troubleshooting

If you encounter any issues:

1. Make sure all dependencies are installed:
```bash
pip install -r requirements.txt
```

2. Check your internet connection
3. Verify that the Amazon URL is correct and accessible
4. If you get blocked, try:
   - Increasing the delay between requests
   - Using a different user agent
   - Using a proxy service

## 📝 Project Structure

```
amazon-scraper/
├── README.md
├── requirements.txt
└── amazon_scraper.py
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## ⚠️ Disclaimer

This tool is meant for educational purposes only. Make sure to comply with Amazon's terms of service and robots.txt when using this scraper. The authors are not responsible for any misuse of this tool.
